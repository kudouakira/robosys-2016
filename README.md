# robosys-2016

##ロボットシステム学：課題１
* ０〜５の数字をデバイスに書き込む  
  書き込まれた数字の回数分LEDを点滅させる

---------
$ git clone https://github.com/kudouakira/robosys-2016.git  
$ cd robosys-2016/  
$ make  
$ sudo insmod LED.ko  
---------

----------
  
$ echo 0 > /dev/myled0  
$ echo 1 > /dev/myled0  
$ echo 2 > /dev/myled0  
$ echo 3 > /dev/myled0  
$ echo 4 > /dev/myled0  
$ echo 5 > /dev/myled0  
  
----------
