<template>
 <svg width="200" height="340" viewBox="0 0 100 170"
    xmlns:svg="http://www.w3.org/2000/svg">
      <title>Lightbulb</title>

      <!-- the bulb -->
      <path d="M 0 50 A 50 50 0 1 1 100 50
                C 100 75 77 105 77 125
                A 10 10 0 0 1 67 135
                L 33 135
                A 10 10 0 0 1 23 125
                C 23 105 0 75 0 50 z"
        style="fill: #f9cb07; stroke: #999;"/>

      <!-- the bulb holder -->
      <g style="stroke-width: 4; stroke: #000; stroke-linecap: round">
        <line x1="33" y1="142" x2="67" y2="142" />
        <line x1="33" y1="150" x2="67" y2="150" />
        <line x1="33" y1="158" x2="67" y2="158" />
      </g>
      <path d="M 40 164 A 12 12 0 0 0 60 164"
        style="fill: #000; stroke: none" />
    </svg>
</template>