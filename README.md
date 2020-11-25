# Image-Segmentation-

# Task :
This is Image Segmenation task on Indian Traffic Data.

# Data:
<pre>
1. You can download the data from this link, and extract it ( https://drive.google.com/file/d/1iQ93IWVdR6dZ6W7RahbLq166u-6ADelJ/view?usp=sharing )

2. All your data will be in the folder "data" 

3. Inside the data you will be having two folders

|--- data
|-----| ---- images
|-----| ------|----- Scene 1
|-----| ------|--------| ----- Frame 1 (image 1)
|-----| ------|--------| ----- Frame 2 (image 2)
|-----| ------|--------| ----- ...
|-----| ------|----- Scene 2
|-----| ------|--------| ----- Frame 1 (image 1)
|-----| ------|--------| ----- Frame 2 (image 2)
|-----| ------|--------| ----- ...
|-----| ------|----- .....
|-----| ---- masks
|-----| ------|----- Scene 1
|-----| ------|--------| ----- json 1 (labeled objects in image 1)
|-----| ------|--------| ----- json 2 (labeled objects in image 1)
|-----| ------|--------| ----- ...
|-----| ------|----- Scene 2
|-----| ------|--------| ----- json 1 (labeled objects in image 1)
|-----| ------|--------| ----- json 2 (labeled objects in image 1)
|-----| ------|--------| ----- ...
|-----| ------|----- .....
</pre>

# Approach:

For this task, I have implemented the research paper CANET. To know more about the architecture you can use this link https://arxiv.org/pdf/2002.12041.pdf .


I have created some small modules in my notebook and then combined the whole network at the end. 


The modules are : 
                  
                  1. Convolutional Block
                  
                  2. Identity Block

                  3. Feature Selection Module
                  
                  4. Global Flow
                  
                  5. Context Flow 
                  
                  6. Adapted Global Convolutional Network
                  
                  
This are the modules which used in the architecture for the segmentation task.


I ran for only 5 epoch but you can run for more epochs and you will get better result than me. You can see segmented images predicted by my model is in the end of the notebook.
