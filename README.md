# glycopeptide-lokidb

> Element providing in-memory client side lokijs data store.

## Usage

1. Import polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>
    ```

2. Import custom element:

    ```html
    <link rel="import" href="bower_components/glycopeptide-lokidb/glycopeptide-lokidb.html">
    ```

3. Start using it!

    ```html
    <glycopeptide-lokidb></glycopeptide-lokidb>
    ```

## Options

Attribute      | Options     | Default      | Description
---            | ---         | ---          | ---
`datasetID`    | *string*    | ``           | unique dataset identifier

## Methods

Method                       | Parameters   | Returns     | Description
---                          | ---          | ---         | ---
`generate()`                 | None.        | Nothing.    | Parses lists of peptides and glycans calls combinePeptidesAndGlycans()

## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

1. Install [bower](http://bower.io/) & [polyserve](https://npmjs.com/polyserve):

    ```sh
    $ npm install -g bower polyserve
    ```

2. Install local dependencies:

    ```sh
    $ bower install
    ```

3. Start development server and open `http://localhost:8080/components/glycopeptide-lokidb/`.

    ```sh
    $ polyserve
    ```

## History

For detailed changelog, check [Releases](https://bitbucket.org/sib-pig/glycopeptide-lokidb/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)
