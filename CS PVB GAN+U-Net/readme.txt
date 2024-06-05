1.Collect 120 images of speckle patterns with a topological charge of [1, -1], [2, -2], ..., [16, -16] respectively, for a total of 1920 images. Save these images in the "0-15" folders within the "speckle picture" directory.

2.Execute preprocess.py to generate training format data by concatenating the speckle pattern images with their corresponding target images. Save the processed data in the "PVBdata" directory.

3.Divide the data into training, testing, and validation sets. Randomly select images with a ratio of 8:1:1, and place them in separate folders named "train," "test," and "val" within the "PVBdata" directory.

4.Run train.py to start the training process.

5.After training is complete, the weight files will be saved in the "saved_models" folder.

6.Execute predict.py to generate predictions, and save the results in the "results" folder.