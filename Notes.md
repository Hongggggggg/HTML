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

  