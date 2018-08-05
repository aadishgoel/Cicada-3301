# Cicada-3301
In Attempt to solve Cicada 3301 Puzzle by myself 

## Start From Start.jpg
![](Start.jpg)

### Content Hidden in the image can be seen by opening image in any editor or in notepad.
> CLAVDIVS CAESAR says "lxxt>33m2mqkyv2gsq3q=w]O2ntk"

This is encrypted by CAESAR CIPHER   (Key 4 as Claudius was the 4th emperor).

So decrypt it by running ` clavdivs_caesar.py ` 
```python
for i in "lxxt>33m2mqkyv2gsq3q=w]O2ntk": print(chr(ord(i)-4),end="")
```
### You will get
> http://i.imgur.com/m9sYK.jpg

![](http://i.imgur.com/m9sYK.jpg)

This image is decoy. You have to use outguess on `Start.jpg`

``` outguess -r Start.jpg Start.txt ```
