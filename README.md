# Shine Map MSAI Final Project

## Getting Started:

Check out `shinemap.ipynb` which has all the required functions and markdown describing the overall steps in the process.

You can take your own photos of an outdoor space and try it out for yourself. Save the photos into a directory and use the load function to load them up. Then you can walk through the next steps.

If there are lots of different surface types in the photo, consider manually setting a ROI (you can also draw a box using Opencv directly in the notebook) so that you can extract this and only perform plane fitting for lighting conditions on this specific area. This helps avoid the issue of reflective surfaces messing up the model.

That's it! Testing_notebook has a lot more code in it for troubleshooting if you're curious, but isn't really very different from the main notebook, so I recommend you just inspect that one.