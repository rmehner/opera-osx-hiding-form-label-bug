This is just a small repository to showcase a small Opera bug that I've found.

Preconditions:

* OSX 10.7.4 (don't know about 10.8, didn't have the time to upgrade yet)
* Opera 12 (Build number: 1467)

Visit http://rmehner.github.com/opera-osx-hiding-form-label-bug with that given browser.
There is a page that includes an iframe. That iframe includes an input field with a label.
This label and the text within the iframe is not shown in Opera, but in other browsers, including the Windows version of Opera.

As soon as you remove the border-radius CSS rule for iframe or reduce it to 2px it works again. Everthing higher than 2px hides the texts.
