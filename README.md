# electron-layout.css
#### v1.0.3


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


# Helper classes

## Text 

| Class Name | Works | Css declaration |
|---|---| --- |
| `.text-center `| Make text centered | ` { text-align: center !important; }` |
| `.text-right `| Aligns the text to the right | ` { text-align: right !important; }` |
| `.text-left `| Aligns the text to the left | ` { text-align: left !important; }` |


## Border


| Class Name | Works | Css declaration |
|---|---| --- |
| `.border-1`| 1px around border | ` { border: 1px solid; }` |
| `.border-2`| 2px around border | ` { border: 2px solid; }` |
| `.border-3`| 3px around border | ` { border: 3px solid; }` |
| `.border-4`| 4px around border | ` { border: 4px solid; }` |
| `.border-5`| 5px around border | ` { border: 5px solid; }` |
| `.border-5`| 5px around border | ` { border: 5px solid; }` |
| `.br-1`| 1px right border | ` { border-right: 1px solid; }` |
| `.br-2`| 2px right border | ` { border-right: 2px solid; }` |
| `.br-3`| 3px right border | ` { border-right: 3px solid; }` |
| `.br-4`| 4px right border | ` { border-right: 4px solid; }` |
| `.br-5`| 5px right border | ` { border-right: 5px solid; }` |
| `.bl-1`| 1px left border | ` { border-left: 1px solid; }` |
| `.bl-2`| 2px left border | ` { border-left: 2px solid; }` |
| `.bl-3`| 3px left border | ` { border-left: 3px solid; }` |
| `.bl-4`| 4px left border | ` { border-left: 4px solid; }` |
| `.bl-5`| 5px left border | ` { border-left: 5px solid; }` |
| `.bl-5`| 5px left border | ` { border-left: 5px solid; }` |
| `.bb-1`| 1px bottom border | ` { border-bottom: 1px solid; }` |
| `.bb-2`| 2px bottom border | ` { border-bottom: 2px solid; }` |
| `.bb-3`| 3px bottom border | ` { border-bottom: 3px solid; }` |
| `.bb-4`| 4px bottom border | ` { border-bottom: 4px solid; }` |
| `.bb-5`| 5px bottom border | ` { border-bottom: 5px solid; }` |
| `.bt-1`| 1px top border | ` { border-top: 1px solid; }` |
| `.bt-2`| 2px top border | ` { border-top: 2px solid; }` |
| `.bt-3`| 3px top border | ` { border-top: 3px solid; }` |
| `.bt-4`| 4px top border | ` { border-top: 4px solid; }` |
| `.bt-5`| 5px top border | ` { border-top: 5px solid; }` |


## Margins

#### Margin top

| Class Name | Css declaration |
|---|---|
| `.mt-0 `| `margin-top: 0 !important` |
| `.mt-10` | `margin-top: 10px !important` |
| `.mt-20` | `margin-top: 20px !important` |
| `.mt-30` | `margin-top: 30px !important` |
| `.mt-40` | `margin-top: 40px !important` |
| `.mt-50` | `margin-top: 50px !important` |
| `.mt-60` | `margin-top: 60px !important` |
| `.mt-70` | `margin-top: 70px !important` |
| `.mt-80` | `margin-top: 80px !important` |
| `.mt-90` | `margin-top: 90px !important` |
| `.mt-10` | ` margin-top: 100px !important` |

#### Margin right

| Class Name | Css declaration |
|---|---|
| `.mr-0 `| `margin-right: 0 !important` |
| `.mr-10` | `margin-right: 10px !important` |
| `.mr-20` | `margin-right: 20px !important` |
| `.mr-30` | `margin-right: 30px !important` |
| `.mr-40` | `margin-right: 40px !important` |
| `.mr-50` | `margin-right: 50px !important` |
| `.mr-60` | `margin-right: 60px !important` |
| `.mr-70` | `margin-right: 70px !important` |
| `.mr-80` | `margin-right: 80px !important` |
| `.mr-90` | `margin-right: 90px !important` |
| `.mr-10` | ` margin-right: 100px !important` |


#### Margin bottom

