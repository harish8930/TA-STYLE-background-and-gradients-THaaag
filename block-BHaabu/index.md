html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>colour grad</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<h1>Background & Gradient </h1>
<div class="container">
<div class="box1">box1</div>
<div class="box2">box2</div>
<div class="box3">box3</div>
</div>



<div class="container2">
<div class="box4">box4</div> 
</div>




</body>
</html>


style.css

html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure, 
footer, header, hgroup, menu, nav, section {
	display: block;
}
body {
	line-height: 1;
}
ol, ul {
	list-style: none;
}
blockquote, q {
	quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
	content: '';
	content: none;
}
table {
	border-collapse: collapse;}



	/*start*/

body{ background-image: url(pexels-photo-268533\(1\).jpeg);

}

.container{display: flex;
	flex-direction: row;
	justify-content: space-around;

}
h1{ font-size: 25px; 
color: white;
text-align: center;
margin-bottom: 30px;
}


.box1, .box2, .box3{width: 200px; 
height: 200px;
border-radius: 10px;
font-size: 10x;
font-weight: 800;
text-align: center;
border: 2px solid black;}

.box1{background-color: red;}

.box2{background-image: linear-gradient(to right, black, red);}

.box3 {background-image: radial-gradient(red, black);}




.container2{display: flex;
justify-content: center;

}

.box4{ background-image: url(700px.jpg);
background-image: linear-gradient(to right bottom,rgb(236, 22, 22));
width: 700px;
height: 300px;
margin-top: 50px;
border-radius: 5px;
}






