# CodingFlow
it always good to have some standardized coding rules

indentation `2 spaces`
indentation type `tab`

### javascript

- put `'use strict';` on top.
- use single qoute for string.
- function brackets put as the sample below.
- no restrict on having space after `=`
- use [flow](https://github.com/facebook/flow) to check javascript input type, ([more details](https://code.facebook.com/posts/1505962329687926/flow-a-new-static-type-checker-for-javascript/)).

```javascript
/**
 * @param {Object} arg1 - user credentials.
 * @param {boolean} arg2 - login for 1 month.
 * @return boolean
 */
function test(arg1, arg2) {
  var string = 'test string'; // sample of string defination
  var username = arg1.username,
      password = arg1.password;
  var login=
    that.login(username, password, function(data){
      return data.result;
    });
  return login;
}
```

### sql
- no `"..." + "..."` allowed in code when writing sql statement
