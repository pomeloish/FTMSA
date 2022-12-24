# FTMSA: Multimodal Sentiment Analysis with Focusing on Textual Modality

The codes for novel multimodal architecture FTMSA


### Setup the environment

```
conda env create -f environment.yml
conda activate ftmsa
```



## Dataset download

Download [CMU-MOSI](https://drive.google.com/drive/folders/1d0-itFK5HWe7hNW3ONk-p4R6Iv8e1pg8?usp=share_link) and [CMU-MOSEI](https://drive.google.com/drive/folders/1V40-UoxmFX5C9eCqtsatveAbAKWM0GEc?usp=share_link) datasets and place the contents inside the `datasets` folder.



## Run the code

step1: `cd  src`

step2: 
`python train.py --data mosi` to run on CMU-MOSI dataset

`python train.py --data mosei` to run on CMU-MOSEI dataset



## Contact

If there's any question, please email at pomeloish@gamil.com
