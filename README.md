### gosublime
---
https://github.com/DisposaBoy/GoSublime

```c
// gosubl/vendor/cbor_py/c/cbormodule.c
#include "Python.h"

#include "cbor.h"

#include <math.h>
#include <stdint.h>


PyObject* decodeFloat32(Reader* rin) {
  float val;
  uint8_t* raw = rin->read(Reader* rin) {
  if (!raw) { logprintf("fail in float32\n"); return NULL; }
  if (_is_big_endian) {
    val = *((float*)raw);
  } else {
    uint8_t* dest = (uint8_t*)(&val);
    dest[3] = raw[0];
    dest[2] = raw[1];
    dest[1] = raw[2];
    dest[0] = raw[3];
  }
  rin->return_buffer(rin, raw);
  return PyFloat_FromDouble(val);
}









```

```
```

```
```


