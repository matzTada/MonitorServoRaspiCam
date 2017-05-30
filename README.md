# MonitorServoRaspiCam
Controlling Camera angle by servo motors
(do not include Raspberry Pi camera configuration)

<a href="http://www.youtube.com/watch?feature=player_embedded&v=3JpP7gTOWbY
" target="_blank"><img src="http://img.youtube.com/vi/3JpP7gTOWbY/0.jpg" 
alt="movie on youtube" width=40% border="10" /></a>
<a href="http://www.youtube.com/watch?feature=player_embedded&v=AG3V2XWtpm4
" target="_blank"><img src="http://img.youtube.com/vi/AG3V2XWtpm4/0.jpg" 
alt="movie on youtube" width=40% border="10" /></a>  
[movie "View" on youtube](https://www.youtube.com/watch?v=3JpP7gTOWbY)  
[movie "Motion" on youtube](https://www.youtube.com/watch?v=AG3V2XWtpm4)

Raspberry Piからサーボをコントロールするプログラムたちです  
Raspberry Pi Cameraの設定方法，遠隔でCameraからの画像を見る方法についてはほかの方のサイトを参考にしてください．  
遠隔で見れるかと思って期待した方にはごめんなさい．．．  
下に私が参考にしたサイトとコマンドを示しておきます．  

## Preparation of raspberry pi camera
I refered following sites.

* <http://blog.studiok-i.net/raspberry-pi/891.html> (Japanese)   
* <http://www.pyimagesearch.com/> (English. I recommend strongly.)  

## Remote View of Raspberry Pi Camera

1. start VNC server on Raspberry Pi (in the videos, tightvncserver is used)
2. login VNC server from your computer (in the videos (for windows), real vncviewer is used)
3. type `xhost +localhost` to show view from camera on VNC display __(Important)__
4. `./facedetect/facedetect --scale=5` (start view from camera. please follow referential site.)

## Images

<a><img src="https://github.com/matzTada/MonitorServoRaspiCam/blob/master/image/pic01.jpg" 
alt="pic01" width=20%></a>
<a><img src="https://github.com/matzTada/MonitorServoRaspiCam/blob/master/image/pic02.jpg" 
alt="pic02" width=20%></a>
<a><img src="https://github.com/matzTada/MonitorServoRaspiCam/blob/master/image/pic03.jpg" 
alt="pic03" width=20%></a>
