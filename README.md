# [Toit programming language][1] syntax highlighting support for Sublime Text 3

You can download using the following commands:

```sh
$ git clone https://github.com/snxx-lppxx/toit-sublime.git -b develop
$ cd toit-sublime
$ xcopy /y /o /e ".\toit-sublime" "%AppData%\Sublime_Text_3\Packages\Toit"
```

You can test the `test-version` of the file:

```sh
$ toit run --no-device ./test/syntax_test.toit
```

## Licensed Agreement of Author with Recipients

For license and copyright information please follow this like: <https://github.com/snxx-lppxx/toit-sublime/blob/master/LICENSE>.

[1]: https://toit.io
