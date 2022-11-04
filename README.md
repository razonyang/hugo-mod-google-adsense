# Hugo Google Adsense Module

## Installation

### Configuration

Append the following configuration into `config.toml`.

```toml
[[module.imports]]
path = "github.com/razonyang/hugo-mod-google-adsense"

[params.googleAdsense]
client = "ca-pub-CLIENT-ID"
```

### Partials

> You can skip this step if your theme support [HugoPress](https://github.com/razonyang/hugopress).

Include the following partial inside `<head>` tag.

```html
{{- partialCached "hugopress/modules/google-adsense/script" . }}
```
