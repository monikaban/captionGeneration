# captionGeneration
Exploring Image Captioning using VGG16 and LSTM

Objective is to generate automatic description for images using deep learning caption generation model.  

Please refer captionGenerationProj.pynb for complete details


The sequence of execution of files 

1. featureExtraction.py -> generates feature.pkl
2. textDataPrep.py      -> generates descriptions.txt
3. loadData.py 
4. modelFitProgressiveLoad.py -> generates 20 model files : model_*.h5
5. evaluateModel.py
7. prepareTokenizer.py   -> generates tokenizer.pkl
8. predictImage.py

Note : feature.pkl and all model_*.h5 files are not uploaded due to upload size limitations on github(25 MB max)
Flicker8k_Dataset: Contains 8092 photographs in JPEG format. Complete dataset can be downloaded from  https://illinois.edu/fb/sec/1713398

