# Final Project Markdown
For my final project, I created an HTML Portfolio Website. This project took a lot of trial and error and some outside research. 
I started by making a new repository and naming it ajfinalport.github.io and I added a readme file with that text to make sure the website was routed correctly so it opened. 
I then thought about how I wanted my website formatted. I wanted there to be a header and an introduction paragraph. I then want to make a gallery of my songs that people can easily listen to. 
I also wanna show my sound design and any other stuff I have made. 

I started by making the header. I made it so the background color was red and put the font as times new roman. 

I then added a subheader that listed my job skills. However, I wanted to change it to be in italics so I looked it up on the w3schools.com website. This website was the main resource I used, it has so much helpful information. 

Next, I decided I wanted to upload an image to the header. 

https://www.youtube.com/watch?v=o5g-lUuFgpg&t=424s

I watched this youtube video which helped me to better understand how to use github to make my site and upload my photos. 

So I uploaded an "images" folder that had the picture I wanted to use. 

https://www.w3schools.com/html/html_images.asp

I looked up on the w3schools website about putting photos in HTML. 

**<img src="saxy.JPG" alt="aj playing sax">**

I entered this line of code however nothing showed up because I had the path wrong and had to change it to images/saxy.JPG

The photo was also really big and not centered so I had to figure out how to change that. 

I then changed the width of the image to 50% and added a margin-top, margin-left, and margin-right details which I read about on the w3schools.com website. https://www.w3schools.com/css/css_margin.asp
This helped me to get the photo centered. I had to try a few different numbers till I got it where I wanted it to be. I also added a solid black border around the photo.

Next, I decided to add an "about me section" next to the photo. I made another header in the body section and created the code in the top part. I tried to use "float" to try and padding to move it to where I wanted it to be however I was not able to get it to do what I wanted. 

I then went back to the w3schools website and read about grid containers and used that. https://www.w3schools.com/css/css_grid_container.asp 
      
        **.grid-container {**
            **display: grid;**
            **grid-template-columns: 1fr 1fr;**
            **max-width: 800px;**
            **margin: 20px auto 0;**
            **align-items: center;**

I had to make a few adjustments to the image code to get everything realigned and had to add the grid container to the body. 

The about me did not match the background color so I had to had add
**background-color: red;** 
I also added text align: center; to make it centered and not left. 

Once I was happy with how the header and the about me section looked, I moved on to the hard part which was creating my image gallery. 

https://www.w3schools.com/css/css_image_gallery.asp

I used this website to help me figure out how to do this. 

https://www.w3schools.com/css/tryit.asp?filename=trycss_image_gallery_responsive

I copied and pasted the code from here into my code and adjusted it as I needed to. 

The photos didnt show up at first because I had to fix the "href" path and I had to delete the width and height. 

I also later became frustrated because every time I clicked on the photos to try and play the audio it just opened another tab. That was because I needed to get rid of the <a target="_blank" href="doubletakes.png">. 

I then wanted to center the photos more. I tried to mess with the float setting in div.gallery but it didnt really do what I want so I decided to use a flexbox container. 

https://www.w3schools.com/css/css3_flexbox_container.asp I used this code for reference. and ended up with this 

      .gallery-container {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-wrap: wrap;
            padding: 30px; 
            margin: 0 40px 0 auto; 

This fixed my issue and then I decided to move on to make one of the photos play sound when clicked however, this ended up not being smart because it took me a very long time to figure out how to make a second row of photos. 






        







      









