# CSS FLEX DIRECTION

  Mobile-first classes for css-flex-direction.
  Set the desired css-flex-direction on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
```
npm install --save-dev css-flex-direction
```
or download the css on github and include in your project.

## File Size


## The Code
```
.fd-row {     flex-direction: row; }
.fd-rev {     flex-direction: row-reverse; }
.fd-col {     flex-direction: column; }
.fd-colrev {  flex-direction: column-reverse; }
.fd-i {       flex-direction: inherit; }

@media screen and (min-width: 48em) {
  .fd-row-ns {     flex-direction: row; }
  .fd-rev-ns {     flex-direction: row-reverse; }
  .fd-col-ns {     flex-direction: column; }
  .fd-colrev-ns {  flex-direction: column-reverse; }
  .fd-i-ns {       flex-direction: inherit; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .fd-row-m {     flex-direction: row; }
  .fd-rev-m {     flex-direction: row-reverse; }
  .fd-col-m {     flex-direction: column; }
  .fd-colrev-m {  flex-direction: column-reverse; }
  .fd-i-m {       flex-direction: inherit; }
}

@media screen and (min-width: 64em)  {
  .fd-row-l {     flex-direction: row; }
  .fd-rev-l {     flex-direction: row-reverse; }
  .fd-col-l {     flex-direction: column; }
  .fd-colrev-l {  flex-direction: column-reverse; }
  .fd-i-l {       flex-direction: inherit; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

