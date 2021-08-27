x

## Requisitos:

- NodeJs v14

## Como rodar:

- `npm install`
- `npm start`

## Como analisar o bundle:

- `npm run build:analize`
- `npm run build -- --stats && npx webpack-bundle-analyzer build/bundle-stats.json -m static -r build/bundle-stats.html -O`

## Referência:

- [Template](https://github.com/flatlogic/react-material-admin)
- [React: Code Splitting](https://reactjs.org/docs/code-splitting.html)
- [Webpack: Bundle Analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer)
- [Webpack: Bundle Analyzer + Create React App](https://github.com/facebook/create-react-app/issues/3518#issuecomment-454144586)
- [Webpack: Magic Comments](https://webpack.js.org/api/module-methods/#magic-comments)
- [Webpack: Preloading/Prefetching](https://webpack.js.org/guides/code-splitting/#prefetchingpreloading-modules)
- [Artigo: JavaScript Start-up Optimization](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/javascript-startup-optimization)
