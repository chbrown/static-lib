## _static-lib_ (Deprecated)

My **client-side javascript libraries** have been moved to [misc-js](https://github.com/chbrown/misc-js).

    git clone https://github.com/chbrown/misc-js


My **static client-side file management** has been moved to [birdy](https://github.com/chbrown/birdy).

    npm install -g birdy

For example, at your command line:

    birdy --pattern 'static/{file}' install jquery underscore \
      misc-js==git://github.com/chbrown/misc-js.git
