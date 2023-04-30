# ASR-Hacker
## Steps for running the code-
1) Upload "visual-acoustic-matching" in My_Drive section of your google drive
2) Upload ASR_Proj.ipynb on your google drive and open it with google colab
3) Change the runtime to GPU and run the cells in ipynb file
4) Make changes to the arguments for performing testing and inference on the code according to the information provided [here](https://github.com/facebookresearch/visual-acoustic-matching/tree/main)
## Results
For the as-is code in the ipynb file, we get-

RTE=0.1854 ; MOSE= 0.3704
## Contributions
1) Changed codes for dataloading in trainer.py & inference.py to make it compatible with google colab
2) Edited the Setup.py and corrected the dependency clashes
3) Removed many deprecated functions and replaced with their new versions
4) Made the ASR_Proj.ipynb to run all the scripts
5) Performed hyperparameter tuning and checked for issues in running the codes (96 hyperparameters present in trainer.py)
6) Made changes to avitar.py & base_avmodel.py to correct errors
7) Successfully tested the code on AVspeech dataset and performed inference using a pair of audio and video.

[Link to Colab Sheet](https://colab.research.google.com/drive/1asDGXRT2mPQM4yQQLluz60Vukhthkcyl?usp=sharing)
