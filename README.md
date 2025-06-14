# upskill-motivation-site
this site asists alot in changing ones mentality and motivates one to do more than he/she has done

<!-- 
  Author: Allan Mulewa Mukare (Proper Upskill Format)
  Date: June 11, 2025
-->

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Motivation & Wellness</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header>
    <h1>🧠 Motivation & Mental Wellness</h1>
    <p>Boost your mindset and stay focused with daily inspiration and growth tools.</p>
  </header>

  <nav>
    <ul>
      <li><a href="index.html">🏠 Home</a></li>
      <li><a href="study.html">📚 Study Hub</a></li>
      <li><a href="freelancers.html">🤝 Freelancers</a></li>
    </ul>
  </nav>

  <section>
    <h2>🌞 Daily Motivational Quote</h2>
    <p id="quote-box">Loading quote...</p>
  </section>

  <section>
    <h2>💪 Mindset Tips</h2>
    <ul>
      <li>Start your day with positive affirmations.</li>
      <li>Set small daily goals and reward yourself.</li>
      <li>Take breaks and breathe – don’t burn out.</li>
      <li>Surround yourself with uplifting content.</li>
    </ul>
  </section>

  <section>
    <h2>📖 Recommended Books</h2>
    <ol>
      <li><a href="https://www.amazon.com/Atomic-Habits-James-Clear/dp/0735211299" target="_blank">Atomic Habits</a> – build strong habits and break bad ones.</li>
      <li><a href="https://www.amazon.com/Magic-Thinking-Big-David-Schwartz/dp/0671646788" target="_blank">The Power of Thinking Big</a> – grow your belief and confidence.</li>
      <li><a href="https://www.amazon.com/Through-Looking-Glass-Lewis-Carroll/dp/1503222683" target="_blank">Wonderland</a> – a creative journey through imagination.</li>
    </ol>
  </section>

  <footer>
    <p>Made by Allan | © 2025 Upskill Portal</p>
  </footer>

  <!-- JavaScript for Random Quote -->
  <script>
    const quotes = [
      "Success is not final, failure is not fatal: It is the courage to continue that counts. – Winston Churchill",
      "Believe you can and you're halfway there. – Theodore Roosevelt",
      "Start where you are. Use what you have. Do what you can. – Arthur Ashe",
      "The only way to do great work is to love what you do. – Steve Jobs",
      "Push yourself, because no one else is going to do it for you.",
      "It always seems impossible until it's done. – Nelson Mandela"
    ];

    const quoteBox = document.getElementById("quote-box");
    const randomIndex = Math.floor(Math.random() * quotes.length);
    quoteBox.innerText = quotes[randomIndex];
  </script>

</body>
</html>




