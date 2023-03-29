# RPi-Facial-ID-Door
The primary goal of this project is create an active facial recognition system to detect trained faces and accordingly unlock the (dorm) door. The process of this project would to be to use a Raspberry Pi and camera, build a Python script within the Pi to capture and save images of a person, train it into a pickles file, and run a facial recognition script to detect for desired faces and accordingly unlock the door.
### Unlocking the Door
In order to unlock the door a system of mechanics needed to be used and it was decided to utilize a Servo motor, string, and a 3D-designed door lock mold to rotate the lock from a locked position into an unlocked position. Upon detection of the correct face, the script will run so that the Servo rotates, pulling the string tied to the mold in order to rotate the lock.
### Running the Program in Continuation and On-Command
For this project to be applicable in every-day use, it is important to have the program be running throughout the day and be capable of running multiple times as a loop. In order to do this, the Pi needed to be taught to run the script upon booting and the script itself would need to be modified to loop.
### Designing the Door
For this project to work with the particular door in question, circuit needed to be built, designs for the wiring and for the camera placement were needed, and proper placement of motors and strings was needed. 
