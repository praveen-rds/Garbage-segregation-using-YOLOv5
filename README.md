# Garbage-segregation-using-YOLOv5
Garbage segregation has been a major problem for a while now particularly with major cities producing tons of waste at an increasing rate every year. It is important address this problem, one of  the best ways to do it is by treating waste materials to make it so that those materials can be reused or recycled. But the problem comes with the fact that every material in these wastes need to be treated differently and so they need to be segregated. The contemporary method of waste segregation is mostly manual. This method is very inefficient and time-consuming, Moreover it rises a lot of heath related siiues to the solid waste management workers. An innovative method to solve this problem is to implemet computer vision. This project implemented the latest YOLOv5s algorithm to segregate 5 different materials of waste, namely cardboard, paper, plastic, metal and glass. YOLOv5 was chosed for this task because, of its features like fast detection speed and small size while stiil having similar accuracy as other algorithms like YOLOv4. This task requires only the segregation of limited calsses while needing to perform the task on a large quantity of objects. So with YOLOv5's speeed, it fits for the task perfectly.

#### Tools and skills required for this project include:
- Python
- Pytorch
- TensorFlow
- OpenCV
- YOLOv5
- Deep Learning

The data used for this project is both one that is downloaded from kaggle "https://www.kaggle.com/asdasdasasdas/garbage-classification" and collected using the OpenCV library.

The code includes various blocks, which runs the pretrained YoloV5, Applying transfer learning to train the model using custom dataset, and to use the trained model on an image, a video file and on live video feed.
