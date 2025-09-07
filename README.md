[index.html](https://github.com/user-attachments/files/22192520/index.html)
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pete Thinkful</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/8.0.1/normalize.min.css">
  <link href="style.css" rel="stylesheet" type="text/css">
</head>

<body>
  <h1>
    Pete Thinkful  Artist
  </h1>
  <nav>
  <a href="about.html">About</a>
  <a href="portfolio.html">Portfolio</a>
  <a href="contact.html">Contact</a>
    </nav>
  
<br>
  <main>
    <div>
      <h2>About</h2>
      <br>
      <h3>
        Hi! I'm Pete Thinkful
      </h3>
      <article>
        <div>
          <img class="image-circle" src="images/pete-thinkful.png" alt="Pete Thinkful">
        
              <p>
        I'm an artist living in Denver,Colorado.
      </p>
      <p>
        As an artist, I'm interested in:</p>
        <ul>
         <li> Producing abstract art</li>
        <li>Creating street graffiti art</li>
    <li>Connecting with like-minded artists</li>
        </ul>
          <p>
            Please feel free to take a look at my website and feel free to <a href="contact.html">contact me.</a>
          </p>
          
          <h3>
            Pete's Background
          </h3>
          
          <p>
            After graduating college, I became an art teacher and worked with beginners and professionals.I love art and my works haave been featured in major art galleries across the globe.
          </p>
          <p>
            If you're looking to hire an artist or if you're an artist looking for collaboration for your next project, please reach out! I'm so excited to work with other artists to create new art.
          </p>
      
        
        
        </div>
        
      </article>

      <hr>
      <h3>
        Portfolio
      </h3>
      <br>
      <h4>
        Abstract Art
      </h4>
      <article>
        <div>
          <img src="images/abstract-red.png" alt="Abstract Red">
          <p>
            Vaporwave wayfares heirloom neutra disrupt. Activated charcoal waistcoat scenester hell of.
          </p>
        </div>
        <div>
          <h4>
            Spiral Zany
          </h4>
          <img src="images/spiral-zany.png" alt="Spiral Zany">

          <p>
            Sriracha portland taxidermy cronut messenger bag, vegan distillery. Vaporwave kickstarter air plant mumblecore food truck.
          </p>
        </div>
        <div>
          <h4>
            Melted Rainbow
          </h4>
          <img src="images/melted-rainbow.png" alt="Melted Rainbow">
          <p>
            Edison bulb single-origin coffee snackwave, actually ennui locavore shabby chic forage.
          </p>
        </div>
      </article>

      <hr>

      <h3>
        Contact
      </h3>
      <p>
        I'd love to hear from you! Please feel free to contact or follow me:
      </p>
        <ol>
          <li><a href="https://linkedin.com/">LinkedIn</a></li>
          <li><a href="https://instagram.com/">Instagram</a></li>
          <li><a href= "https://pinterest.com/">Pinterest</a></li>
        </ol>
      
    </div>
  </main>

  <!-- Footer section -->
  <footer>
    <p>© Pete Thinkful. All rights reserved.</p>
  </footer>
</body>

</html>



[style.css](https://github.com/user-attachments/files/22192521/style.css)
/* The @import rule below imports the Playfair Display and Source Sans Pro fonts into the stylesheet. You don't have to edit this line.*/
@import url("https://fonts.googleapis.com/css2?family=Playfair+Display&family=Source+Sans+Pro:wght@400&display=swap");
body{background-color:#ffffe0}
body
nav{
  text-align: center;
}
h1{
  text-align:center;
  display: block;
  margin: 0 auto;
  color: #003049;
  font-family: "Playfair Display", Tahoma, Geneva, Verdana, sans-serif;
  padding: 40px;
}
ul{
  text-align: left;
}

main h2, h3, h4 {
  color: #003049;
  margin: 0 auto;
  text-align: center;
  font-family: "Playfair Display", Times, serif;
}
main p{
  color: #003049;
  text-align:left
}
a:link { color:blue;}
a:visited {color:red}
a:hover {color:green}
a:active {color:pink}


article {
  padding: 50px 0;
}

article div {
  text-align: center;
  width: 100%;
}

p {
  line-height: 1.5;
}

/* The div container constrains the content width within the main container to 600px */
div {
  margin: auto;
  width: 600px;
}

img {
  width: 100%;
  max-width: 200px;
  height: auto;
}

hr {
  border: 1px solid black;
}

/* Add your solution below */

.image-circle { 
  border-radius: 50%;
  border: 2px solid #003049;
               
}

