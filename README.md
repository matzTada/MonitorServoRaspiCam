Controlling Camera angle by servo motors
(do not include Raspberry Pi camera configuration)
View: https://www.youtube.com/watch?v=zNGVQXqtgJ4
Motion: https://www.youtube.com/watch?v=AG3V2XWtpm4

Raspberry Piからサーボをコントロールするプログラムたちです
Raspberry Pi Cameraの設定方法，遠隔でCameraからの画像を見る方法についてはほかの方のサイトを参考にしてください．
遠隔で見れるかと思って期待した方にはごめんなさい．．．
下に私が参考にしたサイトとコマンドを示しておきます．

-- prepartion of raspberry pi camera --
I refered this site. 
http://blog.studiok-i.net/raspberry-pi/891.html
http://www.pyimagesearch.com/

-- Remote View of Raspberry Pi Camera --
1. start VNC server on Raspberry Pi (in the videos, tightvncserver is used)
2. login VNC server from your computer (for windows, real vncviewer is used)
3. type "xhost +localhost" to run (Important)
4. cd ~/facedetect/
5. ./facedetect --scale=5