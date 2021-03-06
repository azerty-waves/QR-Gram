# QR-Gram
> Converter: from string to QR code to nonograms.

I like nonograms and I like QR codes. Both open the door to a new word when scanned or completed. That's why I created a quick and dirty python code that transfers a string into a QR-code which is then encoded into a nonogram.

To access the message (or website), the player must first fill in the nonogram, then scan it. Obviously, the longer the message, the more complicated the nonogram.

Have fun :)

## Example

So for QR-code:

![qrcode](README.assets/qrcode.png)

You will have the nonogram:

```
                      1 1                                
                    1 3 3             1         1 1      
                    3 1 1         3 3 1 4       3 3 1    
                  1 1 1 2 1 7   2 1 1 1 3   7   1 1 3 1  
                  1 2 2 1 1 1   1 2 1 1 1   1   2 1 1 1 7
                7 2 1 1 1 2 1 1 1 3 1 1 1 2 4 1 2 3 1 1 2
                3 1 3 3 3 1 1 1 3 1 2 2 3 2 1 1 1 3 3 1 1
                7 1 1 1 1 1 7 1 2 1 2 2 1 2 2 4 1 1 5 2 2
        7 2 1 7
      1 1 4 1 1
1 3 1 3 1 1 3 1
1 3 1 1 1 1 3 1
1 3 1 1 1 1 3 1
        1 1 1 1
      7 1 1 1 7
            1 1
      2 2 2 1 2
      2 1 1 1 1
  3 4 1 1 1 1 1
    1 3 1 4 2 1
      1 1 4 1 3
        3 1 2 1
      7 1 2 4 1
      1 1 1 1 3
1 3 1 1 2 2 2 1
    1 3 1 1 2 3
    1 3 1 2 3 3
    1 1 2 2 1 3
          7 2 2
```

## Usage

```
python qr-gram.py your-message-to-encode
```

## Install

```
$ python pip install itertools pyqrcode argparse
```

## Sources

[Reddit - r/dailyprogrammer]( https://www.reddit.com/r/dailyprogrammer/comments/42lhem/20160125_challenge_251_easy_create_nonogram/)

[Reddit - TheBlackCat13]( https://www.reddit.com/user/TheBlackCat13/)

[PyPi - PyQRCode](https://pypi.org/project/PyQRCode/)
