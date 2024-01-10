# Crawl 2 PDF
Recursively crawl a URL and save all pages in a PDF.

## Prerequisites

**Ubuntu / Debian**
```sh
$ sudo apt update
$ sudo apt install -y wkhtmltopdf
```

## Install

**From remote**
```sh
$ wget https://raw.githubusercontent.com/kevinfarrugia/crawl2pdf/main/crawl2pdf
$ chmod +x crawl2pdf
```

**From source**
```sh
$ git clone https://github.com/kevinfarrugia/crawl2pdf.git
$ chmod +x crawl2pdf/crawl2pdf
```

## Usage

**Basic example**
```sh
$ crawl2pdf https://imkev.dev -o output.pdf
```

**Example with custom options**
```sh
$ crawl2pdf https://imkev.dev -o output.pdf -d 2 -w 1
```

The preceding example will crawl with a recursive depth of 2 and a wait time of 1 second between each request.

## License and Copyright

This software is released under the terms of the [Apache License 2.0](https://github.com/kevinfarrugia/crawl2pdf/blob/main/LICENSE).
