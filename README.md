# pdf-autoprint
Add auto printing javascript to PDFs


## Install
You'll need [python](https://www.python.org/) installed

    pip install git+ssh://git@github.com/millerhare/pdf-autoprint.git


## Usage

    $ pdf-autoprint.py --help
    pdf-autoprint, embed auto print JavaScript to a PDF document that will execute automatically when the document is opened

    Usage: pdf-autoprint [options] in-pdf-file out-pdf-file

    Options:
      --version   show program's version number and exit
      -h, --help  show this help message and exit

So for example

    pdf-autoprint.py in.pdf out.pdf

It also supports glob matching which is used in the following way. Note the outpath **must** be a directory if the glob matches multiple files.

    pdf-autoprint.py "doc*.pdf" out/


## License
MIT
