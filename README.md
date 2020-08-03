# covid19_cxr_detection
DL based solution for [COVID19Action-Radiology-CXR](https://ieee-dataport.org/open-access/covid19action-radiology-cxr) i.e. covid-19 detection using chest X-ray images.<br>

## Loss and Accuracy plots
![loss and accuracy plots](https://user-images.githubusercontent.com/45457947/89184742-df93f000-d5b6-11ea-8ece-22b9162f7d85.png)

## Relevant Files
Head over to the [`ps.txt`](https://github.com/Raghwendra-Dey/covid19_cxr_detection/blob/master/ps.txt) to read the problem statement.<br>
[`resnet_transfer.ipynb`](https://github.com/Raghwendra-Dey/covid19_cxr_detection/blob/master/resnet_transfer.ipynb) is the model which uses `resnet-18` pretrained model for transfer learning.<br>
[`conv-net.ipynb`](https://github.com/Raghwendra-Dey/covid19_cxr_detection/blob/master/conv-net.ipynb) is the model which uses `Vanilla Conv-net` model with self-built architecture for training.<br><br>
The [**`Inference code`**](https://github.com/Raghwendra-Dey/covid19_radiology_inference) and the saved model is also open sourced for community use.<br>
I have also written a [**`whitepaper`**](https://github.com/Raghwendra-Dey/covid19_cxr_detection/blob/master/dlfa_proj2_whitepaper.pdf) explaining the detailed approach adopted by me to tackle various problems while solving this problem statement.<br><br>
Got a <b>9/10</b> score for this project and <b>4/5</b> for the whitepaper and inference code.<br><br>
This is the part of the final project for the course DLFA(Deep Learning Foundations and Applications) by prof. Debdoot sheet offered by Centre of Excellence in Artificial Intelligence, IIT Kharagpur.<br><br>
NOTE: This project was done in the kaggle notebooks so all the file paths for loading the dataset, saving model, etc are according to the ones used in kaggle. You can find the kaggle notebooks [resnet-18 here](https://www.kaggle.com/raghwendradey/resnet-transfer) and [conv-net here](https://www.kaggle.com/raghwendradey/dlfa-proj-2).
