<template>
<svg id="usb" width="400" height="400">
    <rect id="metal-rect" x="300" y="120" rx="5" ry="5" width="70" height="60" style="fill:rgb(110,110,110);stroke-width:2;stroke:rgb(130,130,130)" />
    <rect id="top-rect" x="340" y="130" rx="2" ry="2" width="10" height="12" style="fill:rgb(110,110,210);stroke-width:1;stroke:rgb(130,130,130)" />
    <rect id="bottom-rect" x="340" y="160" rx="2" ry="2" width="10" height="12" style="fill:rgb(110,110,210);stroke-width:1;stroke:rgb(130,130,130)" />
    <path id="joint" d="M 370 150 L 360 150 L 360 155 L 350 155 L 350 150 L 320 150 L 320 155 L 300 155" stroke="rgb(130,130,130)" stroke-width="1" fill="none" />
    <text id="copyright" x="295" y="145" fill="rgb(130,130,130)" transform="rotate(90 320,150)" style="font: 10px monospace">K137-2019</text>
    <rect id="outer-rect" x="10" y="100" rx="20" ry="10" width="300" height="100" style="fill:rgb(40,40,40);stroke-width:3;stroke:rgb(60,60,60)" />
    <rect id="inner-rect" x="20" y="110" rx="18" ry="8" width="280" height="80" style="fill:rgb(10,10,10);stroke-width:2;stroke:rgb(20,20,20)" />
    <circle id="logo-circle-big" cx="260" cy="130" r="5" stroke="none" fill="rgb(40,40,40)" />
    <circle id="logo-circle-small" cx="275" cy="120" r="3" stroke="none" fill="rgb(40,40,40)" />
    <rect id="logo-rect" x="280" y="137" width="6" height="6" style="fill:rgb(40,40,40)" />
    <path id="logo-triangle" d="M 295 130 L 290 125 L 290 135 Z" fill="rgb(40,40,40)" />
    <path id="logo-top-line" d="M 260 130 C 275 130 265 120 275 120"  stroke="rgb(40,40,40)" stroke-width="1"
    fill="none" />
    <path id="logo-center-line" d="M 260 130 L 295 130" stroke="rgb(40,40,40)" stroke-width="1"
    fill="none" />
    <path id="logo-bottom-line" d="M 260 130 C 280 130 265 145 280 140" stroke="rgb(40,40,40)" stroke-width="1"
    fill="none" />
    <ellipse id="diode" cx="50" cy="150" rx="4" ry="8" style="fill:rgb(0,0,140);stroke:rgb(40,40,40);stroke-width:2">
      <animate attributeName="fill" values="rgb(0,0,140);rgb(0,140,0);rgb(0,0,140)" dur="5s" repeatCount="indefinite" />
    </ellipse>
    HTML5 SVG is here.
  </svg> 
</template>