# error.php

error.php is a simple and easy way to create a custom error page for your website

## Installation and Usage

Just add the following lines to your htaccess files and your good to go.

```
ErrorDocument 401 /path/to/error.php?id=401
ErrorDocument 403 /path/to/error.php?id=403
ErrorDocument 404 /path/to/error.php?id=404
ErrorDocument 408 /path/to/error.php?id=408
ErrorDocument 500 /path/to/error.php?id=500
ErrorDocument 504 /path/to/error.php?id=504
```
If you don't see the error code that you want to use just add a new entry to error.php and add the line to your htaccess file

```
ErrorDocument <id> /path/to/error.php?id=<id>
```

## Development

The next thing that I'm working on is to make it so you don't have to ad the id= part.

## Copyright and License

The MIT License (MIT)

Copyright © 2013 Simon van Daalen, http://www.toaos.tk

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the “Software”), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.