# Binaries

Find core binaries into the respective folder.



## Flash scripts from Internet

* KianV Linux  

```sh
# be aware this will replace the core in flash
curl -sL https://tinyurl.com/4cbt7um7 | openFPGALoader  -b tangnano20k --file-type ext --external-flash -f
tio -m INLCRNL /dev/serial/by-id/usb-SIPEED_20K_s_FRIEND_2023030621-if01-port0 -b 2000000 
```

* Flappy Bird (outputs HDMI video, flap with user button, reset with the other user button)

```sh
curl -sL https://tinyurl.com/flappybird75 | openFPGALoader -b tangnano20k --file-type fs 
```



