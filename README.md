# MergeTools widgets

Small embeddable pages for the MergeTools store pages (Superhive, Gumroad).

`compare.html` is a drag-to-compare slider:

```
https://paulthien97-ai.github.io/mergetools-widgets/compare.html?a=img/cylinder-1.0.6.jpg&b=img/cylinder-1.0.18.jpg&la=MergeTools+1.0.6&lb=MergeTools+1.0.18
```

- `a`, `b`: before and after images (from this site or from assets.superhivemarket.com only)
- `la`, `lb`: their labels
- `s`: where the line starts, 0-100 (default 50)

Embed it with an iframe, for example `<iframe src="...compare.html?..." width="100%" height="420" frameborder="0"></iframe>`.

The pictures in `img/` are viewport captures of the same scene (a ball merged into Blender's default
cylinder or cone) on MergeTools 1.0.6 and 1.0.18.
