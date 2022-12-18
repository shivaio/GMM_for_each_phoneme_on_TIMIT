# ASR-GMM
Build a GMM for TIMIT dataset with different mixtures such as 2,4,8,16,32,64,256

Steps to Run:
1. Run pip install -r requirements.txt
2. Run python feature_extraction.py --n_delta=2 --timit=./TIMIT/TRAIN --preprocessed=False
3. Run train.ipynb
4. Run test.ipynb
