# Jquery image Slider #

# Simple responsive Jquery image Slider without using any plugin #

To display multiple images under a specific area generally we use controls like Carousel or Slider. It was noticed these Control majorly appears in main page. Here in the below app I am creating an easily configurable jQuery image Slider. To show you the demo here I am with 3 files index.htm, slider.js and main.css. Slider.js and main.css embedded in index.htm file. By simply copying the below files you can create your own free Jquery Slider.

# Technical description #
 
The logic I implemented here is so simple. In my HTML page I have 2 div’s. One is for slider images and the other one I am using for Auto Slide Show. In my first div I have a ul element. Under this in each li I am loading images using simple image tag from HTML. To customize my Jquery image slider better here I added 2 anchor tags for next and previous actions.

To maintain a healthy look and feel I have few CSS classes in style.css file. As it is a simple jquery slider the main logic is inside the js file. In js file I am with 4 variables. IndivisualSlideWidth and IndivisualSlideHeight are storing li width and height. NumberOfSlides storing total number of images I want to show in Slider. In TotalWidthOfAllSlides I am calculating and storing the total width of UL element. During slide show I am hiding the total length and showing each slide independently. After this in my js file I have 2 functions moveSlideLeft() and moveSlideRight(). These function are responsible for slides movement. To configure auto slider option under on change event of autoOptionCheckbox I am calling the moveSlideRight() function. Here for interval between each slide I declared 5000 milliseconds.

Developed by https://jharaphula.com/simple-responsive-jquery-image-slider/
