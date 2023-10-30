## Challenge

```
There's this figure in front of me, but I can't even figure out what it is! What is that thing??
```
And an attachment of a png file.

## Solution

When I tried to open the png image, I got a warning saying it is a corrupted image. So, I put the file into CyberChef and analyzed. There was a hidden zip file. I extracted it and got an executable file `trueform.exe`. 

After analyzing it in CyberChef, I realized that it is not actually an exe file but a rich text format file. I opened it as `trueform.rtf` and flag was written in white color on white background.

### NICC{Y0U_F0UND_MY_TRU3_F0RM}