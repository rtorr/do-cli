#DigitalOcean CLI

Super basic and alpha cli for the DigitalOcean API.

### Set up

Add a `do-conf.js` file in your working directory.

```
module.exports = {
  clientId: '',
  apiKey: ''
};
```

### Commands

```
Usage: do-cli [id] {OPTIONS}

Standard Options:

    --id      <id>
              Allows you to set id for multiple operations

    --ls      Lists Droptlets

    --names   Lists names of Droptlets

    --reboot  Takes <id> as the second argument or set --id <id>
              Reboots Droptlet.

    --pc      Takes <id> as the second argument or set --id <id>
              Power Cycle Droplet.

    --sd      Takes <id> as the second argument or set --id <id>
              Shut Down Droplet.

    --help    Lists options  Lists options
```

### TODOs

* Use enviroment variables for the API keys
* More commands

### Acknowledgements

Mostly a wrapper around [https://github.com/enzy/digitalocean-api](https://github.com/enzy/digitalocean-api)

The MIT License (MIT)

Copyright (c) 2014 Richard Torruellas 

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
