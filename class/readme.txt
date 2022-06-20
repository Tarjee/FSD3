1. inline css 
2. Style tag
    p,div,button
    class name
    id 
3. external stylesheet
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
6. width height 

max-width
min-width
max-height
min-height

 7. Text :
 color : change text color
 text alignment :
 text-align 

 8. text-decoration : 
    - text-decoration-line 
       -overline
       -line-through
       - underline

    - text-decoration-color
    - text-decoration-style
        - solid
        -double
        -dotted
        -dashed
        -wavy
    - text-decoration-thickness

  - text-decoration(shorthand):text-decoration-line(required) text-decoration-color text-decoration-style text-decoration-thickness

 text-transfrom
   - uppercase
   -lowercase
   -capitalize

  text spacing
   - text indent
   - letter spacing
   -line height
   - word spacing
   - white space

  8. Fonts
    - font family
    - serif
    - sans-serif
    - monospace
    - cursive
    - fantasy
      Arial , Times, monospace(fall back font family)

      - font-style
        - normal
        - italic 
        - oblique


    - font-weight 

    - font-size 
        
font(shorthand) : font-style font-variant font-weight font-size font-family

9.Display:

  Block-level elements 
    div
    h1 -h6
    p 
    form 
    header 

  inline elements
    span 
    a 
    img 

 none:    

10.float : 
    - left 
    - right 
    - none 
    - inherit 


11. position:
   - static
        - top , bottom, left , right(can't change)
   -relative
   - fixed 
   - absolute 
   - sticky

12. units:
    absolute
    - cm 
    - mm 
    - in 1in = 96px
    - px 
    - pt 
    - pc 

  - relative
     - em 2 em 2 time size  2em 2* current font-size 16px 
     - ex x-height 
     - rem 1 rem = 16px 
     - vh - %
     - vw  - %
     = % 

     px 
     rem 
     % 
     em 

13. combinators :
      - descendent selector ( ) div p
      - child selector (>)       div > p 
      - adjacent sibling selector (+) div + p
      - general sibling selector (-) div ~ p 

14. pseudo-class 
     - element: hover ->mouse over 

     :frist-child 

15. pseudo-element

 selector::pseudo-element 
 ::first-line - block elements
     - font 
     - color 
     - background 
     - word-spacing
     - letter-spacing
     - text-decoration
    ::first-letter 

    ::after 

  16. display 
     Flexbox layout
     flex-direction : row,column,row-reverse,column-reverse

     axis :
     row row-reverse 
      main-axis 
      cross-axis 


      column column-reveerse 
      main-axis 
      cross-axis

flex: 

flex shorthand: flex-grow flex-shrink flex-basis
flex-flow shorthand : flex-direction flex-wrap 
flex-flow: column wrap 




  grid :
   grid-column : grid-column-start grid-column-end
   grid-area: grid-row-start / grid-column-start / grid-row-end /grid-column-end



   z-index:

  css Transition : start - end
  shorthand of 
  transition: transition-property transition-duration transition-timing-function transition-delay
  transition-delay
  transition-duration
  transition-property
  transition-timing-function

    ease - slow start then fast,  slow end - default
    linear - same speed
    ease in - slow start 
    ease-out - slow end 
    ease-in -out - slow start and end 

  css animations: start - end 






  