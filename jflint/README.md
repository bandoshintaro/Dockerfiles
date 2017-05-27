# docker jflint

- [npm](https://www.npmjs.com/package/jflint)

## Usage

- カレントディレクトリに.jflintrcを置いた状態でdocker runする

```
$ docker run --rm -v "$PWD:/jflint" bando/jflint Jenkinsfile
```
