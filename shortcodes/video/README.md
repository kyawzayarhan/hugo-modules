# Custom Video Shortcode

## Install Module

Add the following code to your module list in the `config/_default/module.toml` file.

```toml
[[imports]]
path = "github.com/kyawzayarhan/hugo-modules/shortcodes/video"
```

<hr>

## Shortcode Implementation

```md
<!-- minimal use -->
{{< video src="https://www.w3schools.com/html/mov_bbb.mp4" >}}

<!-- extended use -->
{{< video src="https://www.w3schools.com/html/mov_bbb.mp4" width="500" height="auto" autoplay="false" loop="false" muted="false" controls="true" class="" >}}
```