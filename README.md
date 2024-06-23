# AsciiDoc Book Template
- EPUB3
- PDF with light, dark and sepia theme

## Build
Use the docker image: https://github.com/asciidoctor/docker-asciidoctor

Run commands:  
```
asciidoctor-epub3 -D output -a ebook-validate sample.adoc

asciidoctor-pdf -a pdf-theme=light -a pdf-themesdir=resources/themes sample.adoc -o output/sample-light.pdf
asciidoctor-pdf -a pdf-theme=sepia -a pdf-themesdir=resources/themes sample.adoc -o output/sample-sepia.pdf
asciidoctor-pdf -a pdf-theme=dark -a pdf-themesdir=resources/themes sample.adoc -o output/sample-dark.pdf
```

## Example
See [releases](https://github.com/Lixfeld/AsciiDoc-Book-Template/releases).  
