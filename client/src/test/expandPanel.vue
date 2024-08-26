<script setup>
const props = defineProps({
  width: String,
  height: String,
  color: String
})
</script>
<template>
  <svg
    xmlns="http://www.w3.org/2000/svg"
    :width="width"
    :height="height"
    viewBox="0 0 22.403 16.195"
  >
    <g :fill="color">
      <path
        id="Path_569"
        data-name="Path 569"
        d="M906.81,202.45l.83.82a.875.875,0,0,0,1.25,0h0l7.21-7.21a.875.875,0,0,0,0-1.25h0l-7.21-7.21a.875.875,0,0,0-1.25,0h0l-.83.82a.887.887,0,0,0,0,1.26l.01.01,4.47,4.26H900.63a.892.892,0,0,0-.89.89v1.19a.892.892,0,0,0,.89.89h10.66l-4.47,4.26a.884.884,0,0,0-.04,1.25.077.077,0,0,1,.03.02"
        transform="translate(-893.96 -187.337)"
      />
      <path
        id="Path_570"
        data-name="Path 570"
        d="M895.12,188.49h1.16a1.161,1.161,0,0,1,1.16,1.16v11.57a1.161,1.161,0,0,1-1.16,1.16h-1.16a1.161,1.161,0,0,1-1.16-1.16V189.65a1.161,1.161,0,0,1,1.16-1.16"
        transform="translate(-893.96 -187.337)"
      />
    </g>
  </svg>
</template>
