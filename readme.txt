1. inline css - 

CSS 
 <p style = 'color:red'> Text</p>

 p - called selector in css
 style - called attribute
 color : property
 red : value

1. color - change text color
    - color name
    -rgb
    rgb(red,green,blue)
    range for each color : 0 to 255
  3*  0 - no color : black 
   3*  255 - white color

    rgb(255,0,0)
    -hex
    #rrggbb
    rr - red
    gg - green
    bb - blue
    00 - ff
    0 - 9
    a - f
    #000000 - black 
    #ffffff - white 

    *aaa
    3 digit hex 
    #rgb 


    -hsl
    h - hue 
    s - saturation
    l - lightness
    0 - 360

    hue: 
    0 - 119 -red
    120 - 239 - green 
    240 - 360 - blue 

    saturation:
    0% - 100%
    0% - gray shade
    100% - full color

    lightness :
    0% - black 
    50% - mid range color 
    100% - white 



2. background-color : 

 opacity : 0.0 - 1.0
 rgba();
 rgb 
 rgba 
 0 - 255 - red -r
 0 - 255 - green -g
 0 - 255 - blue -b
 0.0 - 1.0 - alpha -a 
 a - alpha - 0.0 - 1.0

 background -image : url()

 background :


 3. border:
 
 
  border-style : border-top-style border-right-style border-bottom-style border-left-style
   - dashed
   - solid
   - double
   - groove
   - inset 
   - outset
   - dotted
   - ridge 
   - none 
   - hidden
  
border-width :

border-top-width
border-right-width
border-bottom-width
border-left-width
   - thin
   - medium
   - thick


   border-color
   border-top-color
   border-right-color
   border-bottom-color
   border-left-color


shorthand :
 border :
  border-width 
  border-style(required) 
  border-color

 border-radius : rounder corners


 margins:
  margin-top
  margin-right
  margin-bottom
  margin-left

  shorthand :
   margin : margin-top margin-right margin-bottom margin-left


5. padding: space inside elements