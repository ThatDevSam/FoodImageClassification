# FoodImageClassification

In this case study I acted as a data scientist at Clicks, a stock photography company. Clicks allows photographers from all over the world to upload food related images for people and companies to download. Due to a high daily volume of uploads, manually labeling and auditing each picture is difficult for a team of associates to do. The goal of this case study is to automate the process.

The CNN is able to classify the test set food image correctly **87%** of the time. I was able to increase the accuracy, up from **72%**, by experimenting with the network's architecture, adding in dropout layers, and manipulating the epochs and batch sizes. One particularly impactful lesson I learned during this case study was that the batch size of the model can remarkably influence its success.

### Business Applications:
* One key application of image classification is content moderation. The ability to efficiently analyze and flag images that do not align with a community's guidelines is an invaluable tool for today's social media sites.
* Another prominent application  of image classification is security. For example, enabling law enforcement to accurately identify weapons in images and video is more important now than ever before.

### Strategies for improving the model's performance:
* Explore techniques for addressing the class imbalance like over sampling/under sampling or creating synthetic data for the minority class.
* Apply data augmentations like rotations or flips.
* Continue to tinker with the model's architecture by adding more dense layers, manipulating the kernel filters in the convolution layer, applying batch normalization layers, or adding in regularization.
