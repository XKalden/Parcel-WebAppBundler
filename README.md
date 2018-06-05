# Parcel 
https://github.com/parcel-bundler/parcel

```bash
    npm i --save-dev parcel-bundler babel-preset-env babel-preset-react

```

## .bablirc (file)
```bash
{
    "presets": ["env", "react"]
}
```

package.json =>
"scripts": {
    "start": "parcel index.html"
  },