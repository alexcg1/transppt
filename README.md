# transppt
Transppt is a simple Python script to translate Powerpoint files from the command line while retaining formatting, images, autoshapes, etc.

## Requirements

* Python 3 (Python 2 may work as well, but I haven't tested it)
* [Google Cloud Translation API Library](https://cloud.google.com/translate/docs/reference/libraries#client-libraries-install-python)
* Google Service Account Key (via [Google Cloud Translation API Library](https://cloud.google.com/translate/docs/reference/libraries#client-libraries-install-python) page)
* [python-pptx](https://pypi.python.org/pypi/python-pptx)
* Optional: [progress](https://pypi.python.org/pypi/progress)

## Usage
<pre>transppt.py input_filename</pre>

Output filename will be target_language_input_filename (en_input_filename by default)

## Notes
By default transppt translates to English. Change target variable to suit your needs :)

## Todo

* Code cleanup
* Arguments for output language and output filename
* Maybe add support for other Office formats
