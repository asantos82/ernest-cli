我是光年实验室高级招聘经理。
我在github上访问了你的开源项目，你的代码超赞。你最近有没有在看工作机会，我们在招软件开发工程师，拉钩和BOSS等招聘网站也发布了相关岗位，有公司和职位的详细信息。
我们公司在杭州，业务主要做流量增长，是很多大型互联网公司的流量顾问。公司弹性工作制，福利齐全，发展潜力大，良好的办公环境和学习氛围。
公司官网是http://www.gnlab.com,公司地址是杭州市西湖区古墩路紫金广场B座，若你感兴趣，欢迎与我联系，
电话是0571-88839161，手机号：18668131388，微信号：echo 'bGhsaGxoMTEyNAo='|base64 -D ,静待佳音。如有打扰，还请见谅，祝生活愉快工作顺利。

# Ernest CLI

## Synopsis

Ernest helps you deploy your vcloud infrastructure with a few shell commands.

## Build status

* Master [![CircleCI](https://circleci.com/gh/ernestio/ernest-cli/tree/master.svg?style=svg)](https://circleci.com/gh/ernestio/ernest-cli/tree/master)
* Develop [![CircleCI](https://circleci.com/gh/ernestio/ernest-cli/tree/develop.svg?style=svg)](https://circleci.com/gh/ernestio/ernest-cli/tree/develop)

## Installation

In order to install it and have it running, you just need to run the following commands:

```
$ git clone git@github.com:ernestio/ernest-cli.git
$ cd ernest-cli
$ make
$ make install
```

## Set up

You need to set up your remote ernest instance
```
$ ernest target "http://my.ernest.io"
```

## Run it

You can get help by running:
```
$ ernest
```

And read our documentation about [how to use the CLI](http://ernest.io/documentation/cli-guide/)

## Running Tests

```
make test
```

## Contributing

Please read through our
[contributing guidelines](CONTRIBUTING.md).
Included are directions for opening issues, coding standards, and notes on
development.

Moreover, if your pull request contains patches or features, you must include
relevant unit tests.

## Versioning

For transparency into our release cycle and in striving to maintain backward
compatibility, this project is maintained under [the Semantic Versioning guidelines](http://semver.org/).

## Copyright and License

Code and documentation copyright since 2015 r3labs.io authors.

Code released under
[the Mozilla Public License Version 2.0](LICENSE).
