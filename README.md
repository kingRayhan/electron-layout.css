<h1 style="
    display: inline-block;
    border-bottom: none;
    margin-right: 8px;
"><a id="user-content-electron-layoutcss" class="anchor" href="#electron-layoutcss" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>electron-layout.css</h1>




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
