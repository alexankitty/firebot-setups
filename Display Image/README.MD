# Firebot Webpage Display
By Alexankitty  
Gives a simple option to display an image with more finegrained control.

## Options
**URL**: Specifies the URL of an image to load
**Width**: Width of the image
**Height**: Height of the image
**Anchor**: Side of the overlay to anchor the image to
**X**: X Position  
**Y**: Y position  
**Duration**: How long in seconds it will display for.  

## For anchors use the following:
Top Bottom Middle for vertical (Y axis) position  
Left Right Center for Horizontal (X axis) position  
  
Ex: topright for the topright corner of the screen  
Ex: middlecenter for the middle of the screen  
  
Center positioning is based on top left positioning. Use a negative value to position in the opposite direction.  
Height, Width, X, and Y values all accept CSS Units, or if none are present are assumed to be px.  
  
Features incremented instantiation and cleanup. Won't conflict or alter already running displayed webpages.  
