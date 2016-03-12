## stylelint subdirectories

### Getting Started

```shell
$ git clone https://github.com/frenzzy/stylelint-subdirectories-test.git
$ cd stylelint-subdirectories-test
$ npm install
```

### How to Run

```shell
$ npm test
```

### Actual Result

```shell
test/style.css
1:8 Unexpected empty block (block-no-empty)
```

### Expected Result

```shell
style.css
1:8 Unexpected empty block (block-no-empty)
test/style.css
1:8 Unexpected empty block (block-no-empty)
test/second/style.css
1:8 Unexpected empty block (block-no-empty)
test/second/third/style.css
1:8 Unexpected empty block (block-no-empty)
test/second/third/fourth/style.css
1:8 Unexpected empty block (block-no-empty)
```
