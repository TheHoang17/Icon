<script setup>
const props = defineProps({
  width: String,
  height: String,
  color: String
})
</script>
<template>
<svg xmlns="http://www.w3.org/2000/svg" :width="width ? width : 18"
:height="height ? height : 18"> viewBox="0 0 20.91 15.999">
  <g :fill="color">
  <path id="Path_596" data-name="Path 596" d="M394.71,401.37a2.187,2.187,0,0,1-.58-1.43l-1.38.99.64-1.85a1.755,1.755,0,0,0-.65-2l-1.77-1.25h2.16a1.755,1.755,0,0,0,1.66-1.19l.64-1.92.64,1.92a1.755,1.755,0,0,0,1.66,1.19h2.12l-1.76,1.26a1.752,1.752,0,0,0-.53.65,2.546,2.546,0,0,1,.68.34c.27.18.52.38.77.57a14.147,14.147,0,0,1,3.86-4.57h-5.15L396,388.95a.626.626,0,0,0-.8-.37.616.616,0,0,0-.37.37l-1.72,5.13h-5.7a.615.615,0,0,0-.61.62.34.34,0,0,0,.01.1.563.563,0,0,0,.26.43l4.65,3.28-1.78,5.19a.612.612,0,0,0,.21.69.582.582,0,0,0,.35.15.733.733,0,0,0,.38-.14l4-2.86C394.83,401.48,394.76,401.42,394.71,401.37Z" transform="translate(-386.8 -388.541)"/>
  <path id="Path_597" data-name="Path 597" d="M399.47,401.11c.27-.55.5-1.02.73-1.48a12.426,12.426,0,0,1,4.86-5.22,9.184,9.184,0,0,1,1.61-.69.7.7,0,0,1,.92.4.737.737,0,0,1-.23,1.04,8.275,8.275,0,0,1-1.03.62,10.976,10.976,0,0,0-5.44,7.13,5.776,5.776,0,0,1-.29.89.794.794,0,0,1-1.32.2,3.194,3.194,0,0,1-.39-.57,7.644,7.644,0,0,0-2.62-2.71,2.007,2.007,0,0,1-.44-.38.682.682,0,0,1-.12-.83c.16-.32.38-.59.77-.52a2.544,2.544,0,0,1,.94.31c.57.39,1.09.84,1.62,1.28A5.4,5.4,0,0,1,399.47,401.11Z" transform="translate(-386.8 -388.541)"/>
</g>
</svg>
</template>
<script setup>
