# getpdftitle
getpdftitle extracts the title from pdf files. The extracted title is redirected to stdout.  
When an explicit file name is not specified, the title from all pdf documents in the current directory is extracted and output as a list.
For pdf files that do not contain title in metadata, the pdf is converted to txt file and the first non-empty line is extracted.

## Usage
getpdftitle [-h] [-n] [-s] [filename [filename ...]]  

_positional arguments_:
  filename    Extracts title from file.pdf. Extracts from all pdf files in the  
              current directory if a filename is not specified

_optional arguments_:  
  -h, --help  show this help message and exit  
  -n, --name  Include filename in output  
  -s, --stat  Show statistics of files parsed  

## Requirements
sudo pip install pdfrw  
sudo pip install argparse

## Author
[Cibin Joseph](https://github.com/cibinjoseph) (cibinjoseph92@gmail.com).

## License
MIT License
See [LICENSE](LICENSE) for full text.
