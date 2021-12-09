### filePath
```
C:\ProgramData\Jenkins\.jenkins\secrets\master.key
C:\ProgramData\Jenkins\.jenkins\secrets\hudson.util.Secret
C:\ProgramData\Jenkins\.jenkins\credentials.xm
```


## usage:
```bash 
$ python3 decrypt.py
python3 decrypt.py <master.key> <hudson.util.Secret> <credentials.xml>

$ python3 decrypt.py master.key hudson.util.Secret credentials.xml
12345678
```



PoC to [decrypt jenkins credentials](http://xn--thibaud-dya.fr/jenkins_credentials.html).
Released under MIT License.

This repository is in maintenance mode. 
For pull requests, please use: https://github.com/bstapes/jenkins-decrypt.
