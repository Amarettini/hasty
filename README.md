***Hasty***
[![Actions Status](https://xxx.execute-api.us-west-2.amazonaws.com/production/badge/{owner}/{repo})](https://xxx.execute-api.us-west-2.amazonaws.com/production/results/{Vikdemen}/{hasty})

A CLI client for hastebin-based text sharing websites.

Installation: pip install git+https://github.com/Vikdemen/hasty

Usage:\
hasty [-h] [-c | -f FILE] [-p]\
Grabs data from stdin (press Ctrl-D when you finish writing) and loads it on hastebin.com, returning the link\
-h, --help
-c: --copy - Uses contents of a clipboard as input\
-f: --file - Uses contents of a text file as input\
-p: --paste - Pastes the link in a clipboard instead of printing
