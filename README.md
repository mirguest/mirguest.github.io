# mirguest.github.io

采用 org-mode 生成 html 为主。部分页面是自己写的html。

- org 文件位于: https://github.com/mirguest/pages
- 在 init.el 文件中，设置将 pages 中的内容导出到 mirguest.github.io
- 代码片段：
```elisp
 '(org-publish-project-alist
   (quote
     (("org-pages" :base-directory "c:/Users/mirgu/Documents/GitHub/pages" :publishing-directory "c:/Users/mirgu/Documents/GitHub/mirguest.github.io" :publishing-function org-html-publish-to-html :recursive t)
     ("org-paper" :base-directory "c:/Users/mirgu/Documents/GitHub/paper" :publishing-directory "c:/Users/mirgu/Documents/GitHub/paper" :publishing-function org-html-publish-to-html :recursive t))))

```
