<script setup>
const props = defineProps({
  width: String,
  height: String,
  color: String,
});
</script>
<template>
  <svg
    xmlns="http://www.w3.org/2000/svg"
    :width="width ? width : 12.62"
    :height="height ? height : 12"
  >
    <g :class="[fill, stroke]">
      <path
        id="Path_593"
        data-name="Path 593"
        d="M301.86,394.07H296.2l-1.72-5.13a.626.626,0,0,0-.8-.37.616.616,0,0,0-.37.37l-1.72,5.13h-5.7a.615.615,0,0,0-.61.62.34.34,0,0,0,.01.1.563.563,0,0,0,.26.43l4.65,3.28-1.78,5.19a.612.612,0,0,0,.21.69.582.582,0,0,0,.35.15.733.733,0,0,0,.38-.14l4.54-3.24,4.53,3.24a.767.767,0,0,0,.39.14.532.532,0,0,0,.34-.15.6.6,0,0,0,.21-.69l-1.79-5.19,4.61-3.31.11-.1a.6.6,0,0,0,.06-.83A.579.579,0,0,0,301.86,394.07Zm-5.29,3.01a1.727,1.727,0,0,0-.63,1.99l.63,1.84-1.65-1.18a1.759,1.759,0,0,0-2.03,0l-1.66,1.19.64-1.85a1.755,1.755,0,0,0-.65-2l-1.77-1.25h2.16a1.755,1.755,0,0,0,1.66-1.19l.64-1.92.64,1.92a1.755,1.755,0,0,0,1.66,1.19h2.12Z"
        transform="translate(-285.28 -388.531)"
      />
    </g>
  </svg>
</template>
