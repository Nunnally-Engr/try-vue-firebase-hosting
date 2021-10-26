# Vue.js + Firebase Hosting Sample

## Version info

- vue@2.6.14
- vue/cli@4.5.14
- vue-router@3.5.2
- vuex@3.6.2
- Node: 14.17.1
- firebase-tools@9.14.0

## Prerequisites

- FirebaseでdeployするProjectが作成されていること(今回は `try-vue-firebase-hosting` というProjectをFirebase上に作成)

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Lints and fixes files
```
yarn lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

## Firebase Setting

```
# Firebase Hosting未設定の場合
firebase init hosting

# Firebase Hosting設定済の場合
firebase init hosting:github
```

## Remarks

- リロードした時に404エラーになる対応済( `public/_redirects` ファイルと `firebase.json` の `rewrites` の部分参照)

## Reference URL

- [Deploy to live & preview channels via GitHub pull requests](https://firebase.google.com/docs/hosting/github-integration)