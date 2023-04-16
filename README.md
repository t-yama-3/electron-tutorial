electron-tutorial

```
git remote add origin https://github.com/t-yama-3/electron-tutorial.git
git branch -M main
git push -u origin main
```

```
npm init
npm install electron --save-dev
```

## 起動

package.json

```
  "scripts": {
    "start": "electron .",
  },
```

```
npm run start
```

## 配布

```
npm install --save-dev @electron-forge/cli
npx electron-forge import
```
