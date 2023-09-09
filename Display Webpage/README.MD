# Firebot Webpage Display
By Alexankitty  
Gives a simple MixItUp style option to display a webpage in the overlay.  

## Options
**URL**: Specifies the URL of a webpage to load  
**URLParams**: Specifies the URL parameters (everything after the ?)  
**Width**: Width of the frame  
**Height**: Height of the frame  
**Anchor**: Side of the overlay to anchor the html page to  
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
  
Features random instantiation and cleanup. Won't conflict or alter already running displayed webpages.  