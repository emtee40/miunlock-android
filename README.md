# Instructions

To use this:

1)Install the latest version of Python (tick the "Add Python X.X to PATH" option if you are using Windows)
https://www.python.org/downloads/

2)After installing, open up Terminal (or Command Prompt) and enter:

```pip install requests
   pip install pycryptodome
   pip install pycryptodomex
   pip install adb
   ```
3)Run the program and do what program tells you to do

Windows:
  ```python main.py ```
  
Linux:
   ```./main.py ```

At the end you will get a hex string in some json (or an error in chinese), put this into a file with a hex editor, name it `token`

4)Download github.com/penn5/fastbrute

5)Run interpreter.py from fastbrute

6)Type:
```
=token
oem unlock
```
The device will factory reset and unlock successfully.

Credits:
@GiorgioUghini
@penn5
@notmarek
@pcfighter
@rien333
