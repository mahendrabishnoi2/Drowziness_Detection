# DDD_Hackathon_5.0
##NOTE: Open the Project_files_link file to get the link to zip file uploaded on google drive

  
PROJECT IDEA:  
  Our project is to detect the drowsiness of a driver by detecting the eyes of the driver using a small camera attached on the steering of the wheel.

SCALABILITY:
 This project will reduce the accidental hazards caused by the drowsiness of the driver. Whenever the driver feels dizziness and his eyes will get close our program will detect it and will ring an alarm to wake the driver up.  
 
  Additionaly we would like to add gps and emergency contacts to the system so that whenever the situation like this occurs the mentioned contacts can receive a alert message along with the location.

Although the technique is developed way earlier but it is still not used in the vehicles. By using respi along with the camera we can even attach this device to the onroad vehicles. This will be cheap but a life saving instrument.

FUTURE ASPECTS:
  There could be many improvements in the program like increasing the accuracy, including the heart monitoring system which would alert the emergency medical teams along with the location of the driver if the driver gets heart attack. This will be a very useful feature for the safety of the driver.
 
 By using products like this we can turn our vehicles into smart vehicles which will take care of its owner.
 
 
IMPLEMENTATION:
  We have implemented the program using python libraries like dlib, openCV etc. Our detailed project involves the use of hardwares like respberry pi and a camera. We have used a pretrained model to detect the facial landmarks and extracting the eyes from that.
  Then we decided some of the threshold for the eyes aspect ratio and video frame to detect the eyes of the driver. 
  Now if the aspect ratio of the eyes will get lower than the threshold value, the program will ring the alarm and driver will wake up.
