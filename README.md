# BootNavbar

![license](https://img.shields.io/github/license/kmlpandey77/bootnavbar?style=plastic)

> Bootstrap 4 Responsive Navbar with Multi level Dropdowns \
> This is fully responsive multilevel dropdown (treeview menu) navbar opened on hover.



## Preview
![Multi level hover dropdown Navbar for bootstrap 4](https://raw.githubusercontent.com/kmlpandey77/bootnavbar/master/Preview.png "Navbar Preview")

## Demo
[View Demo](https://kmlpandey77.github.io/bootnavbar)


## Rquirement
	jQuery
	boostrap 4
	animated.css // 

## Download
[Download source](https://github.com/kmlpandey77/bootnavbar/archive/1.0.1.zip)

## CDN

#### css
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/kmlpandey77/bootnavbar/css/bootnavbar.css">

```

#### js
```html
<script src="https://cdn.jsdelivr.net/gh/kmlpandey77/bootnavbar/js/bootnavbar.js"></script>
```	


## Usage
To use bootnavbar in your website, simply drop the stylesheet into your document's `<head>`.

```html
<head>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.7.2/animate.min.css">
  <link rel="stylesheet" href="css/bootstrap.min.css">
  <link rel="stylesheet" href="css/bootnavbar.css">
</head>
```


And, simply drop the JS into your document's `<body>`.

```html
<body>
	  ...
	  ...
	
	  <script src="https://code.jquery.com/jquery-3.3.1.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js"></script>
    <script src="js/bootstrap.min.js"></script>
    <script src="js/bootnavbar.js" ></script>
    <script>
        $(function () {
            $('#bootnavbar').bootnavbar({
              //options

              //animation: false

            });
        })
    </script>
<body>
```

And,  `html`.

```html
<nav class="navbar navbar-expand-lg navbar-light bg-light" id="bootnavbar">
  ...
  ...
</nav>
```


## Options

**animation**

Type: `Boolean`

Default: `true`

Enable/Disable animation effect



**animateIn**

Type: `String`

Default: `'fadeIn'`

Value: `'slideInUp'`,`'zoomIn'`



View more option in [animate.css](https://daneden.github.io/animate.css) 

