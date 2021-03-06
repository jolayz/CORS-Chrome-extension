Welcome to the CORS-Chrome-extension browser extension
=======

[![Badge](https://img.shields.io/badge/link-996.icu-%23FF4D5B.svg)](https://996.icu/#/en_US)
[![LICENSE](https://img.shields.io/badge/license-Anti%20996-blue.svg)](https://github.com/996icu/996.ICU/blob/master/LICENSE)

[中文版](./README_CN.md)

**CORS Helper** allows you to customize the rules to the HTTP response header. You can add the `Access-Control-Allow-Origin:http://localhost:3000` rule to the response header to allow CORS to be developed locally. Avoid cross-domain request interception by the browser.

Instructions
---
After installing the plugin, click the icon in the upper right corner to enable "cross-source resource sharing".

Custom configuration
---
After installing the plugin, click the icon in the upper right corner and click "Customize" to enter the configuration page.

  - The "HTTP Response Header" page allows you to add custom `Access-Control-*` header information to the HTTP response header
  - "Url Mode" page allows you to customize the website for applying rules

Compatible browser
---
Firefox v48+
Chrome v22+

Local development
---
download and run `$ npm install`
Open browser development mode, load the extension directory

License
---
[Anti-996 License] (LICENSE)