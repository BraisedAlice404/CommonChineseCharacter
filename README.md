# 新手压缩字体详细教程
## 文本压缩（文字抽取）
  - 打开[在线工具网站](https://transfonter.org/)
  - Add fonts
  - 按下图所示
  - <image src="https://img-blog.csdnimg.cn/20210918143847417.png?x-oss-process=image/watermark,type_ZHJvaWRzYW5zZmFsbGJhY2s,shadow_50,text_Q1NETiBAemhpeWFuMTk5MA==,size_20,color_FFFFFF,t_70,g_se,x_16"/>
  - Convert  
## 字体引入（按需即可）
```css
@font-face {
    font-family: ‘YourWebFontName’;
    src: url(‘YourWebFontName.eot’); /* IE9 Compat Modes */
    src: url(‘YourWebFontName.eot?#iefix’) format(‘embedded-opentype’), /* IE6-IE8 */
         url(‘YourWebFontName.woff’) format(‘woff’), /* Modern Browsers */
         url(‘YourWebFontName.ttf’) format(‘truetype’), /* Safari, Android, iOS */
         url(‘YourWebFontName.svg#YourWebFontName’) format(‘svg’); /* Legacy iOS */
}
```
