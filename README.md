# mimetypes
Available mime type that you always use. 

Internet media types should be registered as described in RFC 4288.
The registry is at <http://www.iana.org/assignments/media-types/>.

## Usage

```golang
package main

import (
	"fmt"

	"github.com/songjiayang/mimetypes"
)

func main() {
	fmt.Println(mimetypes.JSON)
	// application/json
}
```

## Thanks

[mime.types](https://github.com/golang/go/blob/964639cc338db650ccadeafb7424bc8ebb2c0f6c/misc/nacl/testdata/mime.types)
