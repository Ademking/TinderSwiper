# TinderSwiper

The coolest thing i can do with 1 line of code 😂 

Demo : [https://youtu.be/aevB7K0CAM4](https://youtu.be/aevB7K0CAM4)

<div  align="center">
  <a href="https://youtu.be/aevB7K0CAM4"><img src="https://img.youtube.com/vi/aevB7K0CAM4/0.jpg"/></a>
  </div>

📌 What it does ?

i'm trying to emulate swipe (Like) in Tinder App using ADB .. 
This command takes 5 parameters :
* [X1 start point] 

* [Y1 start point] 

* [X2 end point] 

* [Y2 end point] 

* [Duration]

📌 Code: 

```
for /L %n in (1,1,1000) do (adb -d shell input swipe 500 630 714 722 100)
```
