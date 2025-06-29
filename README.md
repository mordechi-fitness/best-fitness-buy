<!DOCTYPE html>
<html lang="he">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>מוצרי כושר מומלצים</title>
  <link href="https://fonts.googleapis.com/css2?family=Heebo:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Heebo', sans-serif;
      margin: 0;
      padding: 0;
      direction: rtl;
      background-color: #f2f2f2;
      color: #333;
    }
    header {
      background-color: #0d6efd;
      color: white;
      padding: 2rem;
      text-align: center;
    }
    section.products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 1.5rem;
      padding: 2rem;
    }
    .product {
      background: white;
      padding: 1rem;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      text-align: center;
    }
    .product img {
      max-width: 100%;
      height: 180px;
      object-fit: contain;
    }
    .product h3 {
      margin: 1rem 0 0.5rem;
    }
    .product a {
      display: inline-block;
      margin-top: 0.5rem;
      background-color: #28a745;
      color: white;
      padding: 0.5rem 1rem;
      border-radius: 5px;
      text-decoration: none;
    }
    footer {
      background-color: #333;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    .contact {
      background: #ffffff;
      padding: 2rem;
      max-width: 600px;
      margin: auto;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    .contact input, .contact textarea {
      width: 100%;
      padding: 0.5rem;
      margin: 0.5rem 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    .contact button {
      background: #0d6efd;
      color: white;
      padding: 0.7rem 1.2rem;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <header>
    <h1>המוצרים המומלצים ביותר לכושר ובריאות</h1>
    <p>בחרנו עבורך את המוצרים הטובים ביותר שאתה יכול לשווק ולהרוויח מהם</p>
  </header>

  <section class="products">
    <div class="product">
      <img src="https://via.placeholder.com/300x180" alt="מוצר כושר 1">
      <h3>משקולות יד איכותיות</h3>
      <p>סט משקולות אידיאלי לאימוני כוח בבית</p>
      <a href="#">לרכישה >> </a>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/300x180" alt="מוצר כושר 2">
      <h3>רצועות התנגדות מקצועיות</h3>
      <p>מושלם לאימון בכל מקום</p>
      <a href="#">לרכישה >> </a>
    </div>
    <!-- אפשר להוסיף כאן עוד מוצרים -->
  </section>

  <section class="contact">
    <h2>צור קשר</h2>
    <form>
      <input type="text" placeholder="שם מלא" required>
      <input type="email" placeholder="אימייל" required>
      <textarea rows="4" placeholder="ההודעה שלך"></textarea>
      <button type="submit">שלח</button>
    </form>
  </section>

  <footer>
    <p>© כל הזכויות שמורות - אתר שיווק כושר 2025</p>
    <p>
      <a href="#" style="color:white; text-decoration:underline">פייסבוק</a> |
      <a href="#" style="color:white; text-decoration:underline">אינסטגרם</a>
    </p>
  </footer>
</body>
</html>
