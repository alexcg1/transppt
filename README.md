# transppt
Transppt is a simple Python program to translate Powerpoint files from the command line while retaining formatting, images, autoshapes, etc.

## Requirements

* Python 3 (Python 2 may work as well, but I haven't tested it)
* [Google Cloud Translation API Library](https://cloud.google.com/translate/docs/reference/libraries#client-libraries-install-python)
* [python-pptx](https://pypi.python.org/pypi/python-pptx)
* Optional: [progress](https://pypi.python.org/pypi/progress)

## Usage
<pre>transppt.py <input filename></pre>

Output filename will be <target_language>_<input filename>

## Notes
By default this translates to English. Change target variable to suit your needs :)

## Todo

* Code cleanup
