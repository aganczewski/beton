<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Art Gallery</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f4f4;
    }
    header {
      background: #333;
      color: #fff;
      padding: 1rem;
      text-align: center;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem;
      padding: 1rem;
    }
    .gallery img {
      width: 100%;
      height: auto;
      display: block;
      border-radius: 8px;
    }
    footer {
      background: #333;
      color: #fff;
      text-align: center;
      padding: 1rem;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>
  <header>
    <h1>My Art Gallery</h1>
  </header>
  <main>
    <section class="gallery">
      <img src="art1.jpg" alt="Art piece 1">
      <img src="art2.jpg" alt="Art piece 2">
      <img src="art3.jpg" alt="Art piece 3">
      <img src="art4.jpg" alt="Art piece 4">
      <img src="art5.jpg" alt="Art piece 5">
      <img src="art6.jpg" alt="Art piece 6">
    </section>
  </main>
  <footer>
    <p>&copy; 2025 My Art Gallery</p>
  </footer>
</body>
</html>
