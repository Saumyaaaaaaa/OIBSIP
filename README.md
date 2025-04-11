//OIBSIP 
//LANDING PAGE
HTML Code

<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>The Sweet Spot</title>
  <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;600;800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="coffeestyle.css">
  <style>
    body {
      background-image: url('https://static.vecteezy.com/system/resources/previews/028/112/651/non_2x/a-cup-of-coffee-with-book-and-pen-on-the-wooden-table-ai-generated-free-photo.jpg');
      background-repeat: no-repeat;
      background-attachment: fixed;  
      background-size: cover;
    }
    </style>
</head>

<body>
  <header>
    <h1>The Sweet Spot</h1>
    <p>Your cozy corner for stories and sips - where books meet brews</p>
    <button class="btn">Visit Us Today</button>
  </header>

  <section class="intro">
    <h2>Your Literary Escape.</h2>
    <p> At The Sweet Spot, we’re all about words and people, as we combine the magic of a carefully selected book shop with the warmth of an artisan cafe; three bookstores and two coffee shops together we bring the best of both worlds to booklovers and coffee drinkers alike.</p>
  </section>

  <section class="tea">
    <h1> Positivi'tea' in every sip</h1>
  </section>

  <section>
    <div class="features">
      <div class="feature">
        <img src="https://img.icons8.com/color/96/book-shelf.png" alt="Books Galore">
        <h3>Curated Book Collection</h3>
        <p>Fiction, non-fiction, poetry, and indie titles selected by your fellow book lovers.</p>
      </div>

      <div class="feature">
        <img src="https://ouch-cdn2.icons8.com/2S8JKxvg1DbOZUEjtbGYNjuSYbQ8xoWhmDT4yEx_JTw/rs:fit:456:456/czM6Ly9pY29uczgu/b3VjaC1wcm9kLmFz/c2V0cy9zdmcvODk5/L2Q2MDE0OGIxLTYx/NzgtNGFmYS05NGY5/LTRlNzEzOGJmODli/Ny5zdmc.png" alt="Coffee Vibes">
        <h3>Specialty Café</h3>
        <p>Enjoy artisan coffee, cozy teas, and treats while immersed in a literary atmosphere.</p>
      </div>

      <div class="feature">
        <img src="https://img.icons8.com/color/96/open-book--v2.png" alt="Events">
        <h3>Live Readings & Events</h3>
        <p>Join bookclubs, author readings, and writing workshops they inspire and they're out there to connect.</p>
      </div>
    </div>
  </section>

  <section>
    <div class="about">
      <h3>ABOUT US:</h3>
      <p>☕ The theme of The Sweet Spot is to develop a culture where people connect to grow and recreate themselves.<br>☕ Building Cafe culture and bringing together creative people over a coffee.</p>
    </div>
  </section>

  <section class="map-section">
    <h2>Visit Us at Our Cozy Location</h2>
    <img src="https://img.icons8.com/color/500/marker.png" alt="Location">
    <div class="stats">
      <div><strong>9,000+</strong> Books</div>
      <div><strong>90+</strong> Coffee Varieties, Tea and Shakes</div>
      <div><strong>7 Days</strong> Open Weekly</div>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Chapter & Brew. All rights reserved.</p>
  </footer>
</body>

</html>

CSS Code

    body {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Outfit', sans-serif;
    }

    header {
      background-color: rgba(255, 182, 193, 0.5);
      padding: 140px 20px 100px;
      text-align: center;
      position: relative;
      overflow: hidden;
      border-bottom-left-radius: 80px;
      border-bottom-right-radius: 80px;
      box-shadow: 0 20px 50px rgba(0, 0, 0, 0.05);
    }

    header h1 {
      font-size: 4rem;
      font-weight: 800;
      margin-bottom: 1rem;
      color: #1e293b;
    }

    header p {
      font-size: 2rem;
      margin-bottom: 40px;
      color: #334155;
    }

    .btn {
      background: #ec4899;
      color: #fff;
      padding: 16px 40px;
      border: none;
      border-radius: 9999px;
      font-weight: 600;
      font-size: 1.1rem;
      cursor: pointer;
      transition: all 0.3s ease;
      box-shadow: 0 10px 20px rgba(236, 72, 153, 0.4);
    }

    .btn:hover {
      background-color: #db2777;
      transform: translateY(-3px);
    }

    section {
      padding: 100px 20px;
      max-width: 1200px;
      margin: 0 auto;
    }

    .intro {
      text-align: center;
      margin-bottom: 10px;
    }

    .intro h2 {
      font-size: 3.9rem;
      margin-bottom: 10px;
      font-weight: 700;
      color: #8e939e;
    }

    .intro p {
      font-size: 2rem;
      color: #f7f8fa;
      max-width: 800px;
      margin: 0 auto;
    }

    .tea h1 {
      font-size: 6rem;
      color:#da5591;
      text-align: center;
      font-family: 'Brush Script MT', cursive;
    }

    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 60px;
      margin-top: 60px;
      margin-bottom: 30px;
    }

    .feature {
      background-color:rgba(191, 161, 233, 0.7);
      border-radius: 32px;
      padding: 50px 40px;
      text-align: center;
      box-shadow: 0 30px 50px rgba(0, 0, 0, 0.05);
      transition: all 0.3s ease;
    }

    .feature:hover {
      transform: translateY(-12px);
      box-shadow: 0 40px 60px rgba(0, 0, 0, 0.08);
    }

    .feature img {
      height: 90px;
      margin-bottom: 25px;
    }

    .feature h3 {
      font-size: 3rem;
      margin-bottom: 15px;
      font-weight: 700;
      color: #1f2937;
    }

    .feature p {
      font-size: 2.5rem;
      color: #ffffff;
    }

    .about h3 {
      font-size: 3.3rem;
      color:rgb(188, 95, 168);
    }

    .about p {
      font-size:2.5rem;
      color:rgb(176, 111, 144);
    }

    .map-section {
      background: linear-gradient(135deg, #ede9fe, #fef3c7);
      text-align: center;
      padding: 120px 20px;
      border-radius: 60px;
      margin-top: 100px;
      box-shadow: 0 30px 50px rgba(0, 0, 0, 0.03);
    }

    .map-section h2 {
      font-size: 2.5rem;
      margin-bottom: 40px;
      font-weight: 700;
      color: #1e293b;
    }

    .map-section img {
      max-width: 70px;
      height: auto;
      margin-bottom: 30px;
    }

    .stats {
      display: flex;
      justify-content: center;
      gap: 60px;
      font-size: 1.3rem;
      flex-wrap: wrap;
      color: #4b5563;
    }

    .stats div {
      font-weight: 700;
    }

    footer {
      background-color: #1f2937;
      color: #fff;
      text-align: center;
      padding: 50px 20px;
      border-top-left-radius: 60px;
      border-top-right-radius: 60px;
      margin-top: 80px;
      font-size: 1rem;
    }
