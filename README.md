# Red Wavy Underline

Places a red wavy underline under misspelled words instead of the default dashed underline.

![Screenshot](https://raw.githubusercontent.com/lee-dohm/red-wavy-underline/master/screenshot.png)

## Red Wavy Underline Mixin

In addition, you can use the red wavy underline for your own purposes as a mixin with the following code in your `styles.less`. For example, if you wanted to mark all comments with the RWU:

```less
@import "packages/red-wavy-underline/stylesheets/red-wavy-underline"

.editor .comment {
  .red-wavy-underline;
}
```
