With this library, you can make/draw virtualy on your screen

functions/classes:
	obtaincolor - It takes  hsv values(i.e [57,56,0,100,255,255]) and the corresponding bgr value(i.e blue,green,red) as a input
	and process the contours of the masked image. it also point out the center point of the detected object 
	
	getcontours - it takes images as a input. this functions helps the obtaincolor function to detects the contours and the
	center point of the contour (i.e outer bounders of a detected shap or object) 

	draw - this function takes coordinates of the detected object, bgr list to draw and an image. this function helps to draw the
	the color when detected object is moving
