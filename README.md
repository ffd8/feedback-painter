# feedback-painter
cc [teddavis.org](https://teddavis.org) 2020

-----
[p5.js](https://p5js.org) tool, sharing my love for visual feedback.  
wild artifacts and aberrations occur when rendering low-res.  

[https://feedback-painter.glitch.me](https://feedback-painter.glitch.me)

----
### guide:  
- select colors or pick a `random color`  
- draw with the mouse pressed, +/- add `splatter`  
- `zoom`, controls feedback in or out  
- `rotate`, spins feedback left or right  
- `resolution`, controls size of canvas (1/4 to full display density)  
- `clear` » the image  
- `export` » saves transparent png (size is based on resolution)  
- `feedback-painter` » this info.. hi!

----
### shortcuts:  
- [ m ] » toggle menu  
- [ i ] » toggle info  
- [ s ] » splatter  
- [ c ] » random color  
- [ g ] » random grayscale  
- [ b ] » toggle b/w  
- [ e ] » export  
- [ delete ] » clear  

-----
### videos
saved videos are .webm format. easily convert to an .mov using [FFMPEG](https://ffd8.github.io/cli-for-artists-and-designers/).  
- type 'ffmpeg -i' + spacebar, then drag + drop  webm file,   
- type '-c copy' + spacebar, and drag and drop the file again, changing the suffix to mov:  
`ffmpeg -i drag_inputfile.webm -c copy drag_inputfile.mov`