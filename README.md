Redmine 钉钉自定义机器人 WebHook 插件
======================

安装
------------------------------

    $ cd $RAILS_ROOT/plugins
    $ git clone https://github.com/JasonXJKJ/redmine_webhook.git
    $ rake redmine:plugins:migrate RAILS_ENV=production

------------------------------
### Post data
    {
      "msgtype": "text",
      "text": {
        "content": "xxx 创建 xx。指派给: xxx。紧急程度: x"
      }
    }

![avatar](https://raw.githubusercontent.com/JasonXJKJ/redmine_webhook/master/picture.png)

License
------------------------------
The MIT License (MIT)
Copyright (c) JasonXJKJ

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
