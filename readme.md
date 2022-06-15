Microsoft Ajax 测试
===

## form中参数 Requested-With=XMLHttpRequest 引发的网络安全问题

- 引用的jquery.unobtrusive-ajax.js 会在header和 form 中添加 Requested-With=XMLHttpRequest
- jquery.unobtrusive-ajax-fang.js 是我修改的版本，只在header 中添加 Requested-With=XMLHttpRequest





