## Challenge
```
I recieved this very weird email that only contained a file called "openme", it looks like an executable.

Can you see if there is anything weird in this file?
```

## Solution

It is an executable file and the name gives a hint, so I did `strings` command on the file. And the flag is clearly visible:

### 00003008: NICC{leaky_data_huh}