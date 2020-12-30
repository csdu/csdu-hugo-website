Student managed website for Department of Computer Science Society, University of Delhi.

Built using [hugo](https://gohugo.io/) static site generator and [Terminal.css](terminalcss.xyz/).

# Development

## Requirements

just the `hugo` binary. Which you can download and install from https://gohugo.io/getting-started/installing/.

## Installation

```bash
# clone this repository
git clone https://github.com/csdu/csdu.github.io

# go to working directory
cd csdu.github.io
```

## Start local dev server

```bash
# to start local dev server on http://localhost:1313/
hugo server
```

## Build Site

Build static version of the site which you can deploy on any server. This will create a `public` directory which you can deploy on the server. 

```bash
# In csdu.github.io/ 
hugo
```
