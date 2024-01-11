# ob-swift-enhanced
修复已有ob-swift对session支持的问题，使用swift-mode中的run-swift来创建session，另外对结果显示进行优化处理。

## 使用方法
将代码下载到site-lisp中，然后使用下面的代码引入。

``` emacs-lisp
(use-package ob-swift-enhanced
  :ensure nil
  :load-path "~/.emacs.d/site-lisp/ob-swift-enhanced")
```

