# Red Wavy Underline

This package changes the style of underline used by the [spell-check package][spell-check] to highlight spelling errors to the red, wavy underline. This package does *not* do any spell checking by itself.

![Screenshot](https://raw.githubusercontent.com/lee-dohm/red-wavy-underline/master/spelling-example.png)

## Using the RWU Style

You can also use the RWU for other purposes with the new mixin provided in the stylesheet. For example, you can add the RWU to all comments by adding the following to your `styles.less`:

```LESS
@import "packages/red-wavy-underline/stylesheets/red-wavy-underline";

.editor .comment {
  .red-wavy-underline;
}
```

![Mixin Example](https://raw.githubusercontent.com/lee-dohm/red-wavy-underline/master/mixin-example.png)

[spell-check]: https://atom.io/packages/spell-check
