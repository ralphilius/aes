# Advanced Encryption Standard
A symmetric key encryption based on a design principle known as a substitution–permutation network. Key size of 128, 192 or 256 bits.
## Quick Guide
#### Set Key encryption size (Default 256bit)
128bit Keys: `AES.size(128);` \
192bit Keys: `AES.size(192);` \
256bit Keys: `AES.size(256);` 
#### Encrypt Message
```
encrypted_msg = AES.enc("Your Message", "your-password");
```
#### Decrypt Message
```
decrypted_msg = AES.dec(" U2FsdGVkX19bpp2GepmpgIJiBT+0L/jytlR/ZRD5rdE=", "your-password");
```
## Requirements
None.

## Contact
Email: contact@chaepy.net \
Website: https://chaepy.net/