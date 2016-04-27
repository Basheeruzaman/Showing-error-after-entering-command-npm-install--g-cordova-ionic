0 info it worked if it ends with ok
1 verbose cli [ 'C:\\Program Files\\nodejs\\node.exe',
1 verbose cli   'C:\\Program Files\\nodejs\\node_modules\\npm\\bin\\npm-cli.js',
1 verbose cli   'install',
1 verbose cli   '-g',
1 verbose cli   'cordova',
1 verbose cli   'ionic' ]
2 info using npm@2.15.1
3 info using node@v4.4.3
4 verbose install initial load of C:\Users\BASHEER\AppData\Roaming\npm\package.json
5 verbose readDependencies loading dependencies from C:\Users\BASHEER\AppData\Roaming\npm\package.json
6 silly cache add args [ 'cordova', null ]
7 verbose cache add spec cordova
8 silly cache add args [ 'ionic', null ]
9 verbose cache add spec ionic
10 silly cache add parsed spec Result {
10 silly cache add   raw: 'cordova',
10 silly cache add   scope: null,
10 silly cache add   name: 'cordova',
10 silly cache add   rawSpec: '',
10 silly cache add   spec: 'latest',
10 silly cache add   type: 'tag' }
11 silly addNamed cordova@latest
12 verbose addNamed "latest" is being treated as a dist-tag for cordova
13 info addNameTag [ 'cordova', 'latest' ]
14 silly mapToRegistry name cordova
15 silly mapToRegistry using default registry
16 silly mapToRegistry registry https://registry.npmjs.org/
17 silly mapToRegistry data Result {
17 silly mapToRegistry   raw: 'cordova',
17 silly mapToRegistry   scope: null,
17 silly mapToRegistry   name: 'cordova',
17 silly mapToRegistry   rawSpec: '',
17 silly mapToRegistry   spec: 'latest',
17 silly mapToRegistry   type: 'tag' }
18 silly mapToRegistry uri https://registry.npmjs.org/cordova
19 verbose addNameTag registry:https://registry.npmjs.org/cordova not in flight; fetching
20 silly cache add parsed spec Result {
20 silly cache add   raw: 'ionic',
20 silly cache add   scope: null,
20 silly cache add   name: 'ionic',
20 silly cache add   rawSpec: '',
20 silly cache add   spec: 'latest',
20 silly cache add   type: 'tag' }
21 silly addNamed ionic@latest
22 verbose addNamed "latest" is being treated as a dist-tag for ionic
23 info addNameTag [ 'ionic', 'latest' ]
24 silly mapToRegistry name ionic
25 silly mapToRegistry using default registry
26 silly mapToRegistry registry https://registry.npmjs.org/
27 silly mapToRegistry data Result {
27 silly mapToRegistry   raw: 'ionic',
27 silly mapToRegistry   scope: null,
27 silly mapToRegistry   name: 'ionic',
27 silly mapToRegistry   rawSpec: '',
27 silly mapToRegistry   spec: 'latest',
27 silly mapToRegistry   type: 'tag' }
28 silly mapToRegistry uri https://registry.npmjs.org/ionic
29 verbose addNameTag registry:https://registry.npmjs.org/ionic not in flight; fetching
30 verbose request uri https://registry.npmjs.org/ionic
31 verbose request no auth needed
32 info attempt registry request try #1 at 1:28:48 PM
33 verbose request id 1e236c0f3d95392c
34 verbose etag "9U7HNWGHT4VIUIL8TGWNTG646"
35 http request GET https://registry.npmjs.org/ionic
36 verbose request uri https://registry.npmjs.org/cordova
37 verbose request no auth needed
38 info attempt registry request try #1 at 1:28:49 PM
39 verbose etag "1X2EGML6C0FHDLY0YYWAMG66"
40 http request GET https://registry.npmjs.org/cordova
41 http 304 https://registry.npmjs.org/ionic
42 verbose headers { date: 'Wed, 27 Apr 2016 07:58:51 GMT',
42 verbose headers   via: '1.1 varnish',
42 verbose headers   'cache-control': 'max-age=300',
42 verbose headers   etag: '"9U7HNWGHT4VIUIL8TGWNTG646"',
42 verbose headers   age: '289',
42 verbose headers   connection: 'keep-alive',
42 verbose headers   'x-served-by': 'cache-sin6925-SIN',
42 verbose headers   'x-cache': 'HIT',
42 verbose headers   'x-cache-hits': '4',
42 verbose headers   'x-timer': 'S1461743931.660424,VS0,VE0',
42 verbose headers   vary: 'Accept-Encoding' }
43 silly get cb [ 304,
43 silly get   { date: 'Wed, 27 Apr 2016 07:58:51 GMT',
43 silly get     via: '1.1 varnish',
43 silly get     'cache-control': 'max-age=300',
43 silly get     etag: '"9U7HNWGHT4VIUIL8TGWNTG646"',
43 silly get     age: '289',
43 silly get     connection: 'keep-alive',
43 silly get     'x-served-by': 'cache-sin6925-SIN',
43 silly get     'x-cache': 'HIT',
43 silly get     'x-cache-hits': '4',
43 silly get     'x-timer': 'S1461743931.660424,VS0,VE0',
43 silly get     vary: 'Accept-Encoding' } ]
44 verbose etag https://registry.npmjs.org/ionic from cache
45 verbose get saving ionic to C:\Users\BASHEER\AppData\Roaming\npm-cache\registry.npmjs.org\ionic\.cache.json
46 verbose correctMkdir C:\Users\BASHEER\AppData\Roaming\npm-cache correctMkdir not in flight; initializing
47 silly addNameTag next cb for ionic with tag latest
48 silly addNamed ionic@1.7.14
49 verbose addNamed "1.7.14" is a plain semver version for ionic
50 silly mapToRegistry name ionic
51 silly mapToRegistry using default registry
52 silly mapToRegistry registry https://registry.npmjs.org/
53 silly mapToRegistry data Result {
53 silly mapToRegistry   raw: 'ionic',
53 silly mapToRegistry   scope: null,
53 silly mapToRegistry   name: 'ionic',
53 silly mapToRegistry   rawSpec: '',
53 silly mapToRegistry   spec: 'latest',
53 silly mapToRegistry   type: 'tag' }
54 silly mapToRegistry uri https://registry.npmjs.org/ionic
55 verbose addRemoteTarball https://registry.npmjs.org/ionic/-/ionic-1.7.14.tgz not in flight; adding
56 verbose addRemoteTarball [ 'https://registry.npmjs.org/ionic/-/ionic-1.7.14.tgz',
56 verbose addRemoteTarball   'af493d5df4688d917d778b0934d1739b9be6efe6' ]
57 http 200 https://registry.npmjs.org/cordova
58 verbose headers { server: 'CouchDB/1.5.0 (Erlang OTP/R16B03)',
58 verbose headers   etag: '"7WGJZTNR4J3IBLMIIMSZCL3KI"',
58 verbose headers   'content-type': 'application/json',
58 verbose headers   'content-encoding': 'gzip',
58 verbose headers   'cache-control': 'max-age=300',
58 verbose headers   'content-length': '28217',
58 verbose headers   'accept-ranges': 'bytes',
58 verbose headers   date: 'Wed, 27 Apr 2016 07:58:51 GMT',
58 verbose headers   via: '1.1 varnish',
58 verbose headers   age: '60',
58 verbose headers   connection: 'keep-alive',
58 verbose headers   'x-served-by': 'cache-sin6925-SIN',
58 verbose headers   'x-cache': 'HIT',
58 verbose headers   'x-cache-hits': '1',
58 verbose headers   'x-timer': 'S1461743931.665820,VS0,VE0',
58 verbose headers   vary: 'Accept-Encoding' }
59 silly get cb [ 200,
59 silly get   { server: 'CouchDB/1.5.0 (Erlang OTP/R16B03)',
59 silly get     etag: '"7WGJZTNR4J3IBLMIIMSZCL3KI"',
59 silly get     'content-type': 'application/json',
59 silly get     'content-encoding': 'gzip',
59 silly get     'cache-control': 'max-age=300',
59 silly get     'content-length': '28217',
59 silly get     'accept-ranges': 'bytes',
59 silly get     date: 'Wed, 27 Apr 2016 07:58:51 GMT',
59 silly get     via: '1.1 varnish',
59 silly get     age: '60',
59 silly get     connection: 'keep-alive',
59 silly get     'x-served-by': 'cache-sin6925-SIN',
59 silly get     'x-cache': 'HIT',
59 silly get     'x-cache-hits': '1',
59 silly get     'x-timer': 'S1461743931.665820,VS0,VE0',
59 silly get     vary: 'Accept-Encoding' } ]
60 verbose get saving cordova to C:\Users\BASHEER\AppData\Roaming\npm-cache\registry.npmjs.org\cordova\.cache.json
61 verbose correctMkdir C:\Users\BASHEER\AppData\Roaming\npm-cache correctMkdir not in flight; initializing
62 info retry fetch attempt 1 at 1:28:49 PM
63 info attempt registry request try #1 at 1:28:49 PM
64 http fetch GET https://registry.npmjs.org/ionic/-/ionic-1.7.14.tgz
65 http fetch 200 https://registry.npmjs.org/ionic/-/ionic-1.7.14.tgz
66 silly addNameTag next cb for cordova with tag latest
67 silly addNamed cordova@6.1.1
68 verbose addNamed "6.1.1" is a plain semver version for cordova
69 silly cache afterAdd cordova@6.1.1
70 verbose afterAdd C:\Users\BASHEER\AppData\Roaming\npm-cache\cordova\6.1.1\package\package.json not in flight; writing
71 verbose correctMkdir C:\Users\BASHEER\AppData\Roaming\npm-cache correctMkdir not in flight; initializing
72 verbose afterAdd C:\Users\BASHEER\AppData\Roaming\npm-cache\cordova\6.1.1\package\package.json written
73 info retry will retry, error on last attempt: Error: read ECONNRESET
74 info retry will retry, error on last attempt: Error: read ECONNRESET
75 silly fetchAndShaCheck shasum af493d5df4688d917d778b0934d1739b9be6efe6
76 verbose stack Error: shasum check failed for C:\Users\BASHEER\AppData\Local\Temp\npm-4908-33100c61\registry.npmjs.org\ionic\-\ionic-1.7.14.tgz
76 verbose stack Expected: af493d5df4688d917d778b0934d1739b9be6efe6
76 verbose stack Actual:   0f8371451e573dd10fb081580f7a11b22b0417ca
76 verbose stack From:     https://registry.npmjs.org/ionic/-/ionic-1.7.14.tgz
76 verbose stack     at C:\Program Files\nodejs\node_modules\npm\node_modules\sha\index.js:25:8
76 verbose stack     at ReadStream.<anonymous> (C:\Program Files\nodejs\node_modules\npm\node_modules\sha\index.js:72:7)
76 verbose stack     at emitNone (events.js:72:20)
76 verbose stack     at ReadStream.emit (events.js:166:7)
76 verbose stack     at endReadableNT (_stream_readable.js:913:12)
76 verbose stack     at nextTickCallbackWith2Args (node.js:442:9)
76 verbose stack     at process._tickCallback (node.js:356:17)
77 verbose cwd C:\Users\BASHEER
78 error Windows_NT 10.0.10240
79 error argv "C:\\Program Files\\nodejs\\node.exe" "C:\\Program Files\\nodejs\\node_modules\\npm\\bin\\npm-cli.js" "install" "-g" "cordova" "ionic"
80 error node v4.4.3
81 error npm  v2.15.1
82 error shasum check failed for C:\Users\BASHEER\AppData\Local\Temp\npm-4908-33100c61\registry.npmjs.org\ionic\-\ionic-1.7.14.tgz
82 error Expected: af493d5df4688d917d778b0934d1739b9be6efe6
82 error Actual:   0f8371451e573dd10fb081580f7a11b22b0417ca
82 error From:     https://registry.npmjs.org/ionic/-/ionic-1.7.14.tgz
83 error If you need help, you may report this error at:
83 error     <https://github.com/npm/npm/issues>
84 verbose exit [ 1, true ]
