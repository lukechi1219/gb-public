# Material Multi Theme

.

**Swapping CSS files**

If you want to completely swap a theme without including all the styles at once, you can swap the loaded theme file. The details will depend on your application, but the general idea looks like this:

```text
<link id="themeAsset" rel="stylesheet" href="/path/to/my/theme-name.css">
```

```text
function changeTheme(themeName) {
  document.getElementById('themeAsset').href = `/path/to/my/${themeName}.css`;
}
```

[https://material.angular.io/guide/theming\#multiple-themes](https://material.angular.io/guide/theming#multiple-themes)

[https://material.angular.io/guide/theming-your-components](https://material.angular.io/guide/theming-your-components)

.

