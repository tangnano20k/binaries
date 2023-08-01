# Binaries

Find bitstreams of cores into the respective folder.



## Flash scripts

* KianV Linux  (be aware this will replace the core in flash)

```
curl -sL https://tinyurl.com/4cbt7um7 | openFPGALoader  --board=tangnano20k --file-type ext --external-flash -f
```

* Flappy Bird

```
curl -sL  | openFPGALoader  -b tangnano20k 
```