| Class Name | Css declaration |
|---|---|
| `.mb-0 `| `margin-bottom: 0 !important` |
| `.mb-10` | `margin-bottom: 10px !important` |
| `.mb-20` | `margin-bottom: 20px !important` |
| `.mb-30` | `margin-bottom: 30px !important` |
| `.mb-40` | `margin-bottom: 40px !important` |
| `.mb-50` | `margin-bottom: 50px !important` |
| `.mb-60` | `margin-bottom: 60px !important` |
| `.mb-70` | `margin-bottom: 70px !important` |
| `.mb-80` | `margin-bottom: 80px !important` |
| `.mb-90` | `margin-bottom: 90px !important` |
| `.mb-10` | ` margin-bottom: 100px !important` |


#### Margin left

| Class Name | Css declaration |
|---|---|
| `.ml-0 `| `margin-left: 0 !important` |
| `.ml-10` | `margin-left: 10px !important` |
| `.ml-20` | `margin-left: 20px !important` |
| `.ml-30` | `margin-left: 30px !important` |
| `.ml-40` | `margin-left: 40px !important` |
| `.ml-50` | `margin-left: 50px !important` |
| `.ml-60` | `margin-left: 60px !important` |
| `.ml-70` | `margin-left: 70px !important` |
| `.ml-80` | `margin-left: 80px !important` |
| `.ml-90` | `margin-left: 90px !important` |
| `.ml-10` | ` margin-left: 100px !important` |


## Paddings

#### Padding top

| Class Name | Css declaration |
|---|---|
| `.pt-0 `| `padding-top: 0 !important` |
| `.pt-10` | `padding-top: 10px !important` |
| `.pt-20` | `padding-top: 20px !important` |
| `.pt-30` | `padding-top: 30px !important` |
| `.pt-40` | `padding-top: 40px !important` |
| `.pt-50` | `padding-top: 50px !important` |
| `.pt-60` | `padding-top: 60px !important` |
| `.pt-70` | `padding-top: 70px !important` |
| `.pt-80` | `padding-top: 80px !important` |
| `.pt-90` | `padding-top: 90px !important` |
| `.pt-10` | ` padding-top: 100px !important` |

#### Padding right

| Class Name | Css declaration |
|---|---|
| `.pr-0 `| `padding-right: 0 !important` |
| `.pr-10` | `padding-right: 10px !important` |
| `.pr-20` | `padding-right: 20px !important` |
| `.pr-30` | `padding-right: 30px !important` |
| `.pr-40` | `padding-right: 40px !important` |
| `.pr-50` | `padding-right: 50px !important` |
| `.pr-60` | `padding-right: 60px !important` |
| `.pr-70` | `padding-right: 70px !important` |
| `.pr-80` | `padding-right: 80px !important` |
| `.pr-90` | `padding-right: 90px !important` |
| `.pr-10` | ` padding-right: 100px !important` |


#### Padding bottom

| Class Name | Css declaration |
|---|---|
| `.pb-0 `| `padding-bottom: 0 !important` |
| `.pb-10` | `padding-bottom: 10px !important` |
| `.pb-20` | `padding-bottom: 20px !important` |
| `.pb-30` | `padding-bottom: 30px !important` |
| `.pb-40` | `padding-bottom: 40px !important` |
| `.pb-50` | `padding-bottom: 50px !important` |
| `.pb-60` | `padding-bottom: 60px !important` |
| `.pb-70` | `padding-bottom: 70px !important` |
| `.pb-80` | `padding-bottom: 80px !important` |
| `.pb-90` | `padding-bottom: 90px !important` |
| `.pb-10` | ` padding-bottom: 100px !important` |


#### Padding left

| Class Name | Css declaration |
|---|---|
| `.pl-0 `| `padding-left: 0 !important` |
| `.pl-10` | `padding-left: 10px !important` |
| `.pl-20` | `padding-left: 20px !important` |
| `.pl-30` | `padding-left: 30px !important` |
| `.pl-40` | `padding-left: 40px !important` |
| `.pl-50` | `padding-left: 50px !important` |
| `.pl-60` | `padding-left: 60px !important` |
| `.pl-70` | `padding-left: 70px !important` |
| `.pl-80` | `padding-left: 80px !important` |
| `.pl-90` | `padding-left: 90px !important` |
| `.pl-10` | ` padding-left: 100px !important` |
