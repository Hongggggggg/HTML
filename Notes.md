- h1主标题

  ```html
  <h1>Hello World</h1>
  ```
  
- h2副标题

  ```html
  <h2>CatPhotoApp</h2>
  ```
  
- p标签，正文段落

  ```html
  <p>CatPhotoApp</p>
  ```

- 注释

  ```html
  <!-->注释<-->
  ```

- main标签，起提示作用，告诉我们网站的主要内容就是main标签当中的部分

  ```html
  <main>
      <h1>Hello World</h1>
      <p>CatPhotoApp</p>
  </main>
  ```
  
- img标签，插入图片，并且可以用src属性指定图片地址。

  ```html
  <img src="https://www.freecatphotoapp.com/your-image.jpg">
  ```

  img是self-closing的标签，不需要再单独写一个closing tag。

  所有的img元素必须要有一个alt属性，alt属性是在图片无法显示的时候用来填充的内容，如果图片仅仅是用来装饰，可以用空字符串填充

  ```html
  <img src="https://www.freecatphotoapp.com/your-image.jpg" alt="A business cat wearing a necktie.">
  ```

- a标签，插入超链接

  ```html
  <a href="https://freecodecamp.org">this links to freecodecamp.org</a>
  ```

  ​	a标签需要一个网站地址作为目的地，这个网址是填在href属性内的，其次a标签也需要一段文本作为超链接的提示语。
  
  ​	a元素除了可以指向外部的链接，同样叶可以跳转到网站内部的某一区域。想要创建内部的链接，同样需要使用href这个属性，我们将它设置成‘#’加上具体的id的形式来实现，这里的id是HTML当中的一个通用属性，任何标签都可以加上id。
  ```html
  <a href="#header">Contacts</a>
  ...
  <h2 id="header">Contacts</h2>
  ```
  ​	我们给h2标签了一个id属性，当我们点击a标签的时候，它就会跳转到这个id标记的区域
  
  ​	a标签除了可以单独使用，也可将其嵌入至其他文本当中。
  
  ```html
  <p>
  	Here's a <a target="_blank" href="http://freecodecamp.org"> link to freecodecamp.org</a> for you to follow.
  </p>
  ```
  
  ​	其中target属性为“_blank”，既点击这个标签时，会打开一个新的网页tab。

