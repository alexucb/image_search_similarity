# image_search_similarity

1. Here is a simple script to show how we can do image search using open-cv, by ImageHash and SIFT algorightm. 
2. This can be used to face-detection,  pornographic images detection, as well as many other applications where image similarity is needed.

Q&A:
If you have problem with AttributeError: 'module' object has no attribute 'xfeatures2d'.
Basically you need install opencv-contrib-python since starting from open-cv 3.0 SIFT is no longer free for business use.
But you can still twig a bit on top of that, it is no thing but a bunch of mathmatic programming.

https://stackoverflow.com/questions/37039224/attributeerror-module-object-has-no-attribute-xfeatures2d-python-opencv-2
