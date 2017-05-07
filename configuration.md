## 환경설정

`node.js`와 `npm`이 설치되어 있어야 합니다.



`vue2-admin-lte` 를 설치합니다.

```bash
$ npm install vue2-admin-lte
```



`webpack`에 `alias`를 등록합니다.

```js
module.exports = {
  resolve: {
    alias: {
      'va': 'vue2-admin-lte/src'
    }
  }
}
```



전역으로 등록하기 위해 `css`와 `js`파일을 `import`합니다.

```js
// css files
import 'va/lib/css'

// js files
import 'va/lib/script'
```



