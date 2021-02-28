# GNU and Shiny

Meta-package for [MacPorts](https://www.macports.org) that replaces BSD variants and outdated versions of CLI tools in MacOS.

## Usage

Clone this repository and install the ports with:
```bash
sudo port install
```

Most GNU utils are prefixed with the character 'g'.
If you want to use the GNU tools by default add `/opt/local/libexec/gnubin/` to the front of your PATH environment variable.
