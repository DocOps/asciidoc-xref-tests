# AsciiDoc Xref Testing

Experimental repo based loosely on the Jekyll-now bootstrap theme by Barry Clark: http://jekyllthemes.org/themes/jekyll-now/

## Build

Requires Asciidoctor 1.5.7+ and Jekyll 3+

To test this repo:

### Build HTML Book

```shell
asciidoctor -d book -o _output/book-edition.html pages/book-index.adoc
```

### Build PDF Book

```shell
asciidoctor-pdf -d book -o _output/book-edition.pdf pages/book-index.adoc
```

### Build and Serve Jekyll Site
```shell
jekyll s
```
