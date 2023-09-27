# Bootstrap
containers hold rows and rows hold colum's
you can change colum sizes which maxes at 12 units. 
start with making header, main and footer containers
you can put as many rows as you want in a container and as many colum inside of a row
link:bs5 inside of <head>
<div class="container">
<section><section> - no styles 
<section class="row">
<div class="col-6">
Rows are automatically flexed
use <div><div> for all bootstrap elements and classes
container-fluid is to span the entire width of the screen because standard container tags have margin and padding
.col-#  is a shortcut to making a colum fast
<div class="col-6 p-1">- utility shortcut for padding goes up to 5
"m-4" is for margin utility shortcut also only goes up to 5
<p><p> tags are best for text on average
putting margin on the x axis can break bootstrap
bg-primary gives you a blue along with other names to bring up different colors within bootstrap css style sheet
fw-bold makes the text bold
text-light makes the text white
fs- makes the font size bigger or smaller
mb- is to remove or add margin bottom along with the other respecting "M" commands
align-items-center is a flex utility to center all text in the row
<button class="btn"> is to make a nicer looking button
section.row is the shortcut to make a row tag fully
ctrl+/ is to input a comment anchor
text-center centers the text/images
class="img-fluid" makes the images not exceed the colum size
rounded makes the corners of the image rounds the corners such as border radius inside of style.css
my-#  makes a margin on the y axis
col-12 col-md-4 col-lg-3 example of going from desktop to mobile viewport
d-none is a utility to hide elements
d-none d-md-block to make it where the element shows up once the viewport reaches the correct sizing.
sticky-top makes the header follow you down the page
A tags are used to put links onto words and put the link of the website inside of the href=""
order-# puts the order you want things in, in numerical order.
order 1 is first for mobile
order 1,2,3 and on up
put your style css at the bottom of the heading if you want to override the bootstrap
marquee makes items go side to side in animation
position: absolute;
position-relative

you can put rows inside of columns so they can bunch in a certain section

@media(max-width: 767px){
    .hero-image{
        background-image: url()
    }
}
ALWAYS PUT MEDIA AT THE BOTTOM OF STYLE SHEET
d-none d-md-block to switch between phone and desktop views when coming to certain text/icons
light house in dev tools is used to test asecibility ratings.