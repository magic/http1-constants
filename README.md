## @magic/http1_constants

http 1.1 headers, methods and status codes as constant variables

- [install](#install)
- [usage](#usage)
- [changelog](#changelog)

### <a name="install"></a>install

be in a nodejs project.

```bash
npm i --save-dev @magic/http1_constants
```

### <a name="usage"></a>usage

```javascript
import constants from '@magic/http1_constants'

constants.headers.X_FORWARDED_FOR === 'x-forwarded-for'

constants.methods.GET === 'GET'

constants.status.OK === 200
```

#### <a name="changelog"></a>changelog

##### 0.0.2 - unreleased

...

##### 0.0.1

first commit
