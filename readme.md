# The Multilingual Hatemail Corpus

## Purpose

This corpus has been formed as a go-to repository for researchers and hobbyists interested in hatemail.


## Submission Guidelines

Anyone can submit.

Currently the submission format is JSON, 1 string per entry:

```json

{ "entries" : [
	{
		"text" : "HATEMAIL IN HEBREW AND ENGLISH GOES HERE",
		"languages" : ["heb", "eng"]
	},
	{
		"text" : "MORE HATEMAIL IN ESTONIAN GOES HERE",
		"languages" : ["est"]
	}
]}

```

Tag the language with the [ISO 639-2 Language Code](http://www.loc.gov/standards/iso639-2/php/code_list.php).

Submit into a folder by username (or Anonymous, if you prefer). Data may be processed and reorganized later.

Please do not submit sender information.
