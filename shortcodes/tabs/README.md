# Tab Shortcode

## Installation for Gethugothemes themes

Add the following code to your module list in the `config/_default/module.toml` file.

```toml
[[imports]]
path = "github.com/kyawzayarhan/hugo-modules/shortcodes/tabs"
```

Add the following code to your `asstes/scss/style.scss` file.

```scss
@import 'tabs';
```

<hr>

## Shortcode Implementation

```md
{{< tabs "demo-tab" >}}

{{< tab "first" >}}
First Tab
{{< /tab >}}

{{< tab "second" >}}
Second Tab
{{< /tab >}}

{{< tab "third" >}}
Third Tab
{{< /tab >}}

{{< /tabs >}}
```