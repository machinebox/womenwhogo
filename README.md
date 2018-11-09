# Women Who Go London

## Using Machine Learning with Go

We will show you how to take advantage of Machine Learning capabilities to power up your own apps.
Learn about the kinds of problems Machine Learning is good at, and what it cannot do.
We will explore the core concepts around this mysterious technology, and build a real solution from scratch.

## Slides

https://docs.google.com/presentation/d/1Hke2c67_q8KHQqByjX3Wdt6I8sTIl1GhpGcpVo9ZtRI/edit?usp=sharing


## Give Feedback

https://goo.gl/forms/F21XQDR3jxZofIKA3


# Requirements

## Go and some dependencies

Go and you can use `dep` to get the dependencies, or manually `go get` everything.

You can install `wget` with Brew:

```
brew install wget
```

## Dataset

News20 http://www.cs.cmu.edu/afs/cs.cmu.edu/project/theo-20/www/data/news20.tar.gz

To get it you can:

`$ make dataset`


## Word embeddings

http://nlp.stanford.edu/data/glove.6B.zip

Only the 100 dim

To get it:

`$ make wordemb` 


# Some Python2/Tensorflow dependencies

`$ make install`

## Install Tensorflow Go CGO bindings

https://www.tensorflow.org/install/install_go






