# Basic-CSS

Reference the attached HTML file [5_CSS1-1.html](https://github.com/user-attachments/files/25055057/5_CSS1-1.html)
Download attached HTML file.  Your job is to create the CSS (use an external .css file, as indicated in the <link> tag) to replicate the below images, as closely as possible.

Requirements:

Background color closely matches
Header sizes closely match
Top header is aligned correctly
The 2nd paragraph closely matches, including the width, margin, padding, border, and line-height
The 4th and 5th paragraphs closely match colors
Link colors closely match
The link to w3schools is a different color than the list item links
List Items uses two digits
The table header and cells have different backgrounds
The table border applies to all cells, and the borders are overlapping.

Final Image: 
<img width="1898" height="782" alt="image" src="https://github.com/user-attachments/assets/92de14fb-0b77-4948-b434-cf8e8463bdf8" />
<img width="1891" height="549" alt="image" src="https://github.com/user-attachments/assets/765b17c6-e28d-46d3-be0b-3396774fbea6" />




<!--
[Uploading 5_CSS1-1.html…]()
<!DOCTYPE html>

<html lang="en">
	<head>
		<title>CSS Examples</title>
		<link rel="stylesheet" href="5_css1.css">
	</head>
	
	<body>
		<h1>CSS Examples</h1>
		
		<article>
		<h2>Paragraphs</h2>
			<section>
				<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut eget augue felis. Pellentesque at magna ut elit suscipit tincidunt et quis magna. Sed eu feugiat orci. Aenean posuere nunc a ornare scelerisque. Pellentesque varius metus in diam vestibulum consequat a id metus. Etiam non semper nibh. Praesent quis porttitor risus. Pellentesque maximus lorem id varius tincidunt. Proin viverra purus mollis turpis molestie, in pulvinar elit auctor. Morbi libero massa, aliquam convallis nisi id, mattis vehicula magna. Nullam libero nunc, molestie a tempor ut, scelerisque sed diam. Nunc tristique consectetur mollis. Nulla venenatis mi massa, sit amet accumsan risus iaculis sed. Phasellus porta sapien at eros rhoncus, ut accumsan est tincidunt.</p>
				<p id="paragraph2">Donec maximus lectus sed ipsum varius ornare. Cras tincidunt lacus sit amet leo viverra, quis bibendum tortor posuere. Etiam a neque non nunc gravida convallis ac eu justo. Nunc dignissim, purus ac dapibus egestas, mauris felis eleifend enim, ac sollicitudin turpis est eu quam. Phasellus sed suscipit nunc. Praesent lobortis mattis rhoncus. Mauris aliquam posuere massa a bibendum</p>
			</section>
			<section>
				<p>Mauris id mauris convallis, <em>elementum nibh nec</em>, pulvinar enim. Fusce ac nulla enim. Proin efficitur tincidunt ligula, non commodo nibh sodales in. Nunc pretium elementum suscipit. Aenean pellentesque in quam vel ultrices. Mauris eleifend tellus dignissim nunc pretium, sit amet hendrerit metus consequat. Pellentesque ullamcorper nunc eu ultricies faucibus. Morbi vulputate interdum ligula, at consectetur urna consequat a. Cras aliquet, metus a consectetur congue, sem nisi vehicula nulla, at maximus velit nisl ut diam. Quisque placerat dolor at ex mollis, a tristique massa bibendum. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus!</p>
				<p class="blue">Aliquam erat volutpat. Maecenas consequat sed ante a vehicula. Integer ultricies justo volutpat, convallis erat eu, pellentesque quam. Donec efficitur arcu non porta suscipit. Integer cursus nibh vitae tincidunt aliquet. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Vestibulum lacinia dapibus pharetra. Donec hendrerit, orci non luctus hendrerit, urna ipsum tincidunt erat, quis varius nibh dui non diam</p>
				<p class="blue">Ut vitae congue nibh, ac faucibus purus. In pulvinar mi id tellus rutrum faucibus. Nunc non massa lorem. Morbi ac arcu nec risus dignissim pretium. Sed in ex dui. Aliquam erat volutpat. Etiam enim eros, pharetra congue gravida eget, bibendum et odio. Integer magna metus, accumsan ut lobortis vitae, eleifend et neque. Sed ut quam mauris. Suspendisse ac ullamcorper nisl. Sed non luctus massa, nec tristique ligula. Vivamus egestas sem euismod lacus eleifend, at fringilla quam mattis. Sed mattis lacus ut rutrum placerat. Fusce finibus lacus in augue pharetra luctus</p>
			</section>
		</article>
		
		<article>
			<h2>Lists, Links, and Tables</h2>
			<ol>
				<li><a href="#">Item 1</a></li>
				<li><a href="#">Item 2</a></li>
				<li><a href="#">Item 3</a></li>
				<li><a href="#">Item 4</a></li>
				<li><a href="#">Item 5</a></li>
			</ol>
			
			<section>
				<h3>Common HTML Tags</h3>
				
				<p><a href="http://www.w3schools.com" target="_blank">W3schools.com</a> has a great resource for HTML, CSS, and JavaScript!</p>
				
				<table>
					<tr>
						<th>Tag</th><th>Description</th>
					</tr>
					<tr>
						<td>table</td><td>Root for tabular data to be displayed on the page.</td>
					</tr>
					<tr>
						<td>p</td><td>Defines a paragraph.  Considered a block element.</td>
					</tr>
					<tr>
						<td>a</td><td>"Anchor", or link.  Lets users navigate to another page.</td>
					</tr>
					<tr>
						<td>strong</td><td>Indicates how the text should have a strong inflection.  By default, applies bold to the text.</td>
					</tr>
					<tr>
						<td>img</td><td>Adds an image to the page.  Uses the "src" attribute to specify the location of the resource.</td>
					</tr>
				</table>
			</section>
			
		</article>
	</body>
</html>

``
[Uploading 5_CSS1-1.html…]()
<!DOCTYPE html>

<html lang="en">
	<head>
		<title>CSS Examples</title>
		<link rel="stylesheet" href="5_css1.css">
	</head>
	
	<body>
		<h1>CSS Examples</h1>
		
		<article>
		<h2>Paragraphs</h2>
			<section>
				<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut eget augue felis. Pellentesque at magna ut elit suscipit tincidunt et quis magna. Sed eu feugiat orci. Aenean posuere nunc a ornare scelerisque. Pellentesque varius metus in diam vestibulum consequat a id metus. Etiam non semper nibh. Praesent quis porttitor risus. Pellentesque maximus lorem id varius tincidunt. Proin viverra purus mollis turpis molestie, in pulvinar elit auctor. Morbi libero massa, aliquam convallis nisi id, mattis vehicula magna. Nullam libero nunc, molestie a tempor ut, scelerisque sed diam. Nunc tristique consectetur mollis. Nulla venenatis mi massa, sit amet accumsan risus iaculis sed. Phasellus porta sapien at eros rhoncus, ut accumsan est tincidunt.</p>
				<p id="paragraph2">Donec maximus lectus sed ipsum varius ornare. Cras tincidunt lacus sit amet leo viverra, quis bibendum tortor posuere. Etiam a neque non nunc gravida convallis ac eu justo. Nunc dignissim, purus ac dapibus egestas, mauris felis eleifend enim, ac sollicitudin turpis est eu quam. Phasellus sed suscipit nunc. Praesent lobortis mattis rhoncus. Mauris aliquam posuere massa a bibendum</p>
			</section>
			<section>
				<p>Mauris id mauris convallis, <em>elementum nibh nec</em>, pulvinar enim. Fusce ac nulla enim. Proin efficitur tincidunt ligula, non commodo nibh sodales in. Nunc pretium elementum suscipit. Aenean pellentesque in quam vel ultrices. Mauris eleifend tellus dignissim nunc pretium, sit amet hendrerit metus consequat. Pellentesque ullamcorper nunc eu ultricies faucibus. Morbi vulputate interdum ligula, at consectetur urna consequat a. Cras aliquet, metus a consectetur congue, sem nisi vehicula nulla, at maximus velit nisl ut diam. Quisque placerat dolor at ex mollis, a tristique massa bibendum. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus!</p>
				<p class="blue">Aliquam erat volutpat. Maecenas consequat sed ante a vehicula. Integer ultricies justo volutpat, convallis erat eu, pellentesque quam. Donec efficitur arcu non porta suscipit. Integer cursus nibh vitae tincidunt aliquet. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Vestibulum lacinia dapibus pharetra. Donec hendrerit, orci non luctus hendrerit, urna ipsum tincidunt erat, quis varius nibh dui non diam</p>
				<p class="blue">Ut vitae congue nibh, ac faucibus purus. In pulvinar mi id tellus rutrum faucibus. Nunc non massa lorem. Morbi ac arcu nec risus dignissim pretium. Sed in ex dui. Aliquam erat volutpat. Etiam enim eros, pharetra congue gravida eget, bibendum et odio. Integer magna metus, accumsan ut lobortis vitae, eleifend et neque. Sed ut quam mauris. Suspendisse ac ullamcorper nisl. Sed non luctus massa, nec tristique ligula. Vivamus egestas sem euismod lacus eleifend, at fringilla quam mattis. Sed mattis lacus ut rutrum placerat. Fusce finibus lacus in augue pharetra luctus</p>
			</section>
		</article>
		
		<article>
			<h2>Lists, Links, and Tables</h2>
			<ol>
				<li><a href="#">Item 1</a></li>
				<li><a href="#">Item 2</a></li>
				<li><a href="#">Item 3</a></li>
				<li><a href="#">Item 4</a></li>
				<li><a href="#">Item 5</a></li>
			</ol>
			
			<section>
				<h3>Common HTML Tags</h3>
				
				<p><a href="http://www.w3schools.com" target="_blank">W3schools.com</a> has a great resource for HTML, CSS, and JavaScript!</p>
				
				<table>
					<tr>
						<th>Tag</th><th>Description</th>
					</tr>
					<tr>
						<td>table</td><td>Root for tabular data to be displayed on the page.</td>
					</tr>
					<tr>
						<td>p</td><td>Defines a paragraph.  Considered a block element.</td>
					</tr>
					<tr>
						<td>a</td><td>"Anchor", or link.  Lets users navigate to another page.</td>
					</tr>
					<tr>
						<td>strong</td><td>Indicates how the text should have a strong inflection.  By default, applies bold to the text.</td>
					</tr>
					<tr>
						<td>img</td><td>Adds an image to the page.  Uses the "src" attribute to specify the location of the resource.</td>
					</tr>
				</table>
			</section>
			
		</article>
	</body>
</html>

-->
