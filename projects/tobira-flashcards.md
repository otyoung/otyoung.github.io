---
layout: project
title: Tobira Flashcards
permalink: /projects/tobira-flashcards
img: "/assets/images/rrPic.png"
filename: tobira-research.md
description: Practice flashcards for vocabulary from the Tobira Japanese textbooks. Can choose cards based on chapter, and can choose what is on each side of the flashcard from Kanji, the kana reading, and the English meaning.
---

<!-- <html lang="en">
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<link rel="stylesheet" href="">

<body>

<div class="">
 <h1>This is Rodrick's Rangers</h1>
 <p>This is a paragraph.</p>
 <p>This is another paragraph.</p>
</div>

</body>
</html> -->
<html>
<head>
	<title>Bit to Integer Converter</title>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
	<label for="bit1">Bit 1</label>
	<input type="checkbox" id="bit1" value="1">
	<br>
	<label for="bit2">Bit 2</label>
	<input type="checkbox" id="bit2" value="2">
	<br>
	<button onclick="convertToInteger()">Go</button>

	<script>
		function convertToInteger() {
			let bit1 = document.getElementById("bit1");
			let bit2 = document.getElementById("bit2");
			let bits = 0;
			if (bit1.checked) {
				bits += 1;
			}
			if (bit2.checked) {
				bits += 2;
			}
			alert(bits);
		}
	</script>
</body>
</html>
