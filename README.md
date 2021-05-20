# kaggle-Cassava-Leaf-Disease-Classification
NoteBook for the competition "Cassava Leaf Disease Classification" held in Kaggle. Private Leaderboard 369/3900(Top10%) Bronze Medal.    
The Competiton was held from November 20th in 2020 to February 18th in 2021.It is the first time for me to join the competition in Kaggle. Fortunately, I won the bronze medal in this competition.🤣
# solution
My final submission for the competition got 0.8980 on private datasets,which got 0.9039 on public datasets. but my best solution got 0.8987 on private datasets.`new_predict.ipynb` which would be up to Top7% on leaderboard.the code released on GitHub contains training part and testing part. 
Here are some trciks I used on my notebook:
- Data Augmentation,I tried some new methods such as mixup, cutmix(but it didn't work well) while using the traditional methods in `torchvision.transforms` and `albumentations`.
- K-fold cross-validation `k=5`
- Model Ensemble: EfficientB4 + Vision Transformer 
- Test Time Augmentation: I used `TTA=10` for every batch and calculate the mean probability for the result.
- AMP in pytorch for faster training
# Hope
In the competition, I learned a lot of methods for better performance and standard code style from other kaggler's wonderful ideas all over the world.I will keep on reading and learning new technique. Hope I can get better score next time!😃

 
