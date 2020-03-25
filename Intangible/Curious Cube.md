---
Project #2: Cranky Cube
---

Make a cube shaped object that people can interact with through intangible interaction. Your cube has either a behavior (e.g., it senses specific gestures and reacts to them with sound, it lights up when a user blows their warm breath onto it…) or personality (e.g., shy, impatient, cheerful, rude, polite, reserved, grumpy…). Your cube’s functionality or personality will not be communicated through the physical form of the object, instead, users will find them out through the process of interacting with them. Your cube can be made of any material and can be any size. You will use a APDS9960 (Proximity, Light, RGB, and Gesture Sensor) that will be provided for this assignment or any other sensors of your choice.


### Ideation:
- Humanizing the cube
- Plays snoring sounds until you get within an x distance of it, then it wakes up by either an LED light turning on or some
other indication
- Maybe starts swearing once it's been woken up 
- Needs two audio sensors (isd1820) and a gesture sensor (APDS9960)
https://create.arduino.cc/projecthub/gadgetprogrammers/diy-auto-voice-record-and-playback-7a47d7

<img src = "/img/cranky cube.jpg" width = "600" height = "600" >

### Fabrification:
[White opqaue acrylic](https://www.canalplastic.com/collections/acrylic-sheets/products/7508-white-opaque-acrylic-sheet?variant=32920758798)

#### First draft: 
- Video of all working components can be found [here](https://youtu.be/Nskk3B-UGM0)

<img src = "/img/rough.jpeg" width ="550" height ="550" >


### Final:



#### Takeaways/Challenges:
- We definitely ran into a bunch of unexpected obstacles that we weren't able to get help or feedback on due to the COVID- 19 situation escalating 
- One of them being, as you can see in the first draft video, all the individual parts worked initially. But as soon as we 
hooked it up to an external power supply and put it in the acrylic box, the arduino would shut off
- We learned it was due to our power supply not being able to power everything so we have to get rid of the Ardafruit neopixel, so there would no longer be another output indication from the user when it woke up
- The speaker volume turned out to be pretty low and we decided to drop adding the second swearing dialogue that plays after it's worken up
- Overall, it's one thing to find all the different working parts online like the code, materials, and other resourcs but as soon as it's all arrived, a lot of time is invested in getting them all to work and how and fabrification
- I would usually leave fabrification and the physically building part to the last while I focused on the tech more, but I realized both are just as important to the process, especially for creating a finished and polished project 
