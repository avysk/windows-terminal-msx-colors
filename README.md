# windows-terminal-msx-colors
[MSX](https://en.wikipedia.org/wiki/MSX)-like color scheme for
[Windows terminal.](https://github.com/microsoft/terminal)

## Installation

1. Run Windows terminal.
2. Hold Shift key and choose "Settings" in the menu. JSON file with Windows
   terminal settings will appear.
3. Paste content of `scheme.json` file into `schemes` key (notice it is an
   array):

```json
{
    ...,
    "schemes": [
        <Content of scheme.json>,
        ...
    ],
    ...
}
```

## Appearance

![Screenshot](screenshot.png)

## LICENSE

[BSD 2-clause](LICENSE)

## Acknowledgements

The values for colors come from
[this page](https://paulwratt.github.io/programmers-palettes/HW-MSX/HW-MSX-palettes.html).
