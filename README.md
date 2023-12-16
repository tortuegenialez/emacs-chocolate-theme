# Chocolate theme [![MELPA](https://melpa.org/packages/chocolate-theme-badge.svg)](https://melpa.org/#/chocolate-theme)

![chocolate theme banner](assets/Chocolate_banner.png)
> Poor doggies can't experience it because of two reasons

---

Forking chocolate theme to overwrite colors

## Installation

### Install manually

Download [chocolate-theme.el](./chocolate-theme.el) and copy it into the  `~/.emacs.d/themes` directory.

Then add the following code to your `init.el` configuration:

``` emacs-lisp
(add-to-list 'custom-theme-load-path "~/.emacs.d/themes")
(load-theme 'chocolate t)
```

## Credits

`chocolate-theme` is based on a great palette from the [firewatch-hot-syntax](https://github.com/rricard/firewatch-hot-syntax "firewatch-hot-syntax") theme for Atom (which in its turn was inspired by [firewatch-syntax](https://github.com/SebastianSzturo/firewatch-syntax "firewatch-syntax")).

## License

[GPL-3.0](./LICENSE)
