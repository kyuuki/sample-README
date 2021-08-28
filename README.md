README サンプル
===============

GitHub 用 README のサンプル。

[![Build status][shield-build]](#)
[![MIT licensed][shield-license]](#)
[![Rails][shield-rails]][rails]

## Table of Contents

* [Technologies](#technologies)
* [Demo](#demo)
* [Getting started](#getting-started)
* [Deployment](#deployment)
* [Usage](#usage)
* [References](#references)
* [License](#license)

## Technologies

* [Rails][rails] 6.0.x
* [PostgreSQL][postgresql]
* [Heroku][heroku]
* [Kotlin][kotlin] 1.4.x
* [Flutter][flutter] 2.0.x

## Demo

* [GitHub](https://github.com/kyuuki/sample-README)

## Getting started

sample-xxx 系はサンプル自体の作り方を記述。
本来はソースコードの使い始め方。

### README.md

```sh
$ mkdir sample-README
$ cd sample-README
```

- README.md を編集

```
$ git init
$ git add README.md
$ git commit -m "Initial commit"
```

### GitHub

- GitHub に sample-README という名前でリポジトリ追加

```sh
$ git remote add origin git@github.com:kyuuki/sample-README.git
$ git push -u origin master
```

## Deployment

## Usage

* [基本的な書き方とフォーマットの構文 (日)](https://docs.github.com/ja/github/writing-on-github/basic-writing-and-formatting-syntax)

## References

* [読みやすいREADMEを書く](https://yakst.com/ja/posts/3859)
* [素敵なREADMEの書き方](https://qiita.com/koeri3/items/f85a617dcb6efebb2cab)
* [shields.ioを使って技術系アイコンを量産した](https://qiita.com/s-yoshiki/items/436bbe1f7160b610b05c)
* [Awesome README](https://github.com/matiassingers/awesome-readme)

## License

This is licensed under the [MIT](https://choosealicense.com/licenses/mit/) license.  
Copyright &copy; 2021 [Fuji Programming Laboratory](https://fuji-labo.com/)



[rails]: https://rubyonrails.org/
[postgresql]: https://www.postgresql.org/
[heroku]: https://www.heroku.com/home

[kotlin]: https://kotlinlang.org/
[flutter]: https://flutter.dev/

[shield-build]: https://img.shields.io/badge/build-passing-brightgreen.svg
[shield-license]: https://img.shields.io/badge/license-MIT-blue.svg
[shield-rails]: https://img.shields.io/badge/-Rails-CC0000.svg?logo=ruby-on-rails&style=flat
