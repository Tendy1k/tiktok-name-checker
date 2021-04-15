# tiktok-name-checker
This tool verifies tiktok usernames. It's useful for sniping rare names. 

The python file and the executable are only usable in command prompt.
Use the executable file to avoid installing python/dependencies.

- Usage: python check.py <method> <name/lettercount> *, <optional args>
- Example: python check.py --checkOne .dechart
- Example: python check.py --checkMultiple 4 --generationType alphabetical/random

Python requirements:
  - Requests - ``pip install requests``
  - BeautifulSoup4 - ``pip install bs4``
  - Colorama - ``pip install colorama``

Optional args:
   - --ignore-invalid - ignores invalid names
   - --save-to-file - save all valid names to a .txt file
   - --random-header - random headers, reduces the chance of getting rate limited
