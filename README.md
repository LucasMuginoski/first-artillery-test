﻿# first-Artillery-Test

This is my Very First Artillery Test - load testing tool

Install Artillery via npm:
```console
    npm install -g artillery@latest
```
Checking your installation:
```console
    artillery dino
```

Running test:
```console
    artillery run search-and-add-to-cart.yml --output test.json
```

Converted into an HTML report through the Command:
```console
    artillery report --output report.html test.json
```

Now open your report.html file.

NOTE: this test.json and report.html files are beeing ignored in my repository.
