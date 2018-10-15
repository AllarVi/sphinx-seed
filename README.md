# Sphinx setup

1. Install sphinx

'''pip install sphinx'''

2. Go to docs directory and launch sphinx-quickstart

'''sphinx-quickstart'''

3. For markdown support

'''pip install recommonmark'''

4. Then in your '''conf.py''':

'''python
from recommonmark.parser import CommonMarkParser

source_parsers = {
    '.md': CommonMarkParser,
}

source_suffix = ['.rst', '.md']
'''
