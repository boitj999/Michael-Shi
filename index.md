# Object Detection with Raspberry Pi
This will serve as a brief description of your project. Limit this to three sentences because it can become overly long at that point. This copy should draw the user in and make she/him want to read more.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Michael Shi | Valley Christian High School | Electrical Engineering | Incoming Senior

![Headstone Image](https://github.com/BlueStampEng/BSE_Template_Portfolio/blob/4655d8c4b2f1d0fa5912511d0b39542520b9f88e/branding/BlueStamp-Engineering-Logo-White.png)
  
# Final Milestone
My final milestone was to create and train a model that could sucessfully recognize me and my borther's face. I did this by taking around 150 images of me and my brother and boxing the image using a program I downloaded. I then took the images and zipped them in a folder where I used google colab to train model. I then implemented the model with the original detecy.py.

[![Final Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612573869/video_to_markdown/images/youtube--F7M7imOVGug-c05b58ac6eb4c4700831b2b3070cd403.jpg )](https://www.youtube.com/watch?v=F7M7imOVGug&feature=emb_logo "Final Milestone"){:target="_blank" rel="noopener"}

# Second Milestone
My second milestone was to successfully download and run tensorflow lite, which is a tool that would help me use object detection. Most of my challenges in this project came from this milestone. This was probably due to a mix of my inexperience with raspberry pi as well as the difficulty of finding websites that could help me with the bugs I was facing. The first step to installing tensorflow lite was to download all necessary packages. While downloading the packages went pretty smoothly, I quickly found a problem when I was trying to run tensorflow lite object detection. 
The error was: 
incompatible function arguments. (arg0: tflite::python::task::core::BaseOptions, arg1: tflite::task::processor::DetectionOptions.
At first, I thought it was python version that wasn't compatible, so I tried changing the default version of pythong from 3.9 to 3.7. However, that didn't work as the error continued to show. After spending a long time trying to search for the solution, I finally stumbled upon this website:
https://discuss.tensorflow.org/t/problem-in-tensorflowlite-code-with-pyhton-and-flask-on-google-coral-dev-board-for-object-detection/10302.
I finally got tflite to work and it could detect everyday objects that it has in its database.

[![Second Milestone]()](https://www.youtube.com/watch?v=eXkOAw8vaN0&ab_channel=BlueStampEng "Second Milestone"){}
# First Milestone
  

My first milestone was to successfully set up my raspberry pi and have it run on my monitor. To do this, I first needed to download a raspberry pi imager on my mac. I then put an SD card into a card reader and plugged it in my mac. After successfully writing the operating systems on my SD card, I then proceeded to take it out of my mac and plugged it in my raspberry pi. While I recieved a wireless mouse and keyboard, I decided to not waste time on connecting it to my raspberry pi and used a keyboard and mouse of my own instead. I then found a moniter that nobody in my house used and attached the cable into my moniter and the raspberry pi. Finally, I had to give the raspberry pi power and plugged it accordingly. After a couple seconds, the raspberry pi home screen appeared. To end my first milestone, I decided to also set up the raspberry pi camera and get it to work. I enabled the camera through my raspberry pi's configuratons and then installed the actual camera on my raspberry pi.

[![First Milestone](https://www.youtube.com/embed/Wl_JNW2NZNI)](https://www.youtube.com/watch?v=Wl_JNW2NZNI&feature=youtu.be "First Milestone")Milestone 1 Video
