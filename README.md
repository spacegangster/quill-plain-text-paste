Workaround for Quill editor

Issue – on mobile Quill.js flickers when you paste.

See github issue : https://github.com/quilljs/quill/issues/1374

[Solution](https://github.com/quilljs/quill/issues/1374#issuecomment-374008626)
by wonderful [Thomas Dao](https://github.com/thomasdao)


Usage
```
Quill.register('modules/clipboard', PlainTextClipboard);
```
