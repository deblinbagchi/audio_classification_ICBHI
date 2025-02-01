# audio_classification_ICBHI
Audio classification task on ICBHI data

You can directly use the evaluate_from_audio.ipynb file in Google collab and change the path to the model and input files. More info on these below.
Otherwise, you can also run the evaluate_from_audio.py file.

Please set up your environment as follows:

```
pip install -r requirements.txt
```
In order to test out the model, I am selecting the following audio files from the test set of the ICBHI dataset:

1) 102_1b1_Ar_sc_Meditron.wav ------> Original label "Healthy" (Can be found [here](https://drive.google.com/file/d/17xsE7LDLHPLWFjhojHg-KnhJL8RrucJp/view?usp=drive_link))
2) 104_1b1_Ll_sc_Litt3200.wav ------> Original label "COPD" (Can be found [here](https://drive.google.com/file/d/122NzoQqOhw3vyuJNdT1-Ea9iSlGmz-wG/view?usp=drive_link))
3) 109_1b1_Ar_sc_Litt3200.wav ------> Original label "COPD" (Can be found [here](https://drive.google.com/file/d/13iKngiwlrYYAT2jvRnlaUeZzoM3I_6Xw/view?usp=drive_link))


These files can be found at my Google drive. 
Please download the trained model from my Google Drive as well. The model can be found [here](https://drive.google.com/file/d/1EHXYuTQUbReQ6LuBltXWKTYzoRfR3OPU/view?usp=drive_link)


In order to test the model in your own environment, please open the file `evaluate_model.py` and change the path to the model in line 66
and the path to the audio file in line 63. Afterwards, run the file:

```
python evaluate_from_audio.py
```
