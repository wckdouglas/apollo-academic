# apollo-academic

Modern and minimalistic blog theme powered by [Zola](getzola.org). See a live preview [here](https://wckdouglas.netlify.app/).

<sub><sup>Named after the greek god of knowledge, wisdom and intellect</sup></sub>

<details open>
  <summary>Dark theme</summary>
  
  ![blog-dark](https://user-images.githubusercontent.com/26800596/168986771-4ed049e2-e123-4d0e-8a24-7bf43f47551f.png)
</details>

<details>
  <summary>Light theme</summary>
  
![blog-light](https://user-images.githubusercontent.com/26800596/168986766-72a48517-7122-465d-8108-3ae33e1e88b1.png)
</details>

## Features

- [X] Pagination
- [X] Themes (light, dark, auto)
- [X] Analytics using [GoatCounter](https://www.goatcounter.com/)
- [x] Social Links
- [ ] Search
- [ ] Categories

## Installation

1. Download the theme
```
git submodule add https://github.com/wckdouglas/apollo-academic themes/apollo-academic
```

2. Add `theme = "apollo-academic"` to your `config.toml`
3. Copy the example content

```
cp themes/apollo/content content
cp themes/apollo/data data
```

## Options

### Additional stylesheets

You can add stylesheets to override the theme:

```toml
[extra]
stylesheets = [
    "override.css",
    "something_else.css"
]
```

These filenames are relative to the root of the site. In this example, the two CSS files would be in the `static` folder.

## References

This theme is based on [apollo](https://github.com/not-matthias/apollo).  
