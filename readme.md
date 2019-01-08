# 安装使用步骤
## 首先安装Ruby
* 链接: https://pan.baidu.com/s/1To_UdIk2EQH-dg0kZYtb4Q 提取码: fse1
* 命令行输入ruby -v检测是否安装成功
## 替换国内源命令行输入
* 删除原gem源 gem sources --remove https://rubygems.org/
* 添加国内源 gem sources --add https://gems.ruby-china.com/ --remove https://rubygems.org/
* 打印是否替换成功 gem sources -l（更换成功后打印："*** CURRENT SOURCES ***""https://ruby-china.com/"）
## 安装Sass和Compass
* 安装Sass：gem install sass
* 安装Compass：gem install compass
## 使用
* 命令行找到css目录路径（路径下需要先创建.scss文件）
* 输入 sass test.scss  test.css 回车即生成.test.css.map和test.css两个文件
* 单个文件的监听，输入：sass  --watch  test.scss:test.css 回车即监听成功
### 注意：在页面中当然还是引用对应的.css文件
### demo：https://py-jax.github.io/sassRemVw/index.html