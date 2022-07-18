# axios-tauri-api-adapter
Makes it easy to use Axios in Tauri, support Typescript

# Installation

```
npm install axios-tauri-api-adapter
```

# Usage

```js
import axios from 'axios';
import axiosTauriApiAdapter from 'axios-tauri-api-adapter';
const client = axios.create({ adapter: axiosTauriApiAdapter });
```

# Features
- HTTP Requests use `@tauri-apps/api/http` instead of `XHR(XMLHttpRequest)`
- Add `config.jwt` It's going to add JWT to the header

# Todo

* [ ] Add tests

# Resources

* [Changelog](https://github.com/persiliao/axios-tauri-api-adapter/blob/master/CHANGELOG.md)
* [Contributing Guide](https://github.com/persiliao/axios-tauri-api-adapter/blob/master/CONTRIBUTING.md)
* [Code of Conduct](https://github.com/persiliao/axios-tauri-api-adapter/blob/master/CODE_OF_CONDUCT.md)
