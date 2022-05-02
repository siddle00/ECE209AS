# ECE209AS Project - Spring 2022, Dept of Electrical & Computer Engineering, UCLA
Project concerning the ECE 209AS course offered during the Spring 2022 quarter at UCLA. This repository will consists the work done for the ASV spoof detection project

## Project Title 
Using Deep Learning models for Audio spoofing detection. The problem statement is a part of the Automatic Speaker Verification Spoofing and Countermeasures Challenge - https://www.asvspoof.org/ 

## Team Information 
1. Nithin Varma - nithinvarma@ucla.edu, UID - 005851269
2. Sidarth Srinivasan - sidarthsrini@ucla.edu, UID - 005629208 


## Github Repo URL 
All code changes will be pushed to the following repo - https://github.com/siddle00/ECE209AS 

## Github Pages 
https://siddle00.github.io/ECE209AS/ 


## Literature Study 

|  Paper/Article Link | Summary | 
| ------------- | ------------- |
| ***Core Papers i.e papers that are directly relevant to our work*** | | 
| Review Paper - https://arxiv.org/pdf/2102.05889.pdf | Summarising the architectures of 2019 asvspoof for LA and PA. Fusion algorithm is shown to have a better performance for logical Access systems , where the inputs are text to speech. Fusion is not as effective for Physical access. However, a slight modification of the Same called oracle fusion is shown to perform better for PA. |
| http://cslt.riit.tsinghua.edu.cn/~fzheng/PAPERS/2019/1911E_APSIPA_ASVspoof_CXL(ZF).pdf | Describes the implementation of CQT based MGT preprocesssing technique to improve the performance for physical access based spoofing attacks.|
| https://arxiv.org/pdf/1805.09164.pdf | Explores and compares four end to end deep CNN architecture for replay attacks detection (PA audio spoofing). Also explores the diversity in the data set as the results are quite different for evaluation dataset and development dataset.|
| https://ziqi.plus/papers/3174.pdf | Employed multiple feature extraction techqniues and applied a CNN + Residual architecuture| 
| https://arxiv.org/pdf/1911.01601.pdf | This paper gives a brief overview for the creation of asvspoof database both for Logical access and Physical access scenarios with various use cases.|
| Review Paper - https://www.asvspoof.org/papers/IEEE_J_STSP_ASVspoof.pdf | |
| ***Helper Papers - Enables us to understand the different concepts needed for the core paper. For example usage of CNN architectures for speech processing*** ||
|https://ieeexplore.ieee.org/document/6857341 | This paper shows that error rate reduction can be obtained by using convolutional neural networks (CNNs). It first presents a concise description of the basic CNN and explain how it can be used for speech recognition. And then further propose a limited-weight-sharing scheme that can better model speech features. The special structure such as local connectivity, weight sharing, and pooling in CNNs exhibits some degree of invariance to small shifts of speech features along the frequency axis, which is important to deal with speaker and environment variations. Experimental results show that CNNs reduce the error rate by 6%-10% compared with DNNs on the TIMIT phone recognition and the voice search large vocabulary speech recognition tasks.|
| https://arxiv.org/abs/1509.01626 | This article offers an empirical exploration on the use of character-level convolutional networks (ConvNets) for text classification. We constructed several large-scale datasets to show that character-level convolutional networks could achieve state-of-the-art or competitive results. Comparisons are offered against traditional models such as bag of words, n-grams and their TFIDF variants, and deep learning models such as word-based ConvNets and recurrent neural networks.|
| https://conference.scipy.org/proceedings/scipy2015/pdfs/brian_mcfee.pdf | This article discusses about the popular feature extraction methods such as MQCC, CQCC and Spectogram in python.|
| https://www.isca-speech.org/archive/pdfs/odyssey_2018/kinnunen18b_odyssey.pdf | Discusses the popular metric t-DCF used in the ASV spoof 2019 and 2021 datasets.|
| https://arxiv.org/abs/1502.03167 | Batchnorm as a regularizer | 
| ***Sundries + Project Knowledge*** | | 
|https://www.asvspoof.org/interspeech2019_slides.pdf | |
|https://arxiv.org/pdf/2109.00537.pdf| |
|https://www.asvspoof.org/asvspoof2021/asvspoof2021_evaluation_plan.pdf| | 



## Work Done 
1. Literature study was performed to explore different statistical and Deep Learning architectures that were applied to the problem. 
2. Based on the literature study, a combination of CNN + Sequential architecture such as GRU, LSTMs were found to be effective. 

## Work in Progress 
3. Implemetning a baseline model, a CNN based architecture with residual connections is being constructed. 
4. Code changes involving the architecture is pushed - https://github.com/siddle00/ECE209AS/blob/main/Architecture_def.ipynb 

## Goals for Week 6 and Week 7 
5. Finishing implementing the baseline model. 
6. Explore different feature extraction techniques such as MQCC, CQCC, Spectograms and create a permutation of architectures. 




