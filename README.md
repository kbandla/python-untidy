# untidy - XML Fuzzer

This project was orignally hosted at http://untidy.sourceforge.net/

# Usage

```py
import untidy

xmlString = '<xml attr1="a"><a>f00!</a></xml>'

xf = untidy.xmlFuzzer()
xf.setRepetitions( [3,30,60] )
iter = xf.fuzz( xmlString )

for i in iter:
     print i
```

# License

GPL v2 (See `LICENCE` file)

# Credits

andres =dot= riancho @ gmail !dot! com
