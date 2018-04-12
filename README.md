# rebound

Rebound lets you instantly browse Stack Overflow results in your terminal when you get a compiler error. Just use the `rebound` command before the file you want to execute.

![Placeholder Demo](demo.gif)

## Installation

Rebound works on MacOS, Linux, and Windows, with binary downloads available for [every release.](https://github.com/shobrook/rebound/releases) You can also install it with pip:

`$ pip install rebound-cli`

Requires Python 3.0 or higher.

## Usage

Running a file with `rebound` is just as easy as compiling it normally:

`$ rebound [file_path]`

This will execute the file, pull the error message, and let you browse related Stack Overflow questions and answers without leaving the terminal.

__Supported file types:__ Python and Node.js (Ruby and Java coming soon!).

## Contributing

To make a contribution, fork the repo, make your changes and then submit a pull request. If you've discovered a bug or have a feature request, create an [issue](https://github.com/shobrook/rebound/issues/new) and tag it appropriately :)

## Technologies

Rebound is written in Python and built on Urwid. Beautiful Soup is used to scrape Stack Overflow content and subprocess for catching compiler errors.

## Acknowledgements

Special thanks to [@rndusr](https://github.com/rndusr) for helping with the scrollbar.
