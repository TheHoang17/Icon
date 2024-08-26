<script setup>
const props = defineProps({
  width: String,
  height: String,
  color: String
})
</script>
<template>
  <svg xmlns="http://www.w3.org/2000/svg" :width="width" :height="height" viewBox="0 0 54 26">
    <g id="Group_1844" data-name="Group 1844" transform="translate(-744 -383)" :fill="color">
      <path
        id="Path_579"
        data-name="Path 579"
        d="M772.7,383h46a4,4,0,0,1,4,4v18a4,4,0,0,1-4,4h-46a4,4,0,0,1-4-4V387a4,4,0,0,1,4-4"
        transform="translate(-24.7)"
      />
      <text
        id="LIVE"
        transform="translate(754 402)"
        fill="#fff"
        stroke="rgba(0,0,0,0)"
        stroke-width="1"
        font-size="15"
        font-family="SegoeUI-Bold, Segoe UI"
        font-weight="700"
      >
        <tspan x="0" y="0">LIVE</tspan>
      </text>
    </g>
  </svg>
</template>
