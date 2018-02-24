# url2markdown

This is a very simple web service that will take a given URL, and return a Markdown representation of that page.

Powered by [Mercury Web Parser](https://mercury.postlight.com/web-parser/), [Requests](http://python-guide.org/), [html2text](http://www.aaronsw.com/2002/html2text/), and [Flask](http://flask.pocoo.org/).

## Usage


    $ curl http://url2md.herokuapp.com/?url=http://kennethreitz.org
    
    # Hi, there.
    
    My name is Kenneth Reitz.
    ...

Enjoy!

## Configuration

This application requires a [Mercury Web Parser API Token](https://mercury.postlight.com/web-parser/).

    $ export MERCURY_API_TOKEN=xxxxxx


## License

Unfortunately, this code is released under [GPLv3](http://www.gnu.org/copyleft/gpl.html).
