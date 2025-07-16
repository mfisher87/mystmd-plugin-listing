# A MySTMD listing plugin

Inspired by [work by Chris Holdgraf](https://github.com/choldgraf/choldgraf.github.io/blob/35f2a24818ec73304a9769153796a952c0ec2561/src/blogpost.py)


## Similar projects

You should probably use
[Ryan Lovett's listing plugin](https://github.com/ryanlovett/myst-listing-plugin/)
instead :)


## Installation

### Plugin code

Copy this plugin into your repo and list it as an
[executable plugin](https://mystmd.org/guide/executable-plugins)
in your `myst.yml`:

```yaml
# ...
project:
  # ...
  plugins:
    - type: "executable"
      path: "plugin/listing.py"
# ...
```


### Dependencies

Install with `pip` or `conda` or equivalent (I :heart: [pixi](https://pixi.sh/)):

* pandas
* pyyaml
* feedgen


## Usage

In your MyST markdown:

```
:::{listing}
:::
```


## Configuration

TODO!
