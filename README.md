# NodeJS ExpressJS and MongoDB Notes


## JS - was meant to run only in the browser

Following are some JS engines that are present in modern day browser to run JavaScript:

Google Chrome - V8 Engine.
Mozilla Firefox - SpiderMonkey.

Node was developed by Ryan Dahl to run JS outside of the browser.

Node = V8 Engine/SpiderMonkey + Inbuilt Node Modules

Node is a Runtime environment, that allows JS to run outside of browsers in local machines as well.

Now lets see some quick examples to understand this concept of runtime environment:

Playstation games can run in a play station console only.
I can make tandoori roti in a tandoor only.


### CJS

//for importing

const x = require("module")

//for exporting
module.exports = x

Common JS method is used to import or export any Node module.

We are not using ES6 method of importing and exporting because almost all the industries in the market use the CJS method only, and we have to align with the same as most of the resources present on web also prefers the same.

### Node REPL

Read ⇒ Evaluate ⇒ Print ⇒ Loop

Explore this by your own, Do Experiments.

#### JavaScript is….

Single Threaded.
Asynchronous.
Dynamically Typed.
Concurrent.

Note: Go through the Documentation of node as well, and experiment yourself,
specially try some of the inbuilt node modules.