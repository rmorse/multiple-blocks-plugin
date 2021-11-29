# Multiple blocks plugin

This is an implementation of the fantastic `@wordpress/create-block` package, with some restructuring to support multiple blocks in a single WordPress plugin.

I strongly recommend to read the [official guide](https://developer.wordpress.org/block-editor/handbook/tutorials/create-block/), [the docs](https://developer.wordpress.org/block-editor/reference-guides/packages/packages-create-block/), and check out [the article](https://gziolo.pl/2020/12/22/how-to-start-block-development-with-scaffolding/) from it's creator Greg Ziółkowski.

## Follow the tutorial
This project was built to support the [tutorial found here](https://dev.to/rmorse/how-to-create-a-multiple-block-plugin-for-wordpress-mpm) - which uses the WordPress recommended way of creating a block plugin and teaches you how to add additional blocks should you need them.

If you prefer not to follow along, you can continue with the standard setup:

## Installation

1. Clone the project to your desired location
2. Open the command line in the project folder and install the packages:

    ```bash
    npm install
    ```
3. Grab a coffee

## Usage

Run the scripts for the included **buy-button** block
```shell
npm run start:buy-button
npm run build:buy-button
```

Run the scripts for the included **hero** block
```shell
npm run start:hero
npm run build:hero
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
Everyone is permitted to copy and distribute verbatim or modified copies of this license software, and changing it is allowed - for any purpose. No credit is needed whatsoever.

Your WordPress plugin should have a [GPL2 or Later](https://www.gnu.org/licenses/old-licenses/gpl-2.0.html) license, though.
