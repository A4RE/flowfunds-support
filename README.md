<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Поддержка Flow Funds</title>
  <style>
    :root {
      --gradient-light: linear-gradient(135deg, #0F5132, #1A7F56);
      --gradient-dark: linear-gradient(135deg, #0A2B1D, #145B3A);
    }

    body {
      margin: 0;
      padding: 0;
      min-height: 100vh;
      font-family: -apple-system, BlinkMacSystemFont, "SF Pro Text", sans-serif;
      background: var(--gradient-light);
      color: #ffffff;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      transition: background 0.3s ease;
    }

    @media (prefers-color-scheme: dark) {
      body {
        background: var(--gradient-dark);
      }
    }

    h1 {
      font-size: 2.2em;
      font-weight: 700;
      margin-bottom: 0.4em;
    }

    p {
      font-size: 1.1em;
      max-width: 500px;
      line-height: 1.6;
      opacity: 0.9;
    }

    a {
      color: #9AE6B4;
      text-decoration: none;
      font-weight: 600;
    }

    .icon {
      width: 96px;
      height: 96px;
      border-radius: 20px;
      margin-bottom: 16px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.25);
    }

    footer {
      margin-top: 2em;
      font-size: 0.9em;
      opacity: 0.7;
    }
  </style>
</head>
<body>
  <img src="https://a4re.github.io/flowfunds-support/icon.png" alt="Flow Funds icon" class="icon" onerror="this.style.display='none'">
  <h1>Поддержка Flow Funds</h1>
  <p>Если у вас возникли вопросы или предложения по приложению <strong>Flow Funds</strong>, свяжитесь с нами:</p>
  <p><a href="mailto:aakoval01@gmail.com">support@flowfunds.app</a></p>
  <p>Мы стараемся отвечать в течение 24 часов.</p>
  <footer>© 2025 Flow Funds. Все права защищены.</footer>
</body>
</html>
