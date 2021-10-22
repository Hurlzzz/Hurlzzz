# Hello there, I'm [Hurlzzz](https://github.com/Hurlzzz "To my profile") #

## :book: 𝙰𝚋𝚘𝚞𝚝 𝙼𝚎 ##

- Aspiring Developer :desktop_computer:
- Mediocre Fantasy Baseball Player :baseball:
- Former Guitar Hero :guitar:
- Collector of Expensive Carboard :flower_playing_cards:	
- Currently learning how to use GitHub :eyes:
- I’m looking to eventually **Rule the World** :earth_americas:

![Guitar Hero](https://c.tenor.com/HSMSRNtJYzIAAAAC/darth-vader-star-wars.gif)

## :speech_balloon:	Other Information ##

The purpose of this is to fulfill a class requirement, but to also learn a little more about how things work in the developement space with Github.
I don't have any previous experience with sharing work like this so it's interesting to see the processes behind it. 
Below you'll see a very basic *FizzBuzz* program I created to share for this project.

```
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Fizz Buzz</title>
<script>

function fizzbuzz() {
	var display = document.getElementById('display');
	var displayHTML = "";
	for (i = 1; i < 101; i++) {
		if (i % 15 == 0){
			displayHTML += "<p>" + "FizzBuzz" + "</p>";
		}
		else if (i % 3 == 0) {
			displayHTML += "<p>" + "Fizz" + "</p>";
		}
		else if (i % 5 == 0) {
			displayHTML += "<p>" + "Buzz" + "</p>";
		}
		else {
			displayHTML += "<p>" + i + "</p>";
		}
			
	}
	display.innerHTML = displayHTML
}

</script>

</head>

<body onload="fizzbuzz()">
<div id="display">

</div>
</body>

</html>
```

<!---
Hurlzzz/Hurlzzz is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
