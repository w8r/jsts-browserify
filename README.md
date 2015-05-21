# JSTS + npm + browserify bug

**Resolved with javascript.util@0.12.12**

jsts >0.14.0

Reproduce steps:

```shell
git clone https://github.com/w8r/jsts-browserify.git
cd jsts-browserify
npm install
npm start
It'll open the page with the browserified bundle and if you open console you'll see that the error right away
```
