# covid19_cxr_detection
DL based solution for [COVID19Action-Radiology-CXR](https://ieee-dataport.org/open-access/covid19action-radiology-cxr)<br>
Head over to the [`ps.txt`](https://github.com/Raghwendra-Dey/covid19_cxr_detection/blob/master/ps.txt) to read the problem statement.<br>
[`resnet_transfer.ipynb`](https://github.com/Raghwendra-Dey/covid19_cxr_detection/blob/master/resnet_transfer.ipynb) is the model which uses `resnet-18` pretrained model for transfer learning.<br>
[`conv-net.ipynb`](https://github.com/Raghwendra-Dey/covid19_cxr_detection/blob/master/conv-net.ipynb) is the model which uses `Vanilla Conv-net` model with self-built architecture for training.<br>
The Inference code and the saved model is also open sourced for community use. You can find and test it [here](https://github.com/Raghwendra-Dey/covid19_radiology_inference).<br>
I have also written a whitepaper explaining the detailed approach adopted by me to tackle various problems while solving this problem statement. Read it [here](https://github.com/Raghwendra-Dey/covid19_cxr_detection/blob/master/dlfa_proj2_whitepaper.pdf).<br>
This is the part of the final project for the course DLFA(Deep Learning Foundations and Applications) by prof. Debdoot sheet offered by Centre of Excellence in Artificial Intelligence, IIT Kharagpur.<br>
Got a <b>9/10</b> score for this project.<br>
NOTE: This project was done in the kaggle notebooks so all the file paths for loading the dataset, saving model, etc are according to the ones used in kaggle. You can find the kaggle notebooks [resnet-18 here](https://www.kaggle.com/raghwendradey/resnet-transfer) and [conv-net here](https://www.kaggle.com/raghwendradey/dlfa-proj-2).
