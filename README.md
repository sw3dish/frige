# frige

frige is a collection of Javascript-free UI components.

## Getting Started

To use `frige` in a project, simply copy the HTML from the `.html` file and include the relevant `.css` file in the relevant directory under `dist/components`.
However, you probably don't need this package unless you plan to modify the components in `frige`.

### Prerequisites

- To use `frige` in a project
  - None!
- To use tooling to add to `frige`
  - Node (current)

### Installing

- To use `frige` in a project
  - copy the HTML from the `.html` file in the relevant directory under `dist/components`
  - include the relevant `.css` file in the relevant directory under `dist/components`

- To modify the components in `frige`
  - Run `npm watch` to watch your `.html` and `.scss` files. It will run the `lint` and `build` tasks
  - Run `npm build` to compile `.scss` to `.css`. Your built files will be available in `dist`
  - Run `npm lint` to lint `.scss` files with `stylelint` and lint `.html` files with `htmlhint`

## Running the tests


## Built With

* [stylelint](https://github.com/stylelint/stylelint) - CSS/SCSS linter
* [htmlhint](https://github.com/htmlhint/HTMLHint/) - HTML linter
* [node-sass](https://github.com/sass/node-sass) - SCSS -> CSS compiler

## Authors

* **Colin Burr** - *Initial work* - [sw3dish](https://github.com/sw3dish)

## License

This project is licensed under the GNU GPLv3 License - see the [LICENSE](LICENSE) file for details

## Acknowledgments

* Matt Reyer for writing [about a JavaScript-free front-end](https://dev.to/winduptoy/a-javascript-free-frontend-2d3e)
