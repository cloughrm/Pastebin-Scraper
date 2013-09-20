Pastebin-Scraper
================

Monitors pastebin.com for a specified set of keywords.

Usage
=====

Copy pastebin.py to the location of your choice. Make a file called 'keywords.txt' in the same directory. When a pate contains a word from the keyword.txt file, the paste will be saved in a 'Pastebin' folder within date sorted folders.
- pastebin.py
- keywords.txt
- Pastebin
	- Year
		- Month
			- Day
				- date_pasteID_matchedKeywords.txt
				- date_pasteID_matchedKeywords.txt
				- date_pasteID_matchedKeywords.txt

Dependencies
============

pastebin.py was developed to run on Windows 7. The script requires TOR is installed (https://www.torproject.org/download/download). The following python modules are required:
- Socks (http://socksipy.sourceforge.net/)
- SocksiPyHandler (https://github.com/Anorov/PySocks)
