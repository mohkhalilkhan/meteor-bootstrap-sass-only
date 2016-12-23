meteor-bootstrap3-sass-Only
======================
[![Build Status](https://travis-ci.org/dyaa/meteor-bootstrap3-sass-only.svg)](https://travis-ci.org/dyaa/meteor-bootstrap3-sass-only)

Meteor package for Bootstrap 3 with Sass support

To install
----------

Install the `fourseven:scss` SCSS compiler package and the `dyaa:bootstrap-sass-only` package.

```sh
$ meteor add fourseven:scss
$ meteor add dyaa:bootstrap-sass-only
```

To use
------

To activate bootstrap styles on your site, add the following line to the top of your main scss file:

```scss
@import '{dyaa:bootstrap-sass-only}/bootstrap';
```

Be sure to add the appropriate tags (as [recommended by Bootstrap](http://getbootstrap.com/getting-started/#template)) to your document `<head>` somewhere in your HTML. Where you add these tags is dependent on how your meteor project is structured.

```html
<head>
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<!-- HTML5 Shim and Respond.js IE8 support of HTML5 elements and media queries -->
	<!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
	<!--[if lt IE 9]>
		<script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
		<script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
	<![endif]-->
</head>
```

--------------------------------------------------------

Inspired by [englue](https://github.com/englue) 

#### License

Copyright (c) 2017 [Dyaa Eldin Moustafa][1] Licensed under the [MIT license][2].


  [1]: https://dyaa.me/
  [2]: https://github.com/dyaa/meteor-bootstrap-sass-only/blob/master/LICENSE.md