# PDF Password Cracker
This Python Jupyter notebook implements a basic PDF password cracking tool using the pikepdf library.

![Image Description](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjZFmjwNHnIuGZ7dRKugoMnnEHMsqjXIxv5V_5MqZw6M1eSVPX3xhRtx_SGSnI5tKEN5f7G81Dki8MDuVETai8RVNBcgIRqvaNnB_6Kl6bPYivnsys1iYj0fxX1q7cse3jL3jASgZhGt0vHAw964tVkzeOIyp-GM6eARHEVha5vzxEgcbY0Fmhurj22ZiA/w485-h233/codepin.PNG)


# Description
The notebook loads a wordlist of possible passwords and attempts to open an encrypted PDF file with each password. If the PDF opens successfully, the correct password has been found and is printed to the console. A progress bar shows cracking progress.

The key steps are:

Load wordlist of passwords into a list
Loop through passwords attempting to open PDF
Handle exception if incorrect password
Print and break loop if password found
Print message if no password found after exhausting wordlist
# Usage
To use this notebook:

Update the wordlist file path to point to your password wordlist
Update the PDF file path to the encrypted PDF you wish to crack
Run the notebook cell-by-cell
# Credits
This notebook uses the excellent pikepdf library for parsing PDFs. The progress bar is implemented with tqdm.

