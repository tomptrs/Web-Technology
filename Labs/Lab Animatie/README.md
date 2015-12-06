# Web-Technology - Lab Animatie

### Deel 1: De header

Maak een header aan die er als volgt uit ziet:

![header](/header.PNG)


De h1 tag heeft kleurcode: color:#0cb5db;
De div met klasse “opening” heeft kleurcode: background: #a9a8a8; , en een width en height van 200px met bijhorende border-radius.
Vervolgens schrijf je een animatie zodat het koffiekopje oneindig doorheen de andere afbeelding schuift (de afbeelding start met 5s delay, en duurt 10 seconden.

![header Finished](/headerFinish.PNG)


### Deel 2: Navigatie

Schrijf CSS en HTML code voor onderstaande navigatie:

![navigatie](/navigatie.PNG)

Voeg achter de navigatie HTML code volgende snippet toe:
<section class="vs">
	<div>
		<h3>VS</h3>
	</div>
</section>

Nu schrijf je een animatie zodat deze .vs div van boven naar beneden (=plaats waar hij origineel staat) valt: 
Tip: naar boven is een negatieve Y-waarde (translateY)


![navigatie_finished](/navigatie_finished.PNG) 

### Deel 3: animatie advanced

De laatste animatie die je gemaakt hebt, om de VS-div te laten vallen, willen we enkel starten indien op een hyperlink geklikt is. Hiervoor schrijf je javascript + jQuery code in script.js
Om onderstaande code te laten werken, moet je in je HTML bestand refereren naar de jQuery library:
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>


$(".vs").on('webkitAnimationEnd', function() {
		$(".vs").removeClass("bounce-in");
    });

