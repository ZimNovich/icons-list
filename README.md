### Open Source Icon Sets

Semantic UI uses `Font Awesome 5.0.8` icon set, that contains 1,608 icons. There is also `Font Awesome 6.7.2` that contains 2,060 icons (1,565 classic + 495 brand icons), and `Font Awesome 7.1.0` that contains 2,089 icons (1,576 classic + 513 brand icons).

There are also:
- https://fontawesome.com (2,089 icons)
- https://github.com/FortAwesome/Font-Awesome
- https://icons.getbootstrap.com (2,000+ icons)
- https://fonts.google.com/icons
- https://github.com/Templarian/MaterialDesign (7,000+ icons)
- https://github.com/google/material-design-icons
- https://tabler.io/icons (4,985 icons)
- https://remixicon.com (3,188 icons)
- https://phosphoricons.com (9,072 icons)
- https://lucide.dev (1,667 icons)
- https://heroicons.com (316 icons)
- https://feathericons.com (287 icons)
- https://hugeicons.com (4,600+ icons)
- https://www.mingcute.com (3,324 icons)
- https://www.humbleicons.com (284 icons)
- https://lineicons.com (2,036 free icons)
- https://ionic.io/ionicons
- https://griddyicons.com
- https://iconmonstr.com
- https://icons8.com/line-awesome
- https://www.basicons.com (636 icons)
- https://circumicons.com/icons (285 icons)
- https://primer.style/octicons/ (icons by GitHub)

Search icon sets:
- https://icon-sets.iconify.design

Boxicons CDN:
```
<link rel="stylesheet" href="https://cdn.boxicons.com/3.0.7/fonts/basic/boxicons.min.css" />
<link rel="stylesheet" href="https://cdn.boxicons.com/3.0.7/fonts/brands/boxicons-brands.min.css" />
```

Remix Icons CDN:
```
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/remixicon@4.8.0/fonts/remixicon.css" />
```

Font Awesome CDN:
```

<script src="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@7.1.0/js/all.min.js"></script>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@7.1.0/css/fontawesome.min.css" />
```

### Boxicons

My preference is [Boxicons](https://boxicons.com) — an open source set of 3768 icons. They have a `npm package` which can be used like this:
```html
<head>
  <link rel="stylesheet" href="boxicons.min.css">
</head>
```

Boxicons are used by adding the `bx` class and an additional icon name class: using the `bx-` prefix for regular icons, `bxs-` for solid icons, and `bxl-` for logo icons:
```html
<i class="bx bx-hot" />
<i class="bx bxs-hot" />
<i class="bx bxl-facebook-square" />
```
Here is a full list of icons: https://boxicons.com/icons?s=rounded&w=thin

### SVG icons

We could even switch to inline SVG icons, as many developers currently do for online banking applications.

```html
<button type="button" class="button with-icon">
	<svg class="icon icon--larger" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" width="1em" height="1em">
		<path d="M493.4 24.6l-104-24c-11.3-2.6-22.9 3.3-27.5 13.9l-48 112c-4.2 9.8-1.4 21.3 6.9 28l60.6 49.6c-36 76.7-98.9 140.5-177.2 177.2l-49.6-60.6c-6.8-8.3-18.2-11.1-28-6.9l-112 48C3.9 366.5-2 378.1.6 389.4l24 104C27.1 504.2 36.7 512 48 512c256.1 0 464-207.5 464-464 0-11.2-7.7-20.9-18.6-23.4z" />
	</svg> Phone
</button>
```
