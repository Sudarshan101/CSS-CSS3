<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Responsive List</title>
	<link href="assets/css/style.css" rel="stylesheet">
	<link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet">
	
  </head>
  <body>
	<div class="wrapper">
		<div class="page-content">
			<h1>Basic List</h1>
			<ul class="cs-list">
				<li class="cs-item">
					item1
				<li>
				<li class="cs-item">
					item2
				<li>
				<li class="cs-item">
					item3
				<li>
				<li class="cs-item">
					item4
				<li>
				<li class="cs-item">
					item5
				<li>
			</ul>
			<br />
			<h1>List with Divider</h1>
			<ul class="cs-list">
				<li class="cs-item">
					item1
				<li>
				<li class="cs-item">
					item2
				<li>
				<li class="cs-item cs-divider">
					item3
				<li>
				<li class="cs-item">
					item4
				<li>
				<li class="cs-item">
					item5
				<li>
			</ul>
			<br />
			<h1>Title/Description List</h1>
			<ul class="cs-list">
				<li class="cs-item">
					<h1 class="cs-title">Lorem Ipsum</h1>
					<h4 class="cs-sub-title">What is Lorem Ipsum?</h4>
					<p class="cs-description">Lorem Ipsum is simply dummy text of the printing and typesetting industry. </p>
				<li>
				<li class="cs-item">
					<h1 class="cs-title">Lorem Ipsum</h1>
					<h4 class="cs-sub-title">What is Lorem Ipsum?</h4>
					<p class="cs-description">Lorem Ipsum is simply dummy text of the printing and typesetting industry. </p>
				<li>
			</ul>
			<br />
			<h1>Thumbnail/Rounded Thumbnail/Avatar List</h1>
			<ul class="cs-list">
				<li class="cs-item cs-thumbnail-left">
					<img src="assets/images/img1.jpg" class="thumbnail-img" />
					<h1 class="cs-title">Lorem Ipsum</h1>
					<h4 class="cs-sub-title">What is Lorem Ipsum?</h4>
					<p class="cs-description">Lorem Ipsum is simply dummy text of the printing and typesetting industry. </p>
				<li>
				<li class="cs-item cs-thumbnail-right">
					<h1 class="cs-title">Lorem Ipsum</h1>
					<h4 class="cs-sub-title">What is Lorem Ipsum?</h4>
					<p class="cs-description">Lorem Ipsum is simply dummy text of the printing and typesetting industry. </p>
					<img src="assets/images/img2.jpg" class="rounded-img" />
				<li>
				<li class="cs-item cs-thumbnail-left cs-thumbnail-right">
					<img src="assets/images/img1.jpg" class="avatar-img" />
					<h1 class="cs-title">Lorem Ipsum</h1>
					<h4 class="cs-sub-title">What is Lorem Ipsum?</h4>
					<p class="cs-description">Lorem Ipsum is simply dummy text of the printing and typesetting industry. </p>
					<img src="assets/images/img2.jpg" class="rounded-img" />
				<li>
			</ul>
			<br />
			<h1>Thumbnail/Rounded Thumbnail/Avatar List with small size</h1>
			<ul class="cs-list">
				<li class="cs-item cs-thumbnail-left small-thumbnail">
					<img src="assets/images/img1.jpg" class="thumbnail-img" />
					item1
				<li>
				<li class="cs-item cs-thumbnail-right small-thumbnail">
					item1
					<img src="assets/images/img2.jpg" class="rounded-img" />
				<li>
				<li class="cs-item cs-thumbnail-left cs-thumbnail-right small-thumbnail">
					<img src="assets/images/img1.jpg" class="avatar-img" />
					item1
					<img src="assets/images/img2.jpg" class="thumbnail-img" />
				<li>
			</ul>
			<br />
			<h1>Icon List</h1>
			<ul class="cs-list">
				<li class="cs-item cs-icon-left">
					<i class="fa fa-address-book"></i>
					item1
				<li>
				<li class="cs-item cs-icon-left cs-icon-right">
					<i class="fa fa-grav"></i>
					item1
					<i class="fa fa-arrow-right"></i>
				<li>
				<li class="cs-item cs-icon-right">
					<i class="fa fa-arrow-right"></i>
					item1
				<li>
			</ul>
			<br />
			<h1>Button List</h1>
			<ul class="cs-list">
				<li class="cs-item cs-icon-left">
					<i class="fa fa-address-book"></i>
					item1
				<li>
				<li class="cs-item cs-icon-left cs-button-right">
					<i class="fa fa-grav"></i>
					item1
					<button class="cs-button fa fa-arrow-right"></button>
				<li>
			</ul>
			<br />
			<h1>Badge List</h1>
			<ul class="cs-list">
				<li class="cs-item cs-icon-left">
					<i class="fa fa-address-book"></i>
					item1
				<li>
				<li class="cs-item cs-icon-left cs-badge-right">
					<i class="fa fa-grav"></i>
					item1
					<span class="cs-badge">12</span>
				<li>
			</ul>
		</div>
	</div>
	<br /><br /><br />
  </body>
</html>
