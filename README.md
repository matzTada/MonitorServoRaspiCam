Controlling Camera angle by servo motors
(do not include Raspberry Pi camera configuration)
View: https://www.youtube.com/watch?v=zNGVQXqtgJ4
Motion: https://www.youtube.com/watch?v=AG3V2XWtpm4

Raspberry Pi����T�[�{���R���g���[������v���O���������ł�
Raspberry Pi Camera�̐ݒ���@�C���u��Camera����̉摜��������@�ɂ��Ă͂ق��̕��̃T�C�g���Q�l�ɂ��Ă��������D
���u�Ō���邩�Ǝv���Ċ��҂������ɂ͂��߂�Ȃ����D�D�D
���Ɏ����Q�l�ɂ����T�C�g�ƃR�}���h�������Ă����܂��D

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