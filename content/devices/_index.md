---
build:
  list: never
  publishResources: false
  render: never
title: Headless page devices
---

{{ range .Pages.ByTitle }}
  <h2><a href="{{ .RelPermalink }}">{{ .Title }}</a></h2>
{{ end }}