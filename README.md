# AESLib

This is a javascript implement of AES Encryption/Decrytion algorithm using _PKCS7_ padding . It supports 128-bit key only. A simple web interface can be found [here](http://zhengqiyang.com/aesdemo/). 

Here is a sample javascript code: 

```javascript
var message = "This a mesage";
var key = "aesencrytionkeys";
var aes = new AESLib();
var cipher = aes.encrypt(message, key);
console.log("Cipher text = " + cipher);
var decrypted_msg = aes.decrypt(cipher, key);
console.log("Decrypted message = " +decrypted_msg);
```
Javascript code in the html is another working example usage of the library. It's also recommanded to convert the cipher text to base64 before pringting out for readability. 

Zhengqi Yang<zyang36@illinois.edu>
