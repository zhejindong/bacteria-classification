# Q&A - Capstone Project - Bacteria classification


## MODEL

### In the [project description](https://github.com/deibyrios/bacteria-classification/blob/master/README.md) that we got, it is mentioned that _"a deep learning classifier has already been developed to classify colonies from two species, K. pneumoniae and E. coli, which could be extended for the more varied dataset"_. Can we have access to such previous work?
Ans:

They suggested us to build a model from scratch. 

## DATASET

### The Dataset contains 3 types of folders with 3 different types of images: Serial, Streak and Control. What is the meaning / purpose of each of those? 
Ans: 

Diffrent ways to incubate bacteria

### Images in 'Serial' folders are annotated with numbers 1-9. Do those numbers correspond to different bacterial species?
Ans:

They are all the same

### Deep Learning models need hundred thousands images or more to be successful. Are there only 200 images available for training?
Ans: 

So far, we only got 200 pictures. 

### Folders in the Dataset are stamped with different times. Do images in the same type of folders (i.e. Serial) but with different timestamps, correspond to images of the the same bacterial colonies but taken at different times?
Ans: 

As long as the file names have same lable such as P1C1, they are the same bacteria 
 

## IMAGE pre-processing

### What type of images should we annotate (Serial, Streak, Control)? 
Ans:

Serial and Control are first choices 

### In our view, annotating the images will cause a DL model to learn from artificially modified images. At testing time, the model will then try to classify raw images (with no annotation) which will cause the model to fail. In past computer vision classification projects, we just use the name of the file to identify the class or put different classes in different folders. Could we fully understand why should we annotate the images?
Ans:

I think the annotation process just creates masks of the picture which will not mess up the raw pictures 
