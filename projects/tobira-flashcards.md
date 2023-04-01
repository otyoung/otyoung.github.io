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
    <title>White Rectangle with Japanese Text</title>
    <style>
      /* CSS to style the white rectangle */
      .white-rectangle {
        background-color: white;
        color: black;
        font-size: 5vw;
        text-align: center;
        /* position: absolute; */
        /* top: 50%; */
        /* left: 50%; */
        /* transform: translate(-50%, -50%); */
        width: 80%;
        height: 80%;
        display: flex;
        justify-content: center;
        align-items: center;
      }
    </style>
  </head>
  <body>
    <div class="white-rectangle">
      飛ぶ
    </div>
    <script>
      // JavaScript to scale the white rectangle
      const whiteRectangle = document.querySelector('.white-rectangle');
      const resizeRectangle = () => {
        const w = window.innerWidth;
        const h = window.innerHeight;
        const rectangleWidth = w * 0.8;
        const rectangleHeight = h * 0.8 - 300;
        whiteRectangle.style.width = rectangleWidth + 'px';
        whiteRectangle.style.height = rectangleHeight + 'px';
      };
      window.addEventListener('resize', resizeRectangle);
      resizeRectangle();
    </script>
  </body>
</html>