# PSR (PHP Standard Recommendation) 中文版

## 简介

最近在整理 PHP 开发过程中的需要注意的编码规范、最佳实践、安全编码问题、缓存等性能问题，等等，在涉及代码风格方向的规范时，本想对 PSR 作一个摘要性的总结。不过，在实施过程中发现条目过多，不如直接整理翻译 PSR，也正好弥补目前 PSR 中文版不全的问题。

由 PHP-FIG (PHP Framework Interoperability Group) 发起的 PSR 目前接受的规范列表如下（弃用内容及补充部分详看 `accepted` 目录）：

- [PSR-1 Basic Coding Standard](PSR-1-basic-coding-standard.md)

  PSR-1 基本编码规范（中文版）

- [PSR-2 Coding Style Guide](PSR-2-coding-style-guide.md)

  PSR-2 代码风格规范补充（中文版）

- [PSR-3 Logger Interface](PSR-3-logger-interface.md)

  PSR-3 日志接口（中文版）

- [PSR-4 Autoloader](PSR-4-autoloader.md)

  PSR-4 autoloader（中文版）

- [PSR-6 Cache](PSR-6-cache.md)

  PSR-6 缓存规范（中文版）

- [HTTP message interfaces](PSR-7-http-message.md)

  PSR-7 HTTP 消息接口（中文版）

下面是 PHP-FIG 的 PSR 项目 README 中的说明，这里引用一下：

## PHP 框架互操作小组

组建本小组的目的是，通过在各项目的代表之间讨论他们共同的编码规范，以制定一个协作标准。本规范的主要面向对象是本小组的各个组成成员，当然，同时也欢迎关注本规范的其它PHP社区采用本规范。


### 提交规范建议

可以通过以下方式给本规范提交建议:

- fork [PSR代码库][]，创建并检出一个分支，在 `proposed/` 下添加 规范建议，然后 push 分支到 Github，最后给我们发送一个 pull request；又或者

- 在 Github 下新建一个讨论 ticket；又或者

- 在[邮件列表][]中提交建议。

[邮件列表]: http://groups.google.com/group/php-fig/
[PSR代码库]: https://github.com/php-fig/fig-standards

### 成为投票成员

注意，你**不需要**成为投票成员才能在[邮件列表][]中发表言论。

想要成为投票成员，你必须发送一封邮件到[邮件列表][]中。

- 邮件主题格式如下: `Membership Request: {你的名字} ({参与的项目名称})`

- 邮件内容应包括你的名字、你参与的项目名称、项目的地址以及其它相关信息。
  
目前的成员会对你的加入请求进行投票。

请不要在一份申请中提交多个加入请求，每份申请只能提交一份请求。

