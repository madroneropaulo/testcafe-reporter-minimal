# testcafe-reporter-minimal
[![Build Status](https://travis-ci.org/DevExpress/testcafe-reporter-minimal.svg)](https://travis-ci.org/DevExpress/testcafe-reporter-minimal)

This is the **Minimal** reporter plugin for [TestCafe](http://devexpress.github.io/testcafe).

<p align="center">
    <img src="https://raw.github.com/DevExpress/testcafe-reporter-minimal/master/media/preview.png" alt="preview" />
</p>

## Install

This reporter is shipped with TestCafe by default. In most cases, you won't need to install it separately.

However, if you need to install this reporter, you can use the following command.

```
npm install testcafe-reporter-minimal
```

## Usage

When you run tests from the command line, specify the reporter name by using the `--reporter` option:

```
testcafe chrome 'path/to/test/file.js' --reporter minimal
```


When you use API, pass the reporter name to the `reporter()` method:

```js
testCafe
    .createRunner()
    .src('path/to/test/file.js')
    .browsers('chrome')
    .reporter('minimal') // <-
    .run();
```

## Author
Developer Express Inc. (https://devexpress.com)
