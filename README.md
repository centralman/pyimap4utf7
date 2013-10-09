pyimap4utf7
====

Tool for encoding/decoding imap4 style utf7 string.

See [RFC3501](http://tools.ietf.org/html/rfc3501) for details of the modification.


Install
---

`pip install pyimap4utf7`

Usage
---

```
import pyimap4utf7 as iutf7

# encode
e_s = iutf7.encode(u'测试')

# decode
d_s = iutf7.decode(e_s)
```
