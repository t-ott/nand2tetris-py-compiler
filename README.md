# Jack Analyzer (nand2tetris)

### Usage
```
jack_analyzer.py [-h] [-j JACK_FILES] [-c COMPARE_FILES] [-t]

optional arguments:
  -h, --help            show this help message and exit
  -j JACK_FILES, --jack_files JACK_FILES
                        Jack file (with .jack extension) or directory containing Jack files
  -c COMPARE_FILES, --compare_files COMPARE_FILES
                        Existing .xml file or directory of .xml files to compare analyzer output to
  -t, --testall         Test the Jack analyzer on the seven provided .jack files
```

### Example
Analyze all Jack files in the ```Square``` directory and compare them to the provided ```.xml``` files.
```
jack_analyzer.py -j Square -c Square
```