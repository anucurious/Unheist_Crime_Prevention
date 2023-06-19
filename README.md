# Unheist_Crime_Prevention
UNHEIST 
 A CRIME PREVENTION TECHNIQUE USING MEDIA PIPE AND OBJECT DETECTION FROM COMPUTER VISION INTEGRATED WITH MACHINE LEARNING AND DEEP LEARNING 

 Abstract: 

The rate at which crimes are growing in society today is disturbing, and this is a major reason for worry for people all over the world. These days, it seems ineffective to use traditional crime-solving methods. There are various categories into which crimes can be divided. The main topic of this endeavor is bank heists and ATM robberies. 

The project's only goal is to ascertain how government authorities and law enforcement agencies may employ a combination of computer vision and machine learning algorithms to successfully detect and prevent crimes. 

This project is issued in the interest of the security of the public’s hard-earned money. 

This project uses computer vision principles and sends alerts to the security personnel present at the scene and the police who are near the locality. The libraries used are media pipe and object detection using yolov5. The emotional recognition component uses CNN principles to detect anomalies.  

To train the model we will use machine learning principles and deep learning. The model is enhanced with behavior analysis to detect the robbery without the weapons. 

Keywords:  Crime prevention; Machine Learning; Deep learning; Real-time monitoring; Computer vision, CNN.  


Introduction: 

In the current scenario, crimes are increasing in society at an alarming rate and have become a serious cause of concern all over the globe.​ Old crime-solving techniques seem inefficient these times. Crimes can be classified into a number of categories. This project focuses majorly on bank robbery/heist. ​ 

The sole purpose of the project is to determine how a combination of computer vision and machine learning algorithms can be used by officials and police to detect and prevent crimes effectively.​ 

As per the statistics given by Canada, out of the bank robberies that have taken place a quarter of them are unsolved. By the report given by Arizona State University, 80% of the stolen money is never recovered. 

Times of India says that Data analyzed by the crime branch of ATM break-ins in the past three years has revealed that more than half of them remained unsolved. 

These are statistics that are shocking and need to be addressed.  

The main objective of this project intends 

1. To reduce the crime rate.​  

2. It moreover increases the security of people.  

3. The project ultimately is for capturing criminals in a faster way.​

3. General Framework: 

  3.1.Video footage from CCTV Camera: 

  Most of the standard Banks store footage for 90 Days and after that, they archive using Tape Drive Library. Many of them also have redundant recording media parallelly running with the main storage system. After exceeding the threshold level of storage the data undergoes FIFO (First In First Out). But the model that is being proposed here does not require storage of any sought. The model is being trained to work in real time and reduces the lag in response to the actual happenings. 

  3.2.Pose Estimation:  

  This computer vision principle sets the basic foundation of the model. It maps the various key points of the skeleton to the human and looks for an abnormal pose.   

  3.3.Abnormal pose:  

  Plenty of data is fed and pre-trained. Along with this, there is a set of values fed into the system to denote the attack pose. If the pose aligns with the trained attack pose/shoot pose this module invokes the function to capture a snapshot of the pose and hence the function to send a call. The module uses Deep Learning principles to learn the pattern and the various. 

  3.4.Object detection:   

Once the pose is detected it looks for objects that are harmful and will aid in the heist. Objects such as a knife and guns are trained to be detected. Yolov5 is used to detect objects. A confidence score is assigned to the object which enables us to filter out the false alarms. After the object is detected with the trained pose the frame freezes. The frame is now sent to a human for second verification and the alert signal is called. 
 

  3.5.Abnormal behaviour: 

The abnormal behaviour is identified using emotional recognition. We use real-time emotion recognition from facial images. In the proposed method we use three steps of face detection using Haar cascade, and features extraction using the Active shape Model(ASM) for the classification of six emotions anger, sad, surprise, happy, neutral, and fear. 

  3.6. Alert System: 

The alert system is a function that uses a python API that makes a call to the concerned, registered number when the anomaly takes place. 

4.  Proposed Methodology: 

The majorly used technological security in our country is CCTV surveillance.​ The existing system requires personnel dedicated to monitoring abnormal activities that are taking place in the frame. There is a lack of a proper alert system from the place of attack to the police force. So, the arrival of police often gets delayed due to which the recovery rate is low. 

Hence the criminal accomplishes his heist, uncaptured. 

  4.1.Solution: 

Our project uses a combination of pose estimation and object detection to prevent crime.​This project tracks the activity of the suspected criminal. Depending on the pose of the criminal, the object that he/she holds, and the behavior, the alert will be sent to both  

surveillance rooms as well as to the nearest police station.  

The arrival of the police will be much faster than the existing system. 

​It can increase the security of the premises even more. 

  4.2.Working Principle: 

  This project uses three techniques to detect the crime-Pose Estimation​, Object Detection, and emotion recognition. 

    4.2.1.Pose estimation: 

    With the help of Computer Vision's Pose estimation technique, we identify the pose of criminal.​Pose estimation compares the posture of the person with the database and if it resembles a shooting posture, then object detection comes into play.​Object detection checks whether the suspected criminal is holding a weapon or not.​ If it detects a weapon, an alert is sent to the security department and the nearest police station. This happens if and only if both the above mentioned conditions are satisfied.

    MediaPipe provides a robust solution capable of predicting thirty-three 3D landmarks on a human body in real-time with high accuracy even on CPU. It utilizes a two-step machine learning pipeline, by using a detector it first localizes the person within the frame and then uses the pose landmarks detector to predict the landmarks within the region of interest. 

    4.2.2.Object detection: 

Object detection using Yolov5 can be used for crime detection by identifying and tracking individuals and objects in surveillance videos. Yolov5 is a popular machine learning algorithm for object detection, which uses a single convolution neural network to detect multiple objects in an image or video frame. 

4.2.4. Alert system using an automated voice call: 

The python API is being used in this system. It is a library that enables users to program a voice call under conditions that are pre-programmed. In our case, we have used a Twilio account. The account has a few parameters that are assigned to a user. It consists of an account ID, authenticator token, sender phone number, and receiver phone number. 

Once the function is called, a call from the sender number is sent to the receiver. A message can be tailor-made and an automated voice delivers it to the user. 

4.3.Merits over the Existing system: 

It intends to reduce the present crime rate.​ It seeks to improve public safety. It makes sure the policemen arrive at the right time to capture the criminals thereby increasing the recovery rate. It helps in detecting behavior's of people. It helps in preventing future crimes by analyzing the output given by the program. The arrival of police will be much faster than the existing system thereby leading to prevention.

The novelty or innovation statement: 

There is no existing software that provides this service. Since banks are the safe place for many citizens’ hard-earned money it is a very well-required and appreciated product that will be available for the banks to be a part of their security system.  
