jsqrcode-production
===================

Ported to JavaScript by Lazar Laszlo 2011 

lazarsoft@gmail.com, www.lazarsoft.info


## Copyright 2007 ZXing authors

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at
      http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

## Usage

Include script like this
``` html
<script src="https://raw.githubusercontent.com/aray894/jsqrcode-production/master/jsqrcode.min.js"></script>
```

Set qrcode.callback to function "func(data)", where data will get the decoded information.

Decode image with: qrcode.decode(url or DataURL).
Decode from canvas with "qr-canvas" ID: qrcode.decode()
