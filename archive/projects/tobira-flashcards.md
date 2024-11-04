---
layout: project
title: Tobira Flashcards
permalink: /projects/tobira-flashcards
img: "/assets/images/rrPic.png"
filename: tobira-research.md
description: Practice flashcards for vocabulary from the Tobira Japanese textbooks. Can choose cards based on chapter, and can choose what is on each side of the flashcard from Kanji, the kana reading, and the English meaning.
---

<html>
<head>
	<title>Japanese Flashcards</title>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
    {
        box-sizing: border-box;
    }
    /* Set additional styling options for the columns */
    .column {
    float: left;
    }
    .left {
    width: 50%;
    }
    .right {
    width: 50%;
    }
    .row:after {
    content: "";
    display: table;
    clear: both;
    }
    </style>
</head>
<body>
    <div class="column left">
        <emph>Tobira: Beginning Japanese</emph>
        <br>
	    <label for="bAll">Whole Textbook</label>
	    <input type="checkbox" id="bAll" value="0">
	    <br>
	    <label for="bCh1-5">Chapters 1-5</label>
	    <input type="checkbox" id="bCh1-5" value="1">
	    <br>
	    <label for="bCh6-10">Chapter 6-10</label>
	    <input type="checkbox" id="bCh6-10" value="2">
	    <br>
	    <label for="bCh11-15">Chapter 11-15</label>
	    <input type="checkbox" id="bCh11-15" value="3">
	    <br>
	    <label for="bCh16-20">Chapter 16-20</label>
	    <input type="checkbox" id="bCh16-20" value="4">
	    <br>
        <emph>Tobira: Gateway to Advanced Japanese</emph>
        <br>
	    <label for="iAll">Whole Textbook</label>
	    <input type="checkbox" id="iAll" value="5">
	    <br>
	    <label for="iCh1">Chapter 1</label>
	    <input type="checkbox" id="iCh1" value="6">
	    <br>
	    <label for="iCh2">Chapter 2</label>
	    <input type="checkbox" id="iCh2" value="7">
	    <br>
	    <label for="iCh3">Chapter 3</label>
	    <input type="checkbox" id="iCh3" value="8">
	    <br>
	    <label for="iCh4">Chapter 4</label>
	    <input type="checkbox" id="iCh4" value="9">
	    <br>
	    <label for="iCh5">Chapter 5</label>
	    <input type="checkbox" id="iCh5" value="10">
	    <br>
	    <label for="iCh6">Chapter 6</label>
	    <input type="checkbox" id="iCh6" value="11">
	    <br>
	    <label for="iCh7">Chapter 7</label>
	    <input type="checkbox" id="iCh7" value="12">
	    <br>
	    <label for="iCh8">Chapter 8</label>
	    <input type="checkbox" id="iCh8" value="13">
	    <br>
	    <label for="iCh9">Chapter 9</label>
	    <input type="checkbox" id="iCh9" value="14">
	    <br>
	    <label for="iCh10">Chapter 10</label>
	    <input type="checkbox" id="iCh10" value="15">
	    <br>
	    <label for="iCh11">Chapter 11</label>
	    <input type="checkbox" id="iCh11" value="16">
	    <br>
	    <label for="iCh12">Chapter 12</label>
	    <input type="checkbox" id="iCh12" value="17">
	    <br>
	    <label for="iCh13">Chapter 13</label>
	    <input type="checkbox" id="iCh13" value="18">
	    <br>
	    <label for="iCh14">Chapter 14</label>
	    <input type="checkbox" id="iCh14" value="19">
	    <br>
	    <label for="iCh15">Chapter 15</label>
	    <input type="checkbox" id="iCh15" value="20">
	    <br>
    </div>
    <div class="column right">
        <emph>Front Side</emph>
        <br>
	    <label for="frontKanji">Kanji</label>
	    <input type="checkbox" id="frontKanji" value="1">
	    <br>
	    <label for="frontKana">Kana</label>
	    <input type="checkbox" id="frontKana" value="2">
	    <br>
	    <label for="frontEnglish">English</label>
	    <input type="checkbox" id="frontEnglish" value="3">
	    <br>
        <emph>Back Side</emph>
        <br>
	    <label for="backKanji">Kanji</label>
	    <input type="checkbox" id="backKanji" value="1">
	    <br>
	    <label for="backKana">Kana</label>
	    <input type="checkbox" id="backKana" value="2">
	    <br>
	    <label for="backEnglish">English</label>
	    <input type="checkbox" id="backEnglish" value="3">
	    <br>
    </div>
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
