# Krishnamurthy Ganesh - projects

Ganesh is people manager who learnt the art of programming like you. Hands on.

Ganesh comes with problems solving skills and strive to solve some serious industry problems like you. Ganesh comes with technical and key skills are `js`, `angular`, `react`, `typescript`, `nodejs`, anything javascript, `python`, `django`, `data science`, `project management`. I am a `golang` beginner. Ganesh is an `BS 7799 data security organizational internal auditor`, `ISO 9001 organzational internal auditor`, and `Six Sigma Green belt candidate`.

Ganesh `IS` an `Accountable`, `Responsible`, and `Ethical` programmer. Learnings and Earnings will happen life long and are important. Do not, and `NEVER forget` the `ethics`, `empathy`, and `compassion`.

---

Key projects being worked on along with their problem statements and status. [ganeshkbhat](https://www.github.com/ganeshkbhat)

- [taskcontrols](#taskcontrols) - `Workflow Automation Library` with support for Concurrent, or Event based processes/activities in Local/Network Automation Tasks.
- [desktop-cgi](#desktopcgi) - Create `Desktop executable app` using interpreted languages like `PHP`, `Ruby`, `Python`, `Perl`, `CGI`, `JSP`, `ASPX`, `Other` Interpreted Languages).
- [cgijs](#cgijs), [phpcgijs](#phpcgijs) - CGIJS is a library to `run any` CGI mode / `Interpreted language script files`, or connect to any web application server proxies, or manage processes in the system.
- [require-urls](#requireurls) - `Require` / `Import` Deno and GoLang style `remote urls`.
- [loadbalancer](#loadbalancerjs) - threaded and clustered load balancer for nodejs with different forwarding algorithms and server request handling options
- [fastprimenumbers](#fastprimenumbers), [fast-prime](#fastprime), [fast-prime-client](#fastprimeclient), [fasterprimes](#fasterprimes) - Fastest `Prime Number` Calculation (`checks` and `generation`) logic.
- [hasher-apis](#hasherapis) - Simple implementation of `Crypto Module functions` to hash/ encrypt/ decrypt content and get SHA or other algorithm hashes of text or any data.

---

---

Other projects and status. [ganeshkbhat](https://www.github.com/ganeshkbhat)

- [traverse-fs](#traversefs), [fssys](#fssys) - `Traversing` and (glob) `searching` file and folder system recursively along with other utility functions.
- [check-esm](#checkesm), [get-imported](#getimported) - Check/ `Get` all `imports` or `required` modules and check if the file is a ES Module or a CJS/ JS Module or Script.
- [root-dirs](#rootdirs) - `Get root folders` of git, svn, mercurial, nodejs node_modules / package.json / package-lock.json, and nodejs .jscache folder.
- [concurrency.js](#concurrencyjs) - Module to work with `concurrency` - worker threads and worker processes.
- [request-apis](#requestapis) - Common request APIs and basic `http` requests utils.
- [queues.js](#queuesjs) - node package for top and bottom plus lifo/ fifo queues, stack, priority queues, double ended queues, circular queues, wait queues (TODO), and semaphore queues (TODO) implementation.
- [extenders](#extenders) - node package for Array, Object, String, Decorator extention Utils like for Python and more for Node.js.
- [mutables](#mutables) - Manage immutable stores with no jazz in a simple manner. Exploring simpler immutable stores architectures.

- [store](#store):  [github](https://github.com/ganeshkbhat/store) , [npm](https://www.npmjs.com/package/managers)
- [mod-pickle](#mod-pickle):  [github](https://github.com/ganeshkbhat/pickler) , [npm](https://www.npmjs.com/package/mod-pickle)
- [ndarrays](#ndarrays):  [github](https://github.com/ganeshkbhat/numericalarrays) , [npm](https://www.npmjs.com/package/ndarrays)
- [express-noserve](#express-noserve):  [github](https://github.com/ganeshkbhat/noserver-expressjs) , [npm](https://www.npmjs.com/package/express-noserve)
- [noserve](#noserve):  [github](https://github.com/ganeshkbhat/noserver-expressjs) , [npm](https://www.npmjs.com/package/noserve)

---

#### <a name="taskcontrols"></a>taskcontrols

Status: `[indevelopment (MVP)]`

[taskcontrols](https://www.github.com/taskcontrols) - DevOps (DevSecOps) Workflow Automation Library with support for Concurrent, or Event based processes/activities in Local/Network Automation Tasks

`taskcontrol` is intended to be a set of multi-language micro-libraries (`python`, `nodejs`[todo], `typescript`[todo]) to `create, run, manage, and monitor tasks and workflows with data persistance and task-unit level secure operations`. It allows working with multiple architecture modes (with data persistance and security) including `publisher-subscriber`, `agent-less`, `server-agent`, `web api`, `webhooks`, and `message queues`.

- [git python repo](https://www.github.com/taskcontrols/py-taskcontrols), [pypi taskcontrol](https://pypi.org/project/taskcontrol/) [in active development]

`pip3 install taskcontrol`

- [git nodejs repo](https://github.com/taskcontrols/js-taskcontrol), [nodejs taskcontrol](https://www.npmjs.com/package/taskcontrol) [indevelopment - do not install]

`npm install taskcontrol`

---

#### <a name="desktopcgi"></a>desktop-cgi

Status: `[indevelopment (MVP)]`

[desktop-cgi](https://www.github.com/desktop-cgi) - Desktop apps using DesktopCGI, CGIJS, PHPCGIJS, [git repo https://www.github.com/desktop-cgi](https://www.github.com/desktop-cgi/desktop-cgi)

Create Desktop executable app using CGI files, embedded webserver CGI apps (`PHP`, `Ruby`, `Python`, `Perl`, `CGI`, `JSP`, `ASPX`, `Other` Interpreted Languages), or remote proxies.

`Desktop-CGI` is a desktop executable app that can be created from any CGI files or CGI web apps that can be served from an file, an embedded web server using proxy, or an remote proxy web server. It supports embedding and managing embeddable databases and executables. It supports all major Operating systems supported by electron like Windows, Linux, and MacOS supported by Electron.

---

#### <a name="cgijs"></a>cgijs

Status: `[production ready] [indevelopment (new features)]`

[cgijs](https://www.github.com/cgi-js) - Run cgi / interpreted script files that supports command line execution, or connect to cgi / other server proxies, [git repo](https://github.com/cgi-js/cgi-js) , [npmjs cgijs](https://www.npmjs.com/package/cgijs)

`CGIJS` is a library to run any CGI mode / Interpreted language script files, or connect to any web application server proxies, or manage processes in the system. `CGIJS` library:

- Supports running any `CGI` / `Interpreted Language scripts` in `any OS` that runs `node.js`.
- Supports both `CGI` executables as well as `proxy` to `localhost`/ `remote` /`embedded servers` using proxying of multiple protocols (`http`, `websockets`, `tcp`, `udp`, `socks`, `ssh`, `ftp`).
- Supports managing processes like `embedded` `server` executables, embedded `database` executables, or `any other` embedded/ non-embedded executables

`npm install cgijs --save`

---

---

#### <a name="loadbalancerjs"></a>loadbalancerjs

Status: `[production ready] [indevelopment (new features)]`

[loadbalancer](https://www.github.com/ganeshkbhat/loadbalancer) - [git repo](https://www.github.com/ganeshkbhat/loadbalancer) , [npmjs loadbalancer](https://www.npmjs.com/package/loadbalancerjs)

`npm install loadbalancerjs --save`

---

#### <a name="phpcgijs"></a>phpcgijs

Status: `[production ready] [indevelopment (new features)]`

[phpcgijs](https://github.com/cgi-js/node-php-cgi) - Run php scripts like wordpress, drupal, etc with node and cgi counter parts, [git repo](https://github.com/cgi-js/node-php-cgi), [npmjs phpcgijs](https://www.npmjs.com/package/phpcgijs)

Run php scripts like wordpress, drupal, etc with node and cgi counter parts using `phpcgijs`. The script will pipe all files that end in the .php extension through the php parser. All other files will be served as static content. Basic permalinks are supported but the support for them can probably be improved.

Includes `CGIJS` Library as a dependancy.

`npm install phpcgijs --save`

---

#### <a name="traversefs"></a>traverse-fs

Status: `[production ready] [consideration (new features)]`

[traverse-fs](https://github.com/traverse-fs/glob-traverse-fs) - Traversing file system recursively, [git repo](https://github.com/traverse-fs/glob-traverse-fs), [npmjs traverse-fs](https://www.npmjs.com/package/traverse-fs)

`traverse-fs` is a npm module to traverse files and folder using code, or cli, or use glob patterns

`npm install traverse-fs --save`

---

#### <a name="fssys"></a>fssys

Status: `[production ready] [consideration (new features)]`

[fssys](https://github.com/traverse-fs/fssys) - Traversing file system recursively, [git repo](https://github.com/traverse-fs/glob-traverse-fs), [npmjs fssys](https://www.npmjs.com/package/fssys)

`fssys` is a npm module to read write folder/files, fs util functions, traverse files and folder using code, or cli, or use glob patterns

`npm install fssys --save`

---

#### <a name="requireurls"></a>require-urls

Status: `[indevelopment (MVP)]`

[require-urls](https://github.com/ganeshkbhat/require-urls) - Require / Import Deno and GoLang style remote urls, [git repo](https://github.com/ganeshkbhat/require-urls), [npmjs require-urls](https://www.npmjs.com/package/require-urls)

`Deno and GoLang Mode` in `commonjs import` (`require`) and `ES import` syntax using `require-urls`: Replace nodejs require function with requireurls function or use loader.mjs replacing import functionality that can fetches remote urls.

`npm install require-urls --save`

---

#### <a name="fastprimenumbers"></a>fastprimenumbers

Status: `[production ready]`

[fastprimenumbers](https://github.com/ganeshkbhat/fastprimenumbers) - Probably the fastest prime number calculations, [git repo](https://github.com/ganeshkbhat/fastprimenumbers), [npmjs fast-prime](https://www.npmjs.com/package/fast-prime), [pypi fastprime](https://pypi.org/project/fasterprimes/)

`Fastest Prime Number Calculation (checks) logic` and This probably is the BEST solution in the internet as of today 11th March 2022. This same code has been applied in many languages (and can be applied to) like `Python`, `Java`, `PHP`, `Node.js`, `Javascript`, `typescript` and can be applied to `C`, `Go` Lang, `C++`, `.NET`, `Rust`, etc with the same logic and have performance benefits.

It is pretty fast based on the number of iterations needed. Performance time checks were not consistent across languages (in my local system - to be direct about wordings). I have not seen this implemented before and has been indigenously done. Feedback and usage is welcome.

`Max iterations 16666 for n == 100000 instead of 100000 of conventional way.`

`npm install fast-prime --save` , `npm install fast-prime-client --save` , `pip3 install fasterprimes`

---

#### <a name="fastprime"></a>fast-prime

Status: `[production ready]`

[fast-prime](https://github.com/ganeshkbhat/fastprimenumbers/tree/main/nodejs) Fastest Prime Number Calculation (checks) logic for node and browser. Fastest Prime Number Calculation (checks) logic and This probably is the BEST solution in the internet as of today 11th March 2022. [https://github.com/ganeshkbhat/fastprimenumbers/tree/main/nodejs](https://github.com/ganeshkbhat/fastprimenumbers/tree/main/nodejs)

`npm install fast-prime --save`

---

#### <a name="fastprimeclient"></a>fast-prime-client

Status: `[production ready]`

[fast-prime-client](https://github.com/ganeshkbhat/fastprimenumbers/tree/main/javascript) Fastest Prime Number Calculation (checks) logic for browser. Fastest Prime Number Calculation (checks) logic and This probably is the BEST solution in the internet as of today 11th March 2022. [https://github.com/ganeshkbhat/fastprimenumbers/tree/main/javascript](https://github.com/ganeshkbhat/fastprimenumbers/tree/main/javascript)

`npm install fast-prime-client --save`

---

#### <a name="checkesm"></a>check-esm

Status: `[production ready] [consideration (new features)]`

[check-esm](https://www.npmjs.com/package/check-esm) -
JS functions to `check all imports or required modules` and `check if` the file is a `ES Module` or a `CJS/ JS Module` or `Script` [https://github.com/ganeshkbhat/get-isesm](https://github.com/ganeshkbhat/get-isesm)

`npm install check-esm --save`

---

#### <a name="getimported"></a>get-imported

Status: `[production ready]`

[get-imported](https://www.npmjs.com/package/get-imported) -
JS functions to `check all imports or required modules` and `check if` the file is a `ES Module` or a `CJS/ JS Module` or `Script` [https://github.com/ganeshkbhat/get-imports](https://github.com/ganeshkbhat/get-imports)

`npm install get-imported --save`

---

#### <a name="rootdirs"></a>root-dirs

Status: `[production ready] [consideration (new features)]`

[root-dirs](https://github.com/ganeshkbhat/get-root) -
Get root folders of `git`, `svn`, `mercurial`, nodejs `node_modules` / `package.json` / `package-lock.json`, and nodejs `.jscache` folder [https://github.com/ganeshkbhat/get-root](https://github.com/ganeshkbhat/get-root)

`npm install root-dirs --save`

---

#### <a name="hasherapis"></a>hasher-apis

Status: `[production ready]`

[hasher-apis](https://www.npmjs.com/package/hasher-apis) - Simple and flexible implementation Crypto Module functions to hash/ encrypt/ decrypt content and get SHA or other algorithm hashes of text or any data [https://github.com/ganeshkbhat/hasher-apis](https://github.com/ganeshkbhat/hasher-apis)

`npm install hasher-apis --save`

---

#### <a name="concurrencyjs"></a>concurrency.js

Status: `[indevelopment (MVP)] [indevelopment (new features)] [consideration (new features)]`

[concurrency.js](https://www.npmjs.com/package/concurrency.js) - npm module to work with `concurrency - worker threads and worker processes` easily using simple functions and script files [https://github.com/ganeshkbhat/concurrency.js](https://github.com/ganeshkbhat/concurrency.js)

`npm install concurrency.js --save`

---

#### <a name="requestapis"></a>request-apis

Status: `[indevelopment (MVP)]`

<!-- `[production ready]` -->

[request-apis](https://www.npmjs.com/package/request-apis) - npm module for common request APIs and basic http requests utils [https://github.com/ganeshkbhat/request-apis](https://github.com/ganeshkbhat/request-apis)

`npm install request-apis --save`

---

#### <a name="queuesjs"></a>queues.js

Status: `[production ready] [indevelopment (new features)] [consideration (new features)]`

[ queues.js](https://www.npmjs.com/package/queues.js) - node package for top and bottom plus lifo/ fifo queues, stack, priority queues, double ended queues, circular queues (TODO), wait queues (TODO), and semaphore queues (TODO) implementation [https://github.com/ganeshkbhat/queues.js](https://github.com/ganeshkbhat/queues.js)

`npm install queue.js --save`

---

#### <a name="extenders"></a>extenders

Status: `[indevelopment (MVP)] [consideration (new features)]`

[extenders](https://www.npmjs.com/package/extenders) - node package for Array, Object, String, Decorator extention Utils like for Python and more for Node.js [https://github.com/ganeshkbhat/jsextenders](https://github.com/ganeshkbhat/jsextenders)

`npm install extenders --save`

---

#### <a name="mutables"></a>mutables

Status: `[indevelopment (MVP)]`

[mutables](https://www.npmjs.com/package/mutables) - npm module to work with immutable stores. Manage immutable stores with no jazz in a simple manner. Exploring simpler immutable stores architectures [https://github.com/ganeshkbhat/store](https://github.com/ganeshkbhat/store)

`npm install mutables --save`

<!--


#### <a name="link"></a>link

Status: `[indevelopment (MVP)]`


[link](https://www.npmjs.com/package/link) - [https://github.com/ganeshkbhat/link](https://github.com/ganeshkbhat/link)


`npm install link --save`

 -->

<!--

https://github.com/ganeshkbhat/apis-git
https://github.com/ganeshkbhat/apis-mercurial
https://github.com/ganeshkbhat/apis-svn
https://github.com/ganeshkbhat/store
https://github.com/ganeshkbhat/concurrency.js.extended

-->

---
