# Web-Technology - Labo 8 - 



## Voorbeeld responsive design

Bekijk onderstaande code zodat je een idee krijgt om een responsive design uit te werken.
Test de code zelf even uit.


CSS code:

```html
<style>
			
			body {
      background-color: #FEF8EF;
      font-family: Georgia, serif;
      width: 55%;
      margin: 0 auto 100px auto;}

img {
      display: block;
      margin: 0 auto;
      max-width: 100%;}

.kader {
      background-color: white;
      padding: 35px;
      line-height: 1.8em;
      margin: auto;}

a {color: #ED462F;}
p { margin-bottom: 35px;}

input {
      background-color: white;
      border: 2px solid #ED462F;
      color: #ED462F;
      font-size: 1em;
      padding: 15px;
      display: block;
      margin: auto;
      font-family: Georgia, serif;}

@media (max-width: 1100px) {
    body {
        width: 60%;
    }
}

@media (max-width: 910px) {
    body {
        width: 70%;
    }
}

@media (max-width: 810px) {
    body {
        width: 80%;
    }
}

@media (max-width: 710px) {
    body {
        width: 90%;
    }
}

@media (max-width: 610px) {
    body {
        width: 95%;
    }
}

@media (max-width: 450px) {
    .kader {
        padding: 20px;
          font-size: 0.9em;
    }
}

</style>

```

De html code:

```html

<body>

		<img src="https://gallery.mailchimp.com/f7b9ee22124ff6454424dc10c/images/bdf98581-9656-47fc-85a5-b962e42159d3.jpg">
		<div class="kader">
			<p>
				The holidays are an important time for marketers and e-commerce sellers. And email is the best way to reach your audience and generate revenue. This year, we’ve partnered with 5 leading brands—Facebook, Google, Twitter, Shopify, and WooCommerce—to create an <a href="#">automated email series</a> filled with insights, case studies, and best practices.
			</p>
			<p>
				Plus, we’ve written 100 tips you can put to use in your holiday marketing efforts. We’ve even included some beautiful campaigns and products from our customers.
			</p>
			<input type="submit" value="Explore The Tips">

		</div>

	</body>


```

## Oefening 2. 

De basis code:

Maak een responsive website waarbij de kubus onzichtbaar is bij een schermgrootte groter 
dan 1200px. Bij kleinere schermgroottes is de kubus zichtbaar, maar verandert van kleur
en grootte. Bij volgende schermgroottes wil ik een verandering zien:
800 px, 620px, 520px, 420px en 320px.

Zorg ook voor een responsive font, zodat je bij schermen van 520,420 en 320 de fontsize
aanpast.

```html

	body {
      background-color: lightgrey;
      
}

.kubus {
      width: 600px;
      height: 600px;
      background-color: yellow;
      margin: 50px auto 10px auto;
}

p {
      width: 500px;
      margin: auto;
      text-align: center; 
      font-family: helvetica;
      color: #888;
      font-size: 0.8em;
}

h2 {
      font-family: helvetica;
      font-size: 2em;
      margin: 150px auto;
      width: 90px;
      text-align: center;
      display: none;
}

```

De html code:

```html

<body>

		<div class="kubus"></div>
		<h2>Game Over :-)</h2>
		<p>
			* Ik ben responsive. Ontdek het door het scherm kleiner en groter te maken
		</p>

	</body>

```



