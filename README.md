<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Work's Best Friend</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #f6f8fb;
      color: #1a1a1a;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      text-align: center;
      padding: 2rem;
    }
    .container {
      max-width: 600px;
      background: white;
      padding: 2.5rem;
      border-radius: 16px;
      box-shadow: 0 10px 20px rgba(0,0,0,0.08);
    }
    h1 {
      margin-bottom: 0.5rem;
      font-size: 2rem;
    }
    p {
      margin: 1rem 0;
      line-height: 1.6;
      color: #555;
    }
    input[type="email"] {
      padding: 0.75rem 1rem;
      width: 80%;
      border: 1px solid #ccc;
      border-radius: 8px;
      font-size: 1rem;
      margin-top: 1rem;
    }
    button {
      margin-top: 1rem;
      padding: 0.75rem 1.5rem;
      background-color: #3778f0;
      color: white;
      border: none;
      border-radius: 8px;
      font-size: 1rem;
      cursor: pointer;
      transition: background-color 0.3s;
    }
    button:hover {
      background-color: #265ed6;
    }
    form {
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    .footer {
      margin-top: 2rem;
      font-size: 0.9rem;
      color: #aaa;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Work’s Best Friend</h1>
    <p><strong>Simple, effective help for businesses that need it — when they need it.</strong></p>
    <p>We’re a flexible agency helping business owners with marketing and more.<br>
       With tailored services to your real needs.<br>
       Think of us as your on-call business partner.</p>
    <form action="mailto:jay@worksbestfriend.com" method="POST" enctype="text/plain">
      <label for="email">💬 Interested in working with us?</label>
      <input type="email" id="email" name="email" placeholder="Enter your email" required />
      <button type="submit">Send</button>
    <form action="https://formsubmit.co/jay@worksbestfriend.com" method="POST">
  <label for="email">💬 Interested in working with us?</label>
  <input type="email" id="email" name="email" placeholder="Enter your email" required />
  <button type="submit">Send</button>

  <!-- Optional hidden fields -->
  <input type="hidden" name="_subject" value="New Lead from Work's Best Friend!" />
  <input type="hidden" name="_captcha" value="false">
  <input type="hidden" name="_template" value="table">
</form>
    <div class="footer">© 2025 Work’s Best Friend</div>
  </div>
</body>
