# Red Wavy Underline

Places a red wavy underline (RWU) under misspelled words instead of the default dashed underline.

![Screenshot](https://raw.githubusercontent.com/lee-dohm/red-wavy-underline/master/spelling-example.png)

## Using the RWU Style

You can also use the RWU for other purposes with the new mixin provided in the stylesheet. For example, you can add the RWU to all comments by adding the following to your `styles.less`:

```less
@import "packages/red-wavy-underline/stylesheets/red-wavy-underline";

.editor .comment {
  .red-wavy-underline;
}
```

![Mixin Example](https://raw.githubusercontent.com/lee-dohm/red-wavy-underline/master/mixin-example.png)
