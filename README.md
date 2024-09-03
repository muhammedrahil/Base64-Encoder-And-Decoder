# Base64-Encoder-And-Decoder

base64 using Django encrypt and decrypt

A built-in module in Python, the base64 library offers functions for encoding and decoding binary data to and from base64 strings, effectively converting any binary data to plain text. A common encoding method called Base64 converts binary data into a string of printable ASCII characters

```
import base64
```
## encode primary key 

```
pk=kwargs.get('pk')
enc = base64.b64encode(str(pk).encode('ascii'))
enc=enc.decode()
                
```
- eg: MjA=

## decode primary key 

```
pk=kwargs.get('pk')
denc = base64.b64decode(pk)
pk = denc.decode('ascii')
                
```
- eg: 15
