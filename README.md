

## Train
* Download datasets from [here](https://drive.google.com/file/d/1B7ArHRBjt2Dx29a3A6X_lGhD0vDVr3sy/view).
* Download source domain model from [here](https://www.dropbox.com/s/qygkmpm6ez6bojd/source_model.pth.tar?dl=0) or specify the data path in `./train_source.py` and then train `./train_source.py`.
* Save source domain model into folder `./logs/source`.
* Download generated pseudo labels from [here](https://www.dropbox.com/s/opuz9pt78ng1yds/pseudolabel.zip?dl=0) or specify the model path and data path in `./generate_pseudo.py` and then train `./generate_pseudo.py`.
* Save generated pseudo labels into folder `./generate_pseudo`.
* Run `./train_target.py` to start the target domain training process.

## Acknowledgement
The code for source domain training is modified from [BEAL](https://github.com/emma-sjwang/BEAL). 
