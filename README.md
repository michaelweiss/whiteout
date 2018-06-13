Whiteout provides tools to clean up text documents.

## Prerequisites

Whiteout requires [Flask](http://flask.pocoo.org) and [TextTeaser](https://github.com/IndigoResearch/textteaser).

## Use

To start whiteout, set it as application to use in the `FLASK_APP` environment variable and start Flask. The command below tells Flask to reload the application whenever you make changes to the code and to accept requests from any hosts. To run this in production you should tweak this.

```sh
> export FLASK_APP=whiteout.py
> flask run --reload --host 0.0.0.0
```

To run the client open a browser at http://localhost:5000/whiteout.

## License

This code is released under an MIT License.
