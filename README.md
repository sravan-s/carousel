# carousel

> A custom carousel in the style of webcomponents.


## Install

The Bower way
    ```sh
        $ bower install webcomponent-custom-carousel --save
    ```
    OR

[download as ZIP](https://github.com/sravan-s/carousel/archive/master.zip).

## Usage

1. Import polyfill(if necessary):

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents.min.js"></script>
    ```

2. Import custom element:

    ```html
    <link rel="import" href="bower_components/webcomponent-custom-carousel/custom-carousel.html">
    ```

3. Start using it!

    ```html
    <custom-carousel>
        <img src="img1">
        <img src="img2">
        ...
        <img src="imgn">
    </custom-carousel>
    ```

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

3. Start development server and open `http://localhost:8080/components/my-repo/`.

    ```sh
    $ polyserve
    ```

## History

For detailed changelog, check [Releases](https://github.com/sravan-s/carousel/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)
