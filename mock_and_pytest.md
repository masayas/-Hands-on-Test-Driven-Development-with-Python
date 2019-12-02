unittest.mock
===============
* Importatnt thing to remember

  * if we want mock to have "magic" methods pre-made, use the MagicMock class 
  * autospeccing can be useful if we want any mock object to act as the same as the original object being mocked
  * if we want the mock not to add any more attributes or functions, it's a good idea to seal by using seal function
   
* unittest.mock introduction. very well written document:

  * https://docs.python.org/3/library/unittest.mock.html#module-unittest.mock

* examples by the official document:

  * https://docs.python.org/3/library/unittest.mock-examples.html

* Good examples of using mock 

  * https://medium.com/@yeraydiazdiaz/what-the-mock-cheatsheet-mocking-in-python-6a71db997832

https://stackoverflow.com/questions/11501520/importerror-no-module-named-mock


https://myadventuresincoding.wordpress.com/2011/02/26/python-python-mock-cheat-sheet/


* This is a very specific resolution of how to mock a name attribute of an object. This happens if your obejct uses "name" attribute and when using the mock, mock also has the name attribute.

  * https://blog.tunarob.com/2017/04/27/mock-name-attribute/

日本語
---------

* good examples of using assert_called:

  * https://thinkami.hatenablog.com/entry/2017/03/18/063454

* good examples

  * https://note.crohaco.net/2015/python-mock/


* https://codeday.me/jp/qa/20190101/94801.html

* https://dev.classmethod.jp/server-side/python/pytest-getting-started/


multimedia
-----------
* [Understanding Unittest.Mock](https://learning.oreilly.com/videos/understanding-unittest-mock/9781484244135/)

pytest
===========

日本語
---------
* くろのて

  * https://note.crohaco.net/2016/python-pytest/


* よくまとまっている

  * https://www.m3tech.blog/entry/pytest-summary

  * https://www.magata.net/memo/index.php?pytest%C6%FE%CC%E7

  * https://qiita.com/_akiyama_/items/9ead227227d669b0564e

  * https://qiita.com/sasaki77/items/97c90ae272373d78b422


Multimedia
---------------
* [Python Testing with pytest](https://learning.oreilly.com/library/view/python-testing-with/9781680502848/)

* [Hands-On Test Driven Development with Python](https://learning.oreilly.com/videos/-/9781789138313/)

* 

Miscellaneous
=================
* To mock API of AWS boto3, this moto package seems extremely useful: 

  * https://github.com/spulec/moto

* Some people think pytest-mock is a good wrapper of mock package. so worth taking a look

  * https://github.com/pytest-dev/pytest-mock/
