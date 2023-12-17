# Display issue fix for Shapes theme

For more information about this fix, [see our help guide](https://help.switchthemes.co/updates/chrome-display-issue.html).

These are files required to manually fix the high pixel density display issue in Shapes theme.

### Steps to fix:

1. Replace the following files in your theme with the files included in this repository:
  - assets/block-sticker.css
  - sections/call-to-action.liquid
  - snippets/block-sticker.liquid
  - snippets/media-image-placeholder.liquid
  - snippets/media-video.liquid
  - snippets/product-tile-media-image.liquid
  - snippets/static-sticker.liquid

2. Copy the css from `additional-styles.css` and add it to the bottom of `base.bundle.css` or `custom.css`

