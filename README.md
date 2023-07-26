# Listed_assignment

The model has been coded in colab.This model of lip sync creates a synchronization of a given audio and video files. Here i will be explaining in detail how the model works.

1.First step: 
First of all required dependencies, pre trained model and other requirements are called or installed.
In this step there is removal of the directory(rmdir) if it already exist as it may contain data which is not required, if the directory is not present the a new diretory is made(mkdir).
After creating the directory , the pre trained model by the Wav2lip is called for training of the model.
Then the GAN file is called and installed as it is used for the training and testing purpose of the ai model using the trained model by wav2lip.
Then using pip ffmpeg(for audio and video data) and other various requirments are installed.
Now important modules are called for different purposes in the model like html, base64, eval_js,numpy ,etc
Then using base64 and html the video to be uploaded is previewd in the colab.
This helps in installing the major part of the model and pre trained models.

2.Second step: 
In this step, the video to be synced is to be uploaded.Important modules like os(operating system),shutil(used to source code),moviepy.editor(for video file operations), html via ipython, base64,etc.
Now for uploading the video file, either you can upload it or use other path by uploading it to the colab and using that path as video path.
Now the uploaded video needs to be previewd in the colab, so html and js modules are used.

3.Thirst step:
In this step, the auido file to be synced is uploaded . Necessary python modules liks OS, Audio, etc are called. Then previous input audio present then those are removed.
The audio file can be upload directly or by using other path method where the file is uploaded to colab and then its path is used as audio path.
Ipython module is used to display in colab environment. After the file is uploaded it is stored into a dictionary and voice path is creted using the value in the dictionary. Then soundfile.write() is used to save the audio file in wav format.
Then audio is shown in the colab page after the process of uploading and runtime is completed.

4.Fourth step:
This is the final step of the model where the video after syncing using the wav2lip pretrained model is done. Here the model then runs the Pretrained Wav2lip model to produce a similiar synced video with auido file and then it is shown through the show.video() in the colab.

This model helps to sync video and audio files with respect to pre trained models from Wav2lip.
