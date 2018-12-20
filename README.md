# AsciiDoc Xref Testing

Experimental repo based loosely on the Jekyll-now bootstrap theme by Barry Clark: http://jekyllthemes.org/themes/jekyll-now/

## Build

Requires Asciidoctor 1.5.7+ and Jekyll 3+

To test this repo:

### Build HTML Book

#### From project root

```shell
asciidoctor -d book -o _output/book-edition.html -a bookformat=true book-index-root.adoc
```
#### From pages/ dir

```shell
asciidoctor -d book -o _output/book-edition.html -a bookformat=true pages/book-index-flush.adoc
```

### Build PDF Book

#### From project root

```shell
asciidoctor-pdf -d book -o _output/book-edition.pdf -a bookformat=true book-index-root.adoc
```

#### From pages/ dir

```shell
asciidoctor-pdf -d book -o _output/book-edition.pdf -a bookformat=true pages/book-index-flush.adoc
```

### Build and Serve Jekyll Site
```shell
jekyll s
```
