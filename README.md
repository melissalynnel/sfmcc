# sfmcc

Website and media assets for the San Francisco Muslim Community Center project.

## Contents

- `SALAAM V1.mp3`: converted audio asset for publishing and embedding
- `src/`: React source files for the site scaffold
- `app.html`: Vite app entry point
- `index.html`: root landing file

## Local development

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Google Sites audio embed

After the MP3 is published at a public URL, use this embed code:

```html
<audio controls preload="metadata" style="width: 100%; max-width: 480px;">
  <source src="https://your-public-file-url-here.mp3" type="audio/mpeg" />
  Your browser does not support the audio element.
</audio>
```
