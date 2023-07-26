# Listed_assignment

the model has been coded in colab.
This model of lip sync creates a synchronization of a given audio and video files. 
here i will be explaining in detail how the model works.

First step: first of all required dependencies, pre trained model and other requirements are called or installed.
In this step there is removal of the directory(rmdir) if it already exist as it may contain data which is not required, if the directory is not present the a new diretory is made(mkdir).
After creating the directory , the pre trained model by the Wav2lip is called for training of the model.
Then the GAN file is called and installed as it is used for the training and testing purpose of the ai model using the trained model by wav2lip.
Then using pip ffmpeg(for audio and video data) and other various requirments are installed.
Now important modules are called for different purposes in the model like html, base64, eval_js,numpy ,etc
Then using base64 and html the video to be uploaded is previewd in the colab.
This helps in installing the major part of the model and pre trained models.

Second step: in this step, the video to be synced is to be uploaded.
Important modules like os(operating system),shutil(used to source code)
