# COMPGI22 Deep Learning Coursework 4: In-painting task. 
For your last task, you have to use your (previously) trained models to in-paint: 1 missing pixel or a patch of 2x2 pixels in a MNIST image.

Datasets:
* One pixel missing: inpainting_data/2X2_pixels_inpainting.npy
* 2x2 patch missing: inpainting_data/one_pixel_inpainting.npy

They contain: cropped/missing pixel image and the ground truth(GT) image, that you need to reconstruct.

We also provide some scripts to load the data and check that everything when okay during pickling. 
(File an issue or post on moodle if any problems and we'll provide the datasets in a different form)
