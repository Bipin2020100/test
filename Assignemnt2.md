V8 is Google's open source high performance JavaScript and Web Assembly engine where as SpiderMonkey is Mozilla's Javascript engine. V8 is written in C++ and is crome and node.js. 
Spider monkey on the otehr hand is used in various Mozilla's products including Firefox. SpiderMonkey is written in C and C++. JavaScript enjines were just intrepretres before i.e. They used to go throught he code line by line. There was no compilation process involved. Now JavaScript engines use compiler. V8 has JiT(Just in Time) compilation. V8 gets shipped with node.js run time. V8 engine has node.js at its  core.
SpiderMonkey on the other hand uses JavaScript shell in it's open source distribution. JavaScript shell is a command -line program. The shell offers two modes of operation. You can use it as an interactive shell, in which you type JavaScript code at a prompt and get instant gratification, which is handy for experimenting or testing new features. You can also pass in, on the command line, a JavaScript program file to run, in which case the program is run automatically.
SpiderMonkey is the original JavaScript engine first introduced as part of Netscape Navigator. The updates to SpiderMonkey includes TraceMonkey, IonMonkey. Latest version of Mozilla uses IonMonkey and TraceMonkey is absent from SpiderMonkey type interface engine. Even though V8 is first introduced as a part of google crome, v8 seems to be faster engiene. Substantial updates to spiderMonkey including TraceMonkey has helped close the gap. Where SpiderMonkey compiles JavaScript to an intermediate language which is interpreted later on V8 compiles JavaScript to machine instructions, eliminating a need for an interpreter.

souce taken from:
<https://developer.mozilla.org/>
<https://v8.dev/>
<https://developer.mozilla.org/en-US/docs/Mozilla/Projects/SpiderMonkey/Introduction_to_the_JavaScript_shell>
<https://www.quora.com/How-do-V8-and-SpiderMonkey-differ>
