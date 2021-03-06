# osx(1)

The average life cycle of a computer for me is about 3 years; which means every time I have to set up a new one, I spend hours, if not days, trying to get it perfect. From installing the latest software for all of my various use cases to getting all of my personal settings and preferences, it becomes a very tedious operation.  It got me thinking to myself,

> How can I automate this process?

Inspired by a [few peoples](#acknowledgements) `.dotfiles` scripts, I decided to create this library for installing and setting up my OS X machines.

**Why a separate repository?**

I didn't like the connection between setting up your development machine, or `.dotfiles` and setting up your computer with various software and settings.  It appeared to me to be better served from a separate repository so that I could run both my dotfiles install and osx scripts concurrently if needed; or even better I didn't have to install my dotfiles on a machine that needed some synchronized OS X settings.

## How to install

osx(1) is a [shell script][bin], so installation is simple.  [Download][download], extract and copy the script in the `bin` directory over to the `/usr/local/bin` directory and make sure it's in your `$PATH`.

## One-line installation

```bash
$ bash -c "$(curl -#fL raw.github.com/iamnewton/osx/go/install)"
```

N.B. - using the one-line installation will download and install all of the dependencies.

## Usage

```bash
$ osx
```

## Contributing

Suggestions and contributions are always welcome.  If you'd like to see a new profile, you can get involved by either [creating an issue](https://github.com/iamnewton/osx/issues/new), or [forking the code](https://github.com/iamnewton/osx/fork) and [creating a pull request](https://github.com/iamnewton/osx/compare/). For more information on how to work with the code, please see the [CONTRIBUTING.md](https://github.com/iamnewton/osx/blob/master/CONTRIBUTING.md) documentation.

## Acknowledgements

Inspiration and code was taken from many sources, including:

* [@sindresorhus](https://github.com/sindresorhus) (Sindre Sorhus) https://github.com/sindresorhus/quick-look-plugins
* [@necolas](https://github.com/necolas) (Nicolas Gallagher) https://github.com/necolas/dotfiles
* [@mathiasbynens](https://github.com/mathiasbynens) (Mathias Bynens) http://mths.be/osx

[bin]: https://github.com/iamnewton/clone-all/blob/master/clone-all
[download]: https://github.com/iamnewton/clone-all/archive/master.zip
