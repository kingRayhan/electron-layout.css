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

**electron-col-***  - grid class for desktop and large screen [Works when screen size is bigger than **778px**]
**electron-col-t-***  - grid class for tab and medium screen [Works when screen size is bigger than **600px** and smaller than **778px**]

**electron-col-m-***  - grid class for mobile and large screen [Works when screen size is bigger than **600px**]
