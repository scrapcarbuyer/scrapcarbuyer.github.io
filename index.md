---
title: "My Blog"
---

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Blog</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
    }
    header {
      background: #f8f8f8;
      padding: 10px 20px;
      display: flex;
      align-items: center; /* ✅ Vertical alignment */
      border-bottom: 1px solid #ddd;
    }
    header img {
      height: 50px;
      margin-right: 15px; /* ✅ Space between logo and text */
    }
    header h1 {
      font-size: 22px;
      margin: 0;
      color: #333;
    }
    main {
      padding: 20px;
    }
    main img {
      display: block;
      margin: 20px auto;
      max-width: 150px;
    }
  </style>
</head>
<body>
  <header>
    <img src="assets/images/logo.png" alt="Logo">
    <h1>My Blog</h1>
  </header>
  <main>
    <h2>Welcome</h2>
    <p>Welcome to my blog! Here you’ll find posts, updates, and guides.</p>

    <h2>Posts</h2>
    <ul>
      <li><a href="#">Post 1: Getting Started</a></li>
      <li><a href="#">Post 2: Latest Updates</a></li>
      <li><a href="#">Post 3: Tips and Tricks</a></li>
    </ul>
  </main>
</body>
</html>
