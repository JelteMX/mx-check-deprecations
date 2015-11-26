# Mendix Deprecation checker for widgets

This tool is in beta. It checks your .MPK files (widgets) for any Mendix 6 Javascript deprecations.

## Install

Make sure you have Node.JS installed.

Run:

```bash
	npm install mx-check-deprecations -g
```

This will install the checker globally.

## Usage

Run it in your folder where you have widget (.mpk) files:

```bash
	mx-check-deprecations
```

Or check a single widget / list of widgets:

```bash
	mx-check-deprecations WidgetFile.mpk WidgetFile2.mpk ...
```

## Help

```bash
	mx-check-deprecations -h
```

## License

The MIT License (MIT)

Copyright (c) 2015 Jelte Lagendijk

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