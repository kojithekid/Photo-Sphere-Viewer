# Fisheye

Display the panorama with a fisheye effect.

::: code-demo

```yaml
autoload: true
title: PSV Fisheye Demo
```

```js
const baseUrl = 'https://photo-sphere-viewer-data.netlify.app/assets/';

new PhotoSphereViewer.Viewer({
    container: 'viewer',
    panorama: baseUrl + 'sphere.jpg',
    caption: 'Parc national du Mercantour <b>&copy; Damien Sorel</b>',
    defaultPitch: 0.6,
    defaultZoomLvl: 20,
    fisheye: true,
});
```

:::
