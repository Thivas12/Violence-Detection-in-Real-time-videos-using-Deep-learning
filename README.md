# Violence-Detection-in-Real-time-videos-using-Deep-learning

*	Investigated the dataset that contains videos that are classified as violence and non-violence. Firstly, visualized the data to get insights what’s happening. 
*	Extracted the frames from the video using Python’s OpenCV library. And I have created the dataset as a list and checked whether the length of the extracted frames is equal to the sequence length.
*	Used OneHotEncoding to convert the labeled data into vectors. And I have split the data into Train(90%) set and Test(10%) set.
*	Used a finely tuned MobileNetV2, to build the training model. 
*	Model accuracy was ~92%. No unusuality in confusion matrix.
*	The accuracy sustained at 92% while generating classification report.
*	Did a prediction in two ways, frame by frame and on whole video. 

For the dataset follow this Kaggle link : https://www.kaggle.com/datasets/mohamedmustafa/real-life-violence-situations-dataset
