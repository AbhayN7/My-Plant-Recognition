# My Plant Recognition

 In this project, the Jetson Nano will use the imagenet network and utilize transfer learning to be able to identify healthy types of plants. Being able to successfully identify a healthy plant in an individual’s possession allows them to be sure that their plant is healthy and is not dying. Furthermore, this information could help individuals focus on their healthy plant and find the ideal conditions for this plant to grow.
 
## The Algorithm

In order for the nano to detect healthy plants, it has to transfer learn. In order to start this process the nano has to be trained in order to detect these plants. Once it goes through the training stage, the nano goes through the validation stage. In this stage, the nano will test its accuracy in identifying each type of plant. One of these cycles is called an epoch. The more epochs the greater the accuracy. There is also one more stage called the test stage. This is not required for training the nano but helps the user to test out the accuracy of the detection. The code in the my-recognition file loads an image into the gpu/cpu and utilizes the recognition network to classify an image. Once the image is classified, the algorithm finds the object description and prints out the results. 

## Running this project

1. Download the Jetson Inference Library and Python3
2. Download the resnet
[View a video explanation here](video link)
