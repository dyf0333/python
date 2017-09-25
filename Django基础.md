# Django基础

Django admin

Django admin startproject，开始一个项目后面跟上一个项目名称，

python manager.py startpap blog



1、进来的请求转入/blog/
2. Django通过在ROOT_URLCONF来决定根URLconf。
3. Django在URLconf中的所有URL模式中，查找第一个匹配/hello/的条目。
4. 如果找到匹配，将调用相应的视图函数。
5. 视图函数返回一个HttpResponse。
6. Django转换HttpResponse为一个合适的HTTP response,以web page显示出来。
