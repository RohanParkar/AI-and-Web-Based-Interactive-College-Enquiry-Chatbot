# NLP_ChatBot
********************************** Instructions to run project ************************************** 

step 1: Download and Install Anaconda (https://www.anaconda.com/products/individual#windows)

step 2: (Optional) Only if you have Nvidia GPU download and Install CUDA 10.2 (https://developer.nvidia.com/cuda-10.2-download-archive?target_os=Windows&target_arch=x86_64&target_version=10&target_type=exenetwork)

step 3: Download Visual studio Code (https://code.visualstudio.com/)

step 4: Open Anaconda Promt and Execute following commands :
	
step 5:	conda create -n myenv python

step 6:	conda activate myenv

step 7:	conda install numpy

step 8: conda install -c anaconda flask

step 9: pip install Flask-SocketIO==4.3.1
	pip install python-socketio==4.6.0
	pip install python-engineio==3.13.2

step 10: Now to install pytorch : 

	If you have Installed CUDA toolkit 10.2 Execute following command :

		conda install pytorch torchvision cudatoolkit=10.2 -c pytorch

		                     Else 

		conda install pytorch torchvision cpuonly -c pytorch

step 11: Now to install nltk execute :

	pip install nltk

	(After installing nltk, Open python in anaconda promt by typing "python")
	(Once python is open exectue following commands in it)

	import nltk 
	nltk.download('punkt')
	exit()

step 12: Unzip the proejct folder in C drive 

step 13: Open Anaconda promt and activte mynev then navigate to proejct Folder.

step 14: Now exectue "Code ." in Anaconda promt it will open Visual studio Code in that folder.

step 15: Now select (python conda:myenv) to run code train.py 


************************* Run Project **********************************

Run on Visual studio Code
...
train.py
```
This will dump `data.pth` file. And then run 
...
chatbot_final.py
...
Now run 
...
chatup.py
...
This will provide you link by which you can open the chatbot on browser:
