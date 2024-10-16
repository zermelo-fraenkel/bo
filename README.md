# HTML

## Character Reference

| Literal character | Character reference equivalent |
| ----------------- | ------------------------------ |
| <                 | \&lt;                          |
| >                 | \&gt;                          |
| "                 | \&quot;                        |
| '                 | \&apos;                        |
| &                 | \&amp;                         |

## Comments

Comments are wrapped within `<!--` and `-->`.


# Get page from Web Server

### HTTP
```
telnet zermelo-fraenkel.github.io 80

GET /bo/index.html HTTP/1.1
Host: zermelo-fraenkel.github.io
```

### HTTPS
```
openssl s_client -connect zermelo-fraenkel.github.io:443

GET /bo/index.html HTTP/1.1
Host: zermelo-fraenkel.github.io
```
