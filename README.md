# base64-using-django
base64 using Django encrypt and decrypt


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
