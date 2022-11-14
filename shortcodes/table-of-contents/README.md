# Table Of Contents Shortcode

## Install Module

Add the following code to your module list in the `config/_default/module.toml` file.

```toml
[[imports]]
path = "github.com/kyawzayarhan/hugo-modules/shortcodes/table-of-contents"
```

Add the following code to your `asstes/scss/style.scss` file.

```scss
@import 'toc';
```

<hr>

## Shortcode Implementation

```md
{{< toc >}}
```

<hr>

## Customize Shortcode

```toml
[markup.tableOfContents]
startLevel = 2
endLevel = 5
ordered = true
```