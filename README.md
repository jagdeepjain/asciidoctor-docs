# Ski11Up Blogs

## Build

```
$ rake 'doc:build[name-of-the-doc]'
```

Example, if we are building `sample.adoc` then the enter below command in the terminal window.

```
$ rake 'doc:build[sample]'
```

## Check Html

Open the respective `.html` file in the browser to check the same.

## Writers Guide

https://asciidoctor.org/docs/asciidoc-writers-guide/

## Using Theme

```
asciidoctor -a stylesheet=./stylesheets/asciidoctor.css sample.adoc
```
