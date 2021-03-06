# Deep Learning Project: Bird Species Identification


The proposal of this project involves building a simple mobile or web application that will allow both professional and amateur bird watchers to upload photos of birds, automatically identify the species in the photos, and contribute to the monitoring of bird populations at scale. By logging the location, time, and type of species, a database will be built up of when and where different types of birds can be found and as this is done across the country, an accurate representation of the nation’s bird populations will be built. The key component of the application will be the automatic bird identification feature which will be based on a computer vision model built on deep learning. This project focuses on the development of that computer vision model.

Multiple iterations of model types and refinements were tried to assess what would produce the most accurate results. Initial development produced a custom CNN model that demonstrated moderate results, with an accuracy of 60% on a sample of the dataset containing only 10 classes. Given the computational power required to train a custom CNN for a dataset at the scale of the NABirds dataset, the next part of the modelling phase explored transfer learning algorithms. After several iterations of different transfer learning models were tested, a final model with an accuracy of 72.5% based on MobileNet V2 was chosen. The final model integrated into an end-user app is sufficiently accurate to support NABCI-Canada’s goal of developing a comprehensive bird tracking system. 

Google Colab Pro was used to set up GPUs with the aim to fasten the speed of the code without affect the properties of the big dataset. 


## Dataset Link
https://dl.allaboutbirds.org/nabirds
