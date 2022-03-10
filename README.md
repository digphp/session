# Session操作类

提供便捷的session操作方法

## 安装

``` cmd
composer require digphp/session
```

## 用例

``` php
$session = new \DigPHP\Session\Session();
$session->set('foo', 'some val..');
$session->get('foo', 'default val.');
$session->has('foo');
$session->delete('foo');
```
