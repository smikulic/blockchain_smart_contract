1. Setup dev environment
- install metamask - Chrome Plugin https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=en
- install addon build tool "npm install -g node-gyp"
- install Ethereum RPC for testing and development "npm install -g ethereumjs-testrpc"
- install Truffle development environment, testing framework and asset pipeline for Ethereum "npm install -g truffle"

2. Initialize truffle "truffle init"

3. Development process
- update/add contract
- update deployment for new contract (in migrations/deploy_constracts.js)
- start server "testrpc"
- compile src "truffle compile"
- deploy to test(local) blockchain "truffle migrate"

"truffle console" - console mode
try out hello world by using:
var hello
HelloWorld.deployed().then(function(deployed){hello=deployed;});
hello.sayHello.call()

and to inspect the block: "hello.sayHello()"



PRESENTATION
01. What is Blockchain
02. Bitcoin and Blockchain
03. How Does It Work
