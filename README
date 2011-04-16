This repository holds a set of questions for Trivia and Qukkiz.

## STRUCTURE ##

In the root directory are the different languages (like english/german). To add a language simply create a directory (e.g. french). The language defines the language of the question. So if the question is “What does BMW” (http://en.wikipedia.org/wiki/BMW) mean the answers could be “Bayerische Motoren Werke” (german) and “Bavarian Motors Works” (english), but the question should be saved in the english section. 

Within each directory there are following types of filetypes:

1. trivia
2. qukkiz
3. both

Trivia files are usable with triva and qukkiz files are usable with qukkiz. If a question could be used in both, add it into the “both” file.

## USAGE ##

### General ###
Simply copy all wanted files into a directory which Trivia/Qukkiz reads. The disadvantage is, that you have to make updates on your self.

### Qukkiz ###
With qukkiz you have one additional method. To do so, define the files in the qukkiz.yml settings in the file. To add a complete language simply select the directory.

For example to use the english “main.qukkiz” and all german questions:

    questions:
      files:
        - '<repository>/english/main.qukkiz'
        - '<repository>/german/'

Replace “<repository>” with the path to this repository.

### Trivia ###
With Trivia you could only use the General variant.
