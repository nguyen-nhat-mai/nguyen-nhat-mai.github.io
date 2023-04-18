# COMPUTER VISION
### Satellite image semantic segmentation 

The task is to segment the objects (26 labels) in the satellite images. The dataset comprises 374 images (3x3000x4000) of residential neighborhoods in Houston after the hurricane Harvey. 299 out of the total images have corresponding masks (images where each pixel is assigned 1 out of 26 values corresponding to 26 labels). These are used for training deep learning models. The masks for the remaining 75 images are to be predicted. U-net, PSPNet & Deeplabv3+ are employed and evaluated using dice score. Deeplabv3+ outperformed with 72.65% accuracy. [[More...]](https://github.com/nguyen-nhat-mai/satellite-image-semantic-segmentation)

![image](https://user-images.githubusercontent.com/85484281/215187360-3b609176-daab-446c-9d89-7c7b87733686.png)

### CIFAR-10 Image classification

The mission is to build and try networks (based on popular deep learning network architectures such as VGG, Resnet, ...) on CIFAR-10 dataset to predict the class of the image. It is important to understand how data pre-processing, parameter changes and architecture of networks affect the performance. The popular CIFAR-10 contains 60,000 images of size 32x32. Each image belongs to 1 out of 10 classes (airplane, automobile, bird, cat, deer, dog, frog, horse, trip, truck). The evaluation metric is accuracy score. [[More...]](https://github.com/nguyen-nhat-mai/CIFAR-10-image_classification)

![image](https://user-images.githubusercontent.com/85484281/215329326-83096d2e-2be3-41e3-bf20-12b27bbc17da.png)

### Detection of dangerous objects from airport Xray images

As part of an ongoing corporate research project by ESSEC & CentraleSupelec with Deloitte, a deep learning model is being developed to detect dangerous objects such as gun, razor, knife, etc. using the X-ray images. The main objective of the project is to minimize human errors for Deloitte's airport clients in case of implementation and to provide a base model that Deloitte can adapt to other object detection tasks for use by other clients. [[More...]](https://github.com/nguyen-nhat-mai/object_detection)

![image](https://user-images.githubusercontent.com/85484281/215324696-54c4e149-7363-4ce1-915a-0a2875f2195f.png)

# NATURAL LANGUAGE PROCESSING

### Sentiment analysis

The objective is to build a classifier that can predicts opinion polarities (positive, negative or neutral) using language model given the clients' restaurant reviews and corresponding aspect categories. In this project, pretrain-bert was used to encode the text and fine-tuned (changing the final layer and trained for some epoches on this specific dataset) to build the complete model. The average accuracy achieved is 87.23% with standard deviation of 0.84%. [[More...]](https://github.com/nguyen-nhat-mai/sentiment_analysis)

### Fake news detection

The task is to employ traditional machine learning (ML) classification methods to mine the text and identify unreliable news. The dataset comprises 26,000 rows representing fake and reliable news. For each article, title, text, author and label are provided. ML methods employed are Support vector machine (SVM), Naive Bayes, Logistics regression, Knn and Decision tree. The performances of models are evaluated using accuracy score and running time. Naive Bayes proves to outperform in this case with 84% accuracy score and the least running time i.e. 0.11 seconds.[[More...]](https://github.com/nguyen-nhat-mai/fake-news-detection)

![image](https://user-images.githubusercontent.com/85484281/214878082-377fcd85-a8c0-46dc-99ef-06890d66d681.png)

# OTHERS

### Facebook friend recommendation system

### Ile-de-france apartment price prediction
Predicting house & apartment price is essential for the real-estate companies to remain profitable & competitive. Within the scope of this project, the client wants a robust model that can predict the price of newly constructed apartment in Ile-de-france. The records of mutations (ownership transfer) from 2014 to 2020 are provided by the client. Additional info such as the apartment geolocation, demographic & geographic info of the region are also used to feed the models. Among the models tried (Linear Regression, Decision Tree, Random Forest, Gradient Boosting & Extreme Gradient Boosting), Random forest got the best result on the final test set i.e. 85%. [[More...]](https://github.com/nguyen-nhat-mai/ile-de-france-apartment-price-prediction)
