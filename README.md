# Red Wavy Underline [![Dependency Status](https://david-dm.org/lee-dohm/red-wavy-underline.svg)](https://david-dm.org/lee-dohm/red-wavy-underline)

This package changes the style of underline used by the [spell-check package][spell-check] to highlight spelling errors to the red, wavy underline. This package does *not* do any spell checking by itself.

![Screenshot](https://raw.githubusercontent.com/lee-dohm/red-wavy-underline/master/spelling-example.png)

## Using the RWU Style

You can also use the RWU for other purposes with the mixin provided in the stylesheet. For example, you can add the RWU to all comments by adding the following to your `styles.less`:

```less
@import "packages/red-wavy-underline/styles/red-wavy-underline";

atom-text-editor::shadow .comment {
  .red-wavy-underline;
}
```

![Mixin Example](https://raw.githubusercontent.com/lee-dohm/red-wavy-underline/master/mixin-example.png)

## Copyright

Copyright &copy; 2014-2015 by [Lee Dohm](http://www.lee-dohm.com) and [Lifted Studios](http://www.liftedstudios.com). See [LICENSE] for details.

[LICENSE]: https://github.com/lee-dohm/red-wavy-underline/blob/master/LICENSE.md
[spell-check]: https://atom.io/packages/spell-check
