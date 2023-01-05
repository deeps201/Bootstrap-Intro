
### Create a simple HTML file and add Bootstrap’s CSS and JS. 
### Place the link tag in the head for our CSS and the script tag for our JavaScript bundle before the closing body.
          
        <!doctype html>
        <html lang="en">
        <head>
            <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-    GLhlTQ8iRABdZLl6O3oVMWSktQOp6b7In1Zl3/Jr59b6EGGoI1aFkw7cmDA6j6gD" crossorigin="anonymous">
          </head>
          <body>
            <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js" integrity="sha384-w76AqPfDkMBDXo30jS1Sgez6pr3x5MlQ1ZAGC+nuZB+EYdgRZgiwxhTBTkF7CXvN" crossorigin="anonymous"></script>
          </body>
          </html>
         
 
 # BREAKPOINTS
 
 * Small-sm
 * Medium-md
 * Large-lg

# CONTAINERS

          <div class="container-sm"></div>
          <div class="container-md"></div>
          <div class="container-lg"></div>
          
* FLUID CONTAINERS
          
          <div class="container-fluid"></div>
          
 # FLEXBOX
   
     <div class="d-flex p-2"></div>
     
 Note:Display utilities to create a flexbox container and transform direct children elements into flex items.
 
 * FLEX DIRECTIONS
 
          <div class="d-flex justify-content-start">...</div>
          <div class="d-flex justify-content-end">...</div>
          <div class="d-flex justify-content-center">...</div>
 
  Note:Use justify-content utilities on flexbox containers to change the alignment of flex items on the main axis.

 
 * ALIGN ITEMS
 
          <div class="d-flex align-items-start">...</div>
          <div class="d-flex align-items-end">...</div>
          <div class="d-flex align-items-center">...</div>
  
  Note:Use align-items utilities on flexbox containers to change the alignment of flex items on the cross axis.
  
  
  
  
  ##### Use the .flex-fill class to divide them into widths equal to their content while taking up all available horizontal space.
  
  
         *  .flex-fill
         *  .flex-sm-fill
         *  .flex-md-fill
         *  .flex-lg-fill
# IMAGES

* .img-fluid this applies max-width: 100%; and height: auto.
          
         <img src="..." class="img-fluid" alt="...">
          
 * Aligning Images         
          
          <img src="..." class="rounded float-start" alt="...">
          <img src="..." class="rounded float-end" alt="...">
     
      
# INPUT GROUP  
          
  It can extend form controls by adding text, buttons, or button groups on either side of textual inputs, custom selects, and custom file inputs.
          
          
          <div class="input-group ">
            <span class="input-group-text" id="">
            <input type="text" class="form-control" placeholder="" aria-describedby="">
          </div>
                  
                    
# MARGIN AND PADDING
                  
        * m for classes that set margin                
        * p for classes that set padding
                  
  * SIDES
          
        + t - ```for classes that set margin-top or padding-top```
                    
        + b - for classes that set margin-bottom or padding-bottom
                    
        + s - (start) for classes that set margin-left or padding-left 
                    
        + e - (end) for classes that set margin-right or padding-right
                    
        + x - X-Axis
                    
        + y - Y-Axis


          
          
       
       
       
       
       
       
       
    To display a content—like an image with an caption, consider using a <figure>.
          
         <figure class="figure">
         <img src= "..." class="figure-img img-fluid rounded">
         <figcaption class="figure-caption">captions for an image</figcaption>
         </figure>
              
       
       
       
       
   
          
          
          
         
