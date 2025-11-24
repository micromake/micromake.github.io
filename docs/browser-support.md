---
icon: lucide/compass
tags:
  - Get started
  - Compatibility
---

# Browser support

Zensical tries to support the largest possible range of browsers while making it
easy to [customize the theme] using modern CSS features like [custom properties]
and [mask images].

  [customize the theme]: customization.md
  [custom properties]: https://caniuse.com/css-variables
  [mask images]: https://caniuse.com/mdn-css_properties_mask-image

## Supported browsers

The following table lists all browsers for which Zensical offers full support,
so it can be assumed that all features work without degradation. If you find
that something doesn't look right in a browser which is in the supported version
range, please [open an issue]:

<figure markdown>

| Browser                              | Version | Release date |         |        |      Usage |
| ------------------------------------ | ------: | -----------: | ------: | -----: | ---------: |
|                                      |         |              | desktop | mobile |    overall |
| :fontawesome-brands-chrome: Chrome   |     49+ |      03/2016 | 25.65%  | 38.33% |     63.98% |
| :fontawesome-brands-safari: Safari   |     10+ |      09/2016 |  4.63%  | 14.96% |     19.59% |
| :fontawesome-brands-edge: Edge       |     79+ |      01/2020 |  3.95%  |    n/a |      3.95% |
| :fontawesome-brands-firefox: Firefox |     53+ |      04/2017 |  3.40%  |   .30% |      3.70% |
| :fontawesome-brands-opera: Opera     |     36+ |      03/2016 |  1.44%  |   .01% |      1.45% |
|                                      |         |              |         |        | __92.67%__ |

  <figcaption markdown>

Browser support matrix sourced from [caniuse.com].[^1]

  </figcaption>
</figure>

  [^1]:
    The data was collected from [caniuse.com] in January 2022, and is primarily
    based on browser support for [custom properties], [mask images] and the
    [:is pseudo selector] which are not entirely polyfillable. Browsers with a
    cumulated market share of less than 1% were not considered, but might still
    be fully or partially supported.

Note that the usage data is based on global browser market share, so it could
in fact be entirely different for your target demographic. It's a good idea to
check the distribution of browser types and versions among your users.

  [open an issue]: https://github.com/zensical/zensical/issues/new/choose
  [caniuse.com]: https://caniuse.com/
  [:is pseudo selector]: https://caniuse.com/css-matches-pseudo
  [browser support]: #supported-browsers

