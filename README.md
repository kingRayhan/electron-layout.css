<h1>electron-layout.css</h1>version 1.0.2 <br/>




Classess

```css
.electron-container{
  max-width: 1170px;
  width: 95%;
  margin: auto;
  display: table;
}
```

```css
.electron-row:before,
.electron-row:after{
  display: table;
  content: " ";
  clear: both;
}
```

### Grid classes

<dl>
    <dt>.electron-col-*</dt>
    <dd>Grid class for desktop and large screen <br><u>Works when screen size is bigger than 778px</u></dd>

    <dt>.electron-col-t-*</dt>
    <dd>Grid class for tab and medium screen <br><u>Works when screen size is bigger than 600px and smaller than 778px</u></dd>

    <dt>.electron-col-m-*</dt>
    <dd>Grid class for mobile and large screen <br><u>Works when screen size is bigger than 600px</u></dd>
</dl>
