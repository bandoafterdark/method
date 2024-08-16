# NOT PATCHED


# tiktok phone method
 forked from 0xf15 and made better

## How-to-use
Tiktok Font IOS Method.

Download VPN:
OpenSpider VPN

Connect to VPN:
Use this Location Russia u need to use russia or use japan.

Create Tiktok Acc
you need to be connected to russia or japan while creating the acc.

Get Your SessionID
[Get Sessionid](https://vm.tiktok.com/ZMrqyoJJf)

## Important
- To run the script download python (https://www.python.org/downloads/) and add to path
- on your computer open cmd and type `pip install requests`

## Faq
- Q1: Whats all the confusing stuff in the code?
- A1: X-Gorgon and X-khronos is a an algorithm tiktok uses so the request to the API is succesfull
- Q2: How are these header generated?
- A2: X-Khronos is the current time in unix format, X-Gorgon is The **X-Gorgon** header is generated through a series of complex cryptographic operations designed to secure TikTok API requests. It begins with the calculation of MD5 hashes for the request URL parameters, any provided request body (referred to as the "stub"), and cookies. These hashes are then used to construct an initial array, which is supplemented with constant values and the current Unix timestamp. This array undergoes a series of bitwise transformations within a custom class called `XG`. Specifically, each element in the array is subjected to bit reversal, bitwise XOR operations, and manipulations involving both fixed values and dynamically calculated indices. The process includes reversing and rotating bits, utilizing operations like the `reverse` and `RBIT` functions to further obfuscate the data. The transformation iterates over the array, applying intricate bitwise logic to ensure each output is distinct and secure. The result is a hexadecimal string prefixed with '8402', which serves as the final **X-Gorgon** signature. This signature acts as a cryptographic proof of authenticity for the request, allowing TikTok's servers to verify that it originated from a legitimate client and has not been tampered with, thereby adding a robust layer of security to API interactions.



