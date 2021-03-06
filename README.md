# tkJSPinyin

[![LICENSE](https://img.shields.io/badge/license-NPL%20(The%20996%20Prohibited%20License)-blue.svg)](https://github.com/996icu/996.ICU/blob/master/LICENSE)
<a href="https://996.icu"><img src="https://img.shields.io/badge/link-996.icu-red.svg" alt="996.icu"></a>

Get Chinese pinyin from Chinese. Based on [JSPinyin](https://github.com/chinalu/JSPinyin). Ported to ES6, no need for mootool, etc. See `/src` for code.

# Install

```fish
bower install tkJSPinyin
```

# How to use
include the js file, and type:
```js
var pinyin = new Pinyin(false, 'default');// checkPolyphone = false;	charcase = 'default';
alert(pinyin.getFullChars('你好中国'));// NiHaoZhongGuo
```
# LICENSE
```
Copyright (c) 2019 Han

Anti 996 License Version 1.0 (Draft)

Permission is hereby granted to any individual or legal entity obtaining a copy
of this licensed work (including the source code, documentation and/or related
items, hereinafter collectively referred to as the "licensed work"), free of
charge, to deal with the licensed work for any purpose, including without
limitation, the rights to use, reproduce, modify, prepare derivative works of,
publish, distribute and sublicense the licensed work, subject to the following
conditions:

1.  The individual or the legal entity must conspicuously display, without
    modification, this License on each redistributed or derivative copy of the
    Licensed Work.

2.  The individual or the legal entity must strictly comply with all applicable
    laws, regulations, rules and standards of the jurisdiction relating to
    labor and employment where the individual is physically located or where
    the individual was born or naturalized; or where the legal entity is
    registered or is operating (whichever is stricter). In case that the
    jurisdiction has no such laws, regulations, rules and standards or its
    laws, regulations, rules and standards are unenforceable, the individual
    or the legal entity are required to comply with Core International Labor
    Standards.

3.  The individual or the legal entity shall not induce or force its
    employee(s), whether full-time or part-time, or its independent
    contractor(s), in any methods, to agree in oral or written form,
    to directly or indirectly restrict, weaken or relinquish his or
    her rights or remedies under such laws, regulations, rules and
    standards relating to labor and employment as mentioned above,
    no matter whether such written or oral agreement are enforceable
    under the laws of the said jurisdiction, nor shall such individual
    or the legal entity limit, in any methods, the rights of its employee(s)
    or independent contractor(s) from reporting or complaining to the copyright
    holder or relevant authorities monitoring the compliance of the license
    about its violation(s) of the said license.

THE LICENSED WORK IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE COPYRIGHT
HOLDER BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN ANY WAY CONNECTION
WITH THE LICENSED WORK OR THE USE OR OTHER DEALINGS IN THE LICENSED WORK.

```
