# jQuery UI - ESM fork

This is a simple fork of jQuery UI, which has converted the
AMD modules to ESM modules. This means that jQuery UI can be used
with modern builders like Vite, Snowpack and Esbuild.

## Installation

```
npm install @eirslett/jquery-ui-esm
```

And in the app:

```
import 'jquery-ui';
```

Or individual modules:

```
import 'jquery-ui/esm/widgets/dialog.js';
```


