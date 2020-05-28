# Identifying-the-dance-form

This repo includes the solution of **HackerEarth Deep Learning challenge: Identify the dance form**

*Problem Statement* : This International Dance Day, an event management company organized an evening of Indian classical dance performances to celebrate the rich, eloquent, and elegant art of dance. Post the event, the company planned to create a microsite to promote and raise awareness among the public about these dance forms. However, identifying them from images is a tough nut to crack.

You have been appointed as a Machine Learning Engineer for this project. Build an image tagging Deep Learning model that can help the company classify these images into eight categories of Indian classical dance.

------------------------------------------------------------------------------------------------------------------------------------------

### Approach towards the problem 

Since the dataset provided is small, a CNN from scracth may result in low accuracy. Hence a pre-trained model is used and with the use of tranfer learning a decent accuracy is achieved.

I have used Resnet-50 as the pre-trained network.

Accuracy achieved : 82.05 % 

### Machine Learning Library used

[Pytorch](https://pytorch.org/tutorials/beginner/blitz/tensor_tutorial.html)
