# internet-of-thing-lab

https://wokwi.com/projects/333796264659386964










































https://wokwi.com/projects/333796264659386964    {
  "version": 1,
  "author": "Anonymous maker",
  "editor": "wokwi",
  "parts": [
    { "type": "wokwi-arduino-uno", "id": "uno", "top": 144.18, "left": -51.62, "attrs": {} },
    { "type": "wokwi-rgb-led", "id": "rgb1", "top": -105.07, "left": 40.82, "attrs": {} },
    {
      "type": "wokwi-resistor",
      "id": "r1",
      "top": -18.62,
      "left": -64.83,
      "attrs": { "value": "1000" }
    },
    {
      "type": "wokwi-resistor",
      "id": "r2",
      "top": -17.55,
      "left": 129.39,
      "attrs": { "value": "1000" }
    },
    {
      "type": "wokwi-resistor",
      "id": "r3",
      "top": -25.02,
      "left": 303.34,
      "attrs": { "value": "1000" }
      
      
      
      
      https://wokwi.com/projects/333802336095830612<br>
    },
    { "type": "wokwi-rgb-led", "id": "rgb2", "top": -155.17, "left": -34.61, "attrs": {} },
    { "type": "wokwi-rgb-led", "id": "rgb3", "top": -120.49, "left": -199.91, "attrs": {} }
  ],
  "connections": [
    [ "rgb1:R", "r1:2", "green", [ "v0" ] ],
    [ "rgb1:G", "r2:1", "green", [ "v0" ] ],
    [ "rgb1:B", "r3:1", "green", [ "v-1.11", "h207.21" ] ],
    [
      "r1:1",
      "uno:A1",
      "green",
      [ "v-3.42", "h-102.31", "v413.82", "h321.35", "v-30.05", "h15.03" ]
    ],
    [ "r2:2", "uno:A2", "green", [ "v131.91", "h51.36", "v231.19", "h-67.04" ] ],
    [ "r3:2", "uno:A3", "green", [ "v0.67", "h39.24", "v388.39", "h-210.38" ] ],
    [ "rgb1:COM", "uno:3.3V", "green", [ "v150.15", "h-121.42", "v260.08", "h160.67" ] ],
    [ "rgb2:B", "rgb1:B", "green", [ "v-10.68", "h77.99" ] ],
    [ "rgb2:G", "rgb1:G", "green", [ "v-5.28", "h113.87", "v60.11" ] ],
    [ "rgb2:COM", "rgb1:COM", "green", [ "v0" ] ],
    [ "rgb2:R", "rgb1:R", "green", [ "v5.65", "h-12.72", "v43.93" ] ],
    [ "rgb3:B", "rgb2:B", "green", [ "v44.8", "h172.78" ] ],
    [ "rgb3:G", "rgb2:G", "green", [ "v88.35", "h170.52", "v9.25" ] ],
    [ "rgb3:COM", "rgb2:COM", "green", [ "v40.73", "h151.67" ] ],
    [ "rgb3:R", "rgb2:R", "green", [ "v56.51", "h153.74" ] ]
  ]
  
}



https://wokwi.com/projects/333796264659386964
