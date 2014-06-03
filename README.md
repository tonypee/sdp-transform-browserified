# SDP Transform (https://github.com/clux/sdp-transform) hacked for tAMD

Browserified and removed the amd support - hack to support tAMD until a better option is found

1. browserify node_modules/sdp-transform/index.js --standalone sdp-transform > bin/sdp-transform.js

2. delete "else if ("function" == typeof define && define.amd) define(e);"

## License
MIT-Licensed. See LICENSE file for details.
