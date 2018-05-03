1.安装sass
gem install sass

2.scss 转为css文件
sass test.scss
sass test.scss test.css

3.四中编译风格
sass --style nested test.scss test.css
sass --style expanded test.scss test.css
sass --style compact test.scss test.css
sass --style compressed test.scss test.css

4.watch a file
sass --watch input.scss:output.css

watch a directory
sass --watch app/sass:public/stylesheets


5.在线sass转css链接
https://www.sassmeister.com/