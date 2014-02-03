UNTV
====

UNTV is a cross platform DRM-free media platform for home theater computers. 
This project is very new, so right now your best bet is to check out the 
[docs/](https://github.com/gordonwritescode/untv/tree/master/docs) directory.

## Getting Started

### End Users

Download the latest bundled application for your platform:

> **UNTV bundled applications are not yet available.**

* GNU/Linux: [64bit](#) | [32bit](#)
* Mac OSX 10.7+: [32bit](#)
* Windows: [32bit](#)

Place in your Applications directory (or equivalent) and launch as usual. 

### Developers

Since UNTV is very much in infancy, I do not provide pre-built binaries (yet). 
UNTV also depends on a custom build of 
[Node-Webkit](https://github.com/rogerwang/node-webkit) which I have compiled 
for linux64, darwin32, and win32.

##### Clone the repository:

```
~# git clone https://github.com/gordonwritescode/untv.git
```

##### Install dependencies using Node Package Manager:

```
~# cd untv && sudo npm install
```

#####  Make sure you have CoffeeScript installed globally (we use `cake` for tasks):

```
~# sudo npm install coffee-script -g
```

##### Run `cake setup` from the project root

> Alternatively download the custom build of node-webkit here: 
> https://file.ac/s4Lt3Vo6rls/
> Then, unzip and place contents in the `bin/nw-0.8.4-custom` directory.

#####  Run `cake start` from the project root.
