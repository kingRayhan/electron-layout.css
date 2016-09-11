# electron-layout.css


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
    <dd>__Grid class for desktop and large screen <br>__Works when screen size is bigger than 778px__</dd>

    <dt>.electron-col-t-*</dt>
    <dd>__Grid class for tab and medium screen <br>_Works when screen size is bigger than 600px and smaller than 778px__</dd>

    <dt>.electron-col-m-*</dt>
    <dd>__Grid class for mobile and large screen <br>_Works when screen size is bigger than 600px__</dd>
</dl>
