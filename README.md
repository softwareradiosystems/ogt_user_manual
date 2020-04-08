Osmo-GSM-Testers User Manual
============================

Dependencies
------------

This manual requires osmo-gsm-manuals (https://github.com/osmocom/osmo-gsm-manuals):
```
git clone https://github.com/osmocom/osmo-gsm-manuals.git
```

To build the manual, the following are needed, by example of a debian system:

```
sudo apt-get install \
  make \
  asciidoc \
  asciidoc-dblatex \
  xsltproc \
  dblatex \
  docbook5-xml \
  mscgen \
  graphviz \
  python3-nwdiag
```

Dependencies for "make check":

```
sudo apt-get install libxml2-utils
```

Building
--------

Optionally test building all shared content (use -j for parallel building):
- make        # generate test PDFs
- make check  # test for asciidoc errors
