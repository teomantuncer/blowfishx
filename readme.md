# blowfishx

### encrypt
```javascript
blowfish.encrypt('subj to encrypt', 'key', { outputType: 1, cipherMode: 0 });
```
### decrypt
```javascript
blowfish.decrypt('subj to decrypt', 'key', { outputType: 1, cipherMode: 0 });
```
### options
| name          | default       |
|:------------- |:------------- |
| outputType    | Base64        |
| cipherMode    | ECB           |

#### cipherModes
| name   | value    |
|:------ |:-------- |
| ECB    | 0        |
| CBC    | 1        |
| PCBC   | 2        |
| CFB    | 3        |
| OFB    | 4        |
| CTR    | 5        |
#### outputTypes
| name   | value    |
|:------ |:-------- |
| Base64 | 0        |
| Hex    | 1        |
| String | 2        |
| Raw    | 3        |
