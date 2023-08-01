# Binaries

Find core binaries into the respective folder.



## Flash scripts

* KianV Linux  (be aware this will replace the core in flash)

```
curl -sL https://tinyurl.com/4cbt7um7 | openFPGALoader  -b tangnano20k --file-type ext --external-flash -f
```

* Flappy Bird (outputs HDMI, flap with user button, reset with the other user button)

```
curl -sL https://tinyurl.com/flappybird75 | openFPGALoader -b tangnano20k --file-type fs 
```



