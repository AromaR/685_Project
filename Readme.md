Find Data Files here: https://drive.google.com/drive/folders/1VgA9lwvkvoLGUYJJV43vwKKQbPMvLU5q?usp=sharing
You must copy this folder over to your drive to be able to write into it, this link has only read permissions.
The   code   uploaded   to   Github   is   not   in it’s   most   clean   stage   but   the   data   processing   is   in   the   collab   notebook   called” Data_Processing_POMO_Sample”.  The en-tire side corresponding to baseline BERT is in ”POMO_Probing_refactored_bert_base.ipynb” and the side corresponding to TA-
CRED fine-tuned BERT is in ”POMO_Probing_refactored_bert_tacred.ipynb"
Code in the data processing can be modified to read in data from the original PoMo files to convert it to a format that can be used by our other two notebooks. This has already been done and those files are already present in the drive, thus one need not do that.
Do set the GPU in the notebook settings.
Run the Probing notebooks to go through each and every step, there are comments for most of the steps. Again the notebooks have a lot of commented redundant code I did not get time to clean up.
