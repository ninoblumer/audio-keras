bootstrap:docker  
From:tensorflow/tensorflow:nightly-gpu-py3


#---------------------------------------------------------------------
%environment
#---------------------------------------------------------------------
export PATH=/bin:/usr/bin:/usr/local/bin:/usr/local/cuda/bin:
export LC_ALL=C

#---------------------------------------------------------------------
%post
#---------------------------------------------------------------------

apt-get update -y && apt-get upgrade -y
	
#pip3 install --upgrade -I setuptools
pip3 install --upgrade keras 

	
pip3 install \
	jupyter \
	matplotlib \
	seaborn	\
	Image \
	scikit-learn \
	lxml \
	joblib \
	h5py \
	python_speech_features \
	sox \
	librosa \
	PyAudio \
	SpeechRecognition \
