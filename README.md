# icerepo
a repo for the icelab work

modified the initial google earth engine imports to conform to a list style described in the comments in "summer_water_export" Please use that as the reference, it has comments describing what I'm doing.

These will generate a number of export tasks that unfortunately have to be manually run from within the GEE UI. At some future point would be worthwhile to do this in python instead so that the process could be automatic.

The resultant files are pushed to a google drive folder and can be zipped up, downloaded, and moved over to compute canada from there and unzipped.

After unzipping (currently placing in /project/6008048/spectral/ICE) then can start up a cedar node with a GPU attached to do processing and model training. The processing piece need not use the GPU, but for ease of operation have done everything in a GPU container.

(continue after placing into final directories on spectral)
