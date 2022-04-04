## Getting Started

```sh
git clone git@github.com:SimonSiefke/nextjs-title-issue.git &&
cd nextjs-title-issue &&
npm ci &&
npm run build &&
npm i -g http-server &&
http-server dist
```

## Output with React 18

```html
<title>| abc<!-- --></title>
```

## Output with React 17

```html
<title>| abc</title>
```
