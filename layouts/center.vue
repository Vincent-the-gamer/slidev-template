<script setup lang="ts">
import { computed } from "vue";

const props = defineProps({
    background: {
        type: String,
        default: "",
    },
});

function resolveBgStyle(background?: string) {
    if (!background) return {};
    const isColor = background[0] === "#" || background.startsWith("rgb");
    return {
        background: isColor ? background : undefined,
        color: !isColor ? "white" : undefined,
        backgroundImage: isColor ? undefined : `url("${background}")`,
        backgroundRepeat: "no-repeat",
        backgroundPosition: "center",
        backgroundSize: "cover",
    };
}

const style = computed(() => resolveBgStyle(props.background));
</script>

<template>
    <div
        class="slidev-layout center h-full grid place-content-center"
        :style="style"
    >
        <div class="my-auto">
            <slot />
        </div>
    </div>
</template>
