## Challenge

```
I just spun up my first website with a login page and everything! My friend tells me my page isn't secure and I'm not sure why.
```
And an attached pcap file.

## Solution

I opened the pcap file with Wireshark. Sorted with respect to protocol to see different protocols easier. 4 HTTP protocols took my attention as HTTP is an insecure protocol. After following the TCP protocol, the flag was in the login request, username part. (full flag can be got after URL decoding)

### NICC{h77p_15_1n53cur3}
