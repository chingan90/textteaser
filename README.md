TextTeaser
=============

TextTeaser is an automatic summarization algorithm. 

This fork adds Python 3.x support while implementing additional functions.

### Installation

    >>> git clone https://github.com/chingan90/textteaser.git
    >>> pip install -r textteaser/requirements.txt

### How to Use

    >>> from textteaser import TextTeaser
    >>> tt = TextTeaser()
    >>> tt.summarize(title, text)

You can also test TextTeaser by running `python test.py`.
