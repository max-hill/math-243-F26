# Parametric Curve Ant

A self-contained teaching app for plotting a parametric curve and watching an ant trace it over the parameter interval.

## Add it to the Math 243 GitHub Pages site

1. Copy this `parametric-ant` folder into the course repository at `assets/parametric-ant`.
2. Add the following HTML wherever the app should appear in a Markdown or HTML page:

```html
<iframe
  src="{{ '/assets/parametric-ant/index.html' | relative_url }}"
  title="Parametric curve ant tracer"
  style="width: 100%; height: 850px; border: 0;"
  loading="lazy">
</iframe>
```

If the page is plain HTML rather than Jekyll, use `src="/math-243-F26/assets/parametric-ant/index.html"` instead.

The app has no dependencies: all HTML, CSS, and JavaScript are contained in `index.html`.
