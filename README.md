# Magento2 icon packs

Replace the default Magento2 Blank or Luma icons
with any other popular icon frameworks.

## How to use

Copy your icon pack of choice to your theme in the `web/fonts`.

And change/add the following variables to load your new icons instead.

```less
@icons__font-path: "@{baseDir}fonts/M2-Luma-Material/M2-Luma-Material";
@icons__font-name: "M2-Luma-Material";
```

_Example of M2-Luma-Material import_

Also [see the wiki](https://github.com/GrimLink/magento2-icon-packs/wiki) for;
- How to use the extra 3 icons (bag, sort up and sort down)
- How to replace it with your own icon pack.

## Icon packs

The following icon packs are available in this repo

- The default Magento 2 icons
- [Material Icons](https://github.com/google/material-design-icons)
- [Bootstrap 5 Icons](https://github.com/twbs/icons)

The following icon packs are planned to be added

- [FontAwesome 5](https://github.com/FortAwesome/Font-Awesome)
- [Feather Icons](https://github.com/feathericons/feather)
