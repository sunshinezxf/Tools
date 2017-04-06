# Tools
Develop some micro tools to help improve work efficiency

## Fannsplitfile
* Tis tool aims to help those who are fighting with opening large log files. It could help help you slice your large log file into pieces. And you may find it easier to have the log part file opened.

### Aguments
* This tool receives two parameter:
1. Target file path. By entering the file path, this tool would load the target file and do some job later.
2. Number of lines in each part file. This parameter is optional. The tool has a default value 500000 by default. 

### Usage
* This tool is written in Java, packaged as a jar. In order to run the jar, you need to install Java 8.
* java -jar xxx.jar or java -jar filepath [um-per-part]
