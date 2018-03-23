## My academic project with Udacity's Machine Learning Engineer Nanodegree

In this project, I have built a pipeline that can be used within a web or mobile app to process real-world, user-supplied images.  Given an image of a dog, the algorithm will identifies an estimate of the canine’s breed.  If supplied an image of a human, the code will identify the resembling dog breed.  


### Instructions

1. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the relevant folder. Make sure the folder name and location are consistent with the paths specified in the dog\_app.ipynb file. 
2. Download the [human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip). Unzip the folder and place it in the relevant folder. Make sure the folder name and location are consistent with the paths specified in the dog\_app.ipynb file.  
3. Donwload the [VGG-16 bottleneck features](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogVGG16Data.npz) for the dog dataset. Place it in the relevant folder. Make sure the folder name and location are consistent with the paths specified in the dog\_app.ipynb file.
4. Obtain the necessary Python packages, and switch Keras backend to Tensorflow. The yml files below can be obtained from the [Project's Requirements folder on GitHub.](https://github.com/udacity/dog-project/tree/master/requirements)
	
	For __Mac/OSX__:
	```
		conda env create -f dog-mac.yml
		source activate aind-dog
		KERAS_BACKEND=tensorflow python -c "from keras import backend"
	```

	For __Linux__:
	```
		conda env create -f dog-linux.yml
		source activate aind-dog
		KERAS_BACKEND=tensorflow python -c "from keras import backend"
	```

	For __Windows__:
	```
		conda env create -f dog-windows.yml
		activate aind-dog
		set KERAS_BACKEND=tensorflow
		python -c "from keras import backend"
	```

