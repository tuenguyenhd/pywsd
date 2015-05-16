pywsd.py
--------

Install ImageMagick for remove watermark. For OSX:
```
brew install imagemagick
```

For Ubuntu:

```
sudo apt-get install imagemagick
```


This is a utility script to create UML sequence diagrams using a plain-text
notation. That is, this program converts

	alice->bob: authentication request
	bob-->alice: response

to 

![example.png](https://raw.github.com/btbytes/pywsd/master/example.png)


## Typical Usage

Simplest:

	$ ./pywsd.py example.txt
	$ ls
	example.png


Something fancy:

	$ ./pywsd.py example.txt -s napkin
	$ ls
	example.png

The sequnce diagram should look like something you drew on a napkin.

Note: `./pywsd.py -h` for a list of available styles.

