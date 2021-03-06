# Doodle-Recognition
# Problem
Doodle recognition is the problem of identifying a doodle’s category(the object it represents). For example given a doodle of a plane, can a model predict the category the doodle belongs to.
# Motivation For The Project
My motivation for choosing this project is two-fold. One is that doodle recognition enables me to learn and apply my deep learning skills. Since doodles have less complexity to them, as a beginner to deep learning, I thought it would be a good idea to start with this kind of simple data before going to train more complicated and layered images.
Secondly, the problem of doodle recognition is extremely important. As noted in a paper published by Stanford University on Doodle, “[beyond] just the scope of Quick, Draw!, the ability to recognize and classify hand-drawn doodles has important implications for the development of artificial intelligence at large. For example, research in computer vision and pattern recognition, especially in subfields such as Optical Character Recognition (OCR), would benefit greatly from the advent of a robust classifier on high noise datasets”. 
# Dataset Used
In this project, I take on the task of building models in order to perform doodle recognition. I use the Quick! Draw! Dataset, which is the world's largest doodling dataset containing over 50 million drawings each belonging to one of the 345 categories.
# How to use the code
In order to use the code, it is important to first load the dataset in the drive. 
To get the dataset, vist the link https://console.cloud.google.com/storage/browser/quickdraw_dataset/full/numpy_bitmap?pli=1
Download two files: full_numpy_bitmap_ambulance.npy and full_numpy_bitmap_angle.npy. 
Create a folder in the drive called ‘logistic dataset’. Import both these files in the drive. Once this is done, open the google collab code and mount the drive.
Now, follow the instructions in the Google Collab to run the code and get the desired results.
Note: I tried to load data into github but the data is too big.
