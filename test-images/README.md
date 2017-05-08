## Test image data

This directory contains photographic data to be used for the Sea It Rise phone app.
Each directory has a different index location (e.g. Golden Gardens and Orcas Island) 
followed by a datestamp that reflects when the images were taken. These photos are in 
general taken by the Sea It Rise team to use in improving our collection user process 
and to provide test data from different handsets.

## Acquisition Protocol

So far (as of 2017-05-07) the basic process for collecting these images are the following:

1. Go to a location of interest (preferably a shoreline where the impact on sea level rise
will be obvious, or, alternatively, where the change will be easy to see in the image. Set
your smartphone camera to have "location" enabled.

1. Find a the high tide mark on the shoreline.

1. Take a series of pictures in portrait mode. Start with a photo of your feet, with your
body pointed directly "offshore". Take a series of photos that overlap until the waterline is 
in the center of the frame and/or you can see the horizon or far shore. This usually happens 
when your arms are at shoulder height.

1. At that same "height", take a series of portrait photos as you spin 360 degrees, with some overlap
  1. if possible or preferable, take 1 "regular" photo and then take a panoramic or photosphere
  photo at the same location. 
  
## Post-processing

This technique will allow for several different pieces of data. 
 * Different handsets record different EXIF data.
 * Different handsets have different resolution and/or pixel density
 * In order to properly "register" the photo we need both
   1. a world location (latitude, longitude, and, if possible, elevation) 
   1. details of f-stop and focal length
   1. handset orientation (from azimuth/gyro sensors)
 * Getting different shoreline locations (both high-bank as well as low-bank/estuary type) will 
 give us a better feeling for how our AR tech works in different situations
