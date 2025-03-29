<!DOCTYPE html>
<html>

<head>
    <title>Webbie - Fitness Gym in San Antonio</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <header>
        <h1>Fitness Gyms in San Antonio</h1>
    </header>

    <main>
        <section>
      <a href="#">
      <button>Gentleman's Fitness Gym</button>
        </a>
          <img class="gym-img" src="/storage/emulated/0/DCIM/Facebook/FB_IMG_1742546884644.jpg">
      <p>Gentleman's Fitness Gym • Julo, San Antonio, Nueva Ecija</p>
        </section>

        <section>
        <a href="#">
      <button>C16 Muscle Labz Fitness Gym</button>
       </a>
     <img class="gym-img" src="/storage/emulated/0/DCIM/Facebook/FB_IMG_1742554450040.jpg">
     <p>C16 Muscle Labz Fitness Gym • Poblacion, San Antonio, Nueva Ecija</p>
        </section>

        <section>
   <a href="#">
  <button>M1 Fitness Gym</button>
   </a>
     <img class="gym-img" src="/storage/emulated/0/DCIM/Facebook/FB_IMG_1742554780137.jpg">
     <p>M1 Fitness Gym • Poblacion, San Antonio, Nueva Ecija</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Fitness Gym. All Rights Reserved.</p>
    </footer>
</body>

</html>

CSS

* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;   
}

body {
    font-family: Arial, sans-serif;
    background-color: lightgray;
    color: darkslategray;
    line-height: 1;
    margin-bottom: 10px;
}

header {
    background-color: black;
    color: white;
    padding: 20px;
    text-align: center;
}

main {
    display: grid;
    grid-template-columns: repeat (autofill);
    gap: 20px;
    padding: 20px;
    max-width: 1200px;
    margin: 0 auto;
}

section {
    background-color: white;
    border-radius: 8px;
    overflow: hidden;
    text-align: center;
    padding: 10px;
}

button {
    background-color: orange;
    color: white;
    border: none;
    padding: 10px 20px;
    font-size: 16px;
    border-radius: 5px;
    margin: 10px 0;
}
.gym-img {
    width: 100%;
    height: auto;
    border-radius: 5px;
    margin-bottom: 10px;
}

p {
    font-size: 14px;
    color: dimgray;
}

footer {
    margin-top:10px;
    background-color: black;
    color: white;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}
