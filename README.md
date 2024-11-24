# Human_Actitvity_Detection

1. Data Pre-processing - The information was gathered from the KTH-50 Dataset. The accuracy of the intended system is directly influenced by the quality and amount of data collected. We understand and clean data in this step.
2. Frame Extraction - In this step, for each of the videos, we extract equally spaced frames, resize the frames, and normalize the resized frames of the video.
3. Dataset Creation – We take frames from each video and extract features and labels to create dataset, i.e. indices of the class associated with videos and paths of the videos in the disk. We use the above data to fabricate our dataset.
4. Split Data (Train and Test) - The dataset is divided into two parts: training and testing.
5. Training Model - The training dataset is input into CNN and LSTM sequentially to generate an LRCN model .
6. Result - We train the LRCN models on the created dataset and compare the performance of both the models by classifying random YouTube videos.
