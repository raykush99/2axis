---
title: "2axis"
author: "Kush Ray"
description: "A robot that can move in the x and y axis. It is meant to be able to move an air hockey puck and play with you, but has the option to add any other attachment to it (like a pen for drawing or a laser)"
created_at: "2025-07-01"
---

**Total Time: 5.5 hours**     

**Day 1: July 1**    
Today I started by researching how to make a 2 axis robot. I looked into how 3D printers work, and realized a linear steel rod with a linear ball bearing works best and is the cheapest. With this, I started to make an onshape model. One problem I had was how to use special elements, like aluminum t-slots or ball bearings in my CAD. After doing some research, I learned I could link these models into my CAD, making it much easier to use special parts in my 3D model. I imported the bearing and aluminum tubes and then measured my air hockey table to find I need a frame 40 in by 36 in. However, I could not find an aluminum t-slot that long, so I traced the face sketch and extruded it to extend it. I edited the imported part to fit my requirments. I also made 3D printable brackets to attach to the aluminum tubes and hold the bearings. I was able to make the basic movement frame, and added mates and limits to simulate how it would move. I also added the grove to the main slider in order to be able to add multiple attachments to the frame. One problem I faced was that the horizontal length was slightly less than 36 in (35.66in), and it would be easier if the horizontal and vertical bars were the same. I spend some time changing dimensions to make room for the extra 0.44 inches. I also used a variable for the bolt, rod, and bearing diameter in case I can't find the exact dimensions I modelled. Overall, I was able to make the base to see how the robot would move (without any motors), and added variables to make easy changes later.        
Note: I could not find the original creator of the aluminum tube and bearing, but the STEP files are in the onshape project (unsure if I used someone else's CAD or a linked CAD, since could not find name of owner or original document) (Not trying to steal credit or work, just no citations given by onshape about the model I imported)
![image](https://github.com/user-attachments/assets/cd1dff40-5f06-4457-a271-380629e3de3e)      
![image](https://github.com/user-attachments/assets/575b9da9-ed1e-454e-a513-5bcbf8b9892e)       
![image](https://github.com/user-attachments/assets/95600a5a-89e8-4fdb-8a07-aa3cbe4451c2)                        
![image](https://github.com/user-attachments/assets/ac058b62-ffa7-4b15-a1ff-88520e23dd78)      
![image](https://github.com/user-attachments/assets/5a95b7ff-ab79-4b6e-a029-2f856e5fa20a)            

**Time spent: 3.5  hours**      

**Day 2: June 2**    
Today was a parts research day. I spend the most of this session finding the exact parts I needfor the project so I can finish the CAD based on those dimensions. One problem was that the linear rods were very expensive, so I decided to use thinner rods (around 10 mm instead of 16mm). I was also able to find which stepper motor I am using and the driver, so now I will  be able to make a case for the motor. I decided to use an arduino mega for the microcontroller due to it being cheaper, easier to use, while still having a large number of inputs and outputs. I also did some research and found that 1/4-20 nuts and bolts are best for t-slots. I decided to use 1/2 inch bolts and added it to the BOM. I also made the initial BOM and added all the parts and prices. Another thing I did today was make the attachments that go on the slider to see how the groove would work. I made two attachments (one from an air hockey stricker, the other for a pen), and added mates to see the sliding motion. Overall, today, I was able to find the parts I needed to continue the CAD and made a simple part to test the groove mechanism on the slider.     
![image](https://github.com/user-attachments/assets/110092b4-3f12-4106-98e8-83ebc000aea9)       
![image](https://github.com/user-attachments/assets/c1ad9f77-a99e-4609-8b81-51f1dcecdf55)         
![image](https://github.com/user-attachments/assets/d0e75771-0d7c-48df-9711-3ba0d4b923d9)     
![image](https://github.com/user-attachments/assets/39d99d1b-5c05-4e86-88be-b11ab20509e4)        

**Time spent: 2 hours**       





