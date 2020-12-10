# My Digital Resume

## ToDo
- Add carousel for skills icons
- Make sure pages are responsive and scale to mobile
- Mobile view of resume

## Support Info

### Meta for scaling
<meta name="viewport" content="width=device-width, initial-scale=1.0">

### Include the below
<picture>
  <source srcset="img_small.jpg" media="(max-width: 600px)">
  <source srcset="img_medium.jpg" media="(max-width: 1500px)">
  <source srcset="img_large.jpg">
  <img src="img.jpg" alt="Image">
</picture>

### Size reference
/*code for mobile devices smaller than 600px*/
body { background-color: blue; }

/* Small devices (portrait tablets and large phones, 600px and up) */
@media only screen and (min-width: 600px) {
   body { background-color: red; }
} 

/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {
   body { background-color: green; }
} 

/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 992px) {
   body { background-color: yellow; }
} 

/* Extra large devices (large laptops and desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {
   body { background-color: orange; }
}