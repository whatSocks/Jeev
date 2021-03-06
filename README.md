# Jeev

Jeev is a python alternative to Github's famous Hubot, using Python+Gevent instead of Node+CoffeeScript. 

# Motivation

I got tired of Hubot's callback spaghetti, and decided to write an alternative to work with my company's slack channel.
This project is a work in progress, and is roughly documented. 

# Getting Started

Just set up a python virtual environment, run `pip install -r requirements.txt`, `cp config.sample.py config.py`
and then run `python main.py` and you're up and running. The default adapter will listen for messages in STDIN, and 
print the bot's replies to STDOUT.

# License

The MIT License (MIT)

Copyright (c) 2014 Jacob Heinz

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.