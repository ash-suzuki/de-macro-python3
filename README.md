# de-macro-python3
de-macro-python3.py converts tex files with private macros to files without macros.
de-macro-python3.py is a derivative of de-macro.py scripted by Peter Gacs (https://www.ctan.org/tex-archive/support/de-macro).
The original de-macro.py is licensed under the Academic Free Licence version 2.1.
This is why the original is attached.
de-macro-python3.py is licensed under MIT License.

# Example
python de-macro-python3.py example.tex

# Usage
Define your private macros in \<your-macro\>-private.sty, and de-macro-python3.py expands them.
Not only does it expand the private macros in \<your-macro\>-private.sty, de-macro-python3.py expands \<input-i\>.tex if the argument tex file contains input{\<input-i\>}.
Please read the comments on de-macro-python3.py for more detail usage.
