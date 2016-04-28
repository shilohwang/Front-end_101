#HTML Quiz week1

##About Sublime text
1. 更換其他預設monospace字體(例如：[Source code pro](https://github.com/adobe-fonts/source-code-pro/archive/2.010R-ro/1.030R-it.zip)，解壓縮後後選取OTF資料夾內的sourcecodepro-Regular.otf安裝)
2. 使用Package control套件安裝**Alignment**套件,安裝後可先參考網路上教學[如何使用此套件](http://kevintsengtw.blogspot.tw/2012/03/sublime-text-2-part5-alignmentcode.html)，並且使用它

##About HTML5
1. 新建立一個.html文件，並且包含以下內容(盡量使用Emmet產生)
2. 同時試試這些Tags：mark, q，並說明用途為何

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Document</title>
</head>
<body>
  <div id="header">
    <h1>Test Gallery</h1>
  </div>

  <div id="nav">
    <label for="favourite-phone">Search</label>
    <input type="phone_brand", id="phone_brand", list="site-list"/>
    <datalist id="site-list">
      <option value="Apple">
      <option value="Samsung">
      <option value="Sony">
      <option value="HTC">
    </datalist>
    <button>Go!</button>
    <hr>
    <select class="filter", id="option-filter">
      <optgroup label="html">
        <option value="head">head</option>
        <option value="body">body</option>
        <option value="footer">footer</option>
      </optgroup>
      <optgroup label="css">
        <option value="DOM">DOM</option>
        <option value="Translation">Translation</option>
        <option value="Rotation">Rotation</option>
      </optgroup>
      <optgroup label="javascript">
        <option value="jQuery">jQuery</option>
        <option value="jQuery-UI">jQuery-UI</option>
      </optgroup>
    </select>
    <ul type='circle'>
      <li><a href="#1">Item1</a></li>
      <li><a href="#2">Item2</a></li>
      <li><a href="#3">Item3</a></li>
    </ul>
  </div>

  <div id="section">
    <!-- 下面的image tage請選取自己電腦內的圖片 -->
    <img src="" alt="" width='200px'>
    <h2>Hello html~</h2>
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rem omnis eos harum voluptates ipsa qui, aperiam velit fugiat itaque ab, veritatis illo mollitia adipisci dolor laboriosam vitae neque soluta totam.</p>
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Fugit praesentium sunt ipsum sit accusamus aut repellendus laborum, laudantium sint voluptate, quibusdam ut, facilis nobis pariatur qui optio, voluptatibus doloremque reiciendis.</p>
  </div>

  <div id="footer">
    Copyright XXXX
  </div> 
</body>
</html>
```
