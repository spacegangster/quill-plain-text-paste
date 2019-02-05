Workaround for Quill editor

Issue – on mobile Quill.js flickers when you paste.

See github issue : https://github.com/quilljs/quill/issues/1374

[Solution](https://github.com/quilljs/quill/issues/1374#issuecomment-374008626)
by wonderful [Thomas Dao](https://github.com/thomasdao)

-------------

Usage

```bash
# in your project root
yarn add quill-plain-text-paste
```

```js
// in your app – import and register the module
import PlainTextClipboard from 'quill-plain-text-paste'

Quill.register('modules/clipboard', PlainTextClipboard);
```

PS. you might want to add some UA detection and enable the code only for certain mobile devices
