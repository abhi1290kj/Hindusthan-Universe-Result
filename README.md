
<html lang="hi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Sarkari Alert - सरकारी रिजल्ट</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f4f4f4;
      color: #111;
    }
    header {
      background: #800000;
      color: white;
      text-align: center;
      padding: 20px 10px;
    }
    header h1 {
      margin: 0;
      font-size: 2em;
    }
    header p {
      margin-top: 5px;
      font-size: 0.95em;
    }
    nav {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      background: #990000;
    }
    nav a {
      padding: 12px 16px;
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      background: #b30000;
    }
    .ticker {
      background: #111;
      color: #ffcc00;
      padding: 10px;
      overflow: hidden;
      white-space: nowrap;
    }
    .ticker span {
      display: inline-block;
      padding-left: 100%;
      animation: marquee 15s linear infinite;
    }
    @keyframes marquee {
      0% { transform: translateX(0); }
      100% { transform: translateX(-100%); }
    }
    .container {
      max-width: 1000px;
      margin: auto;
      padding: 20px;
      background: #fff;
      box-shadow: 0 0 8px rgba(0,0,0,0.1);
    }
    .search-box {
      display: flex;
      margin-bottom: 20px;
    }
    .search-box input {
      flex: 1;
      padding: 10px;
      font-size: 1em;
      border: 1px solid #ccc;
      border-radius: 4px 0 0 4px;
    }
    .search-box button {
      padding: 10px 20px;
      border: none;
      background: #800000;
      color: #fff;
      font-weight: bold;
      cursor: pointer;
      border-radius: 0 4px 4px 0;
    }
    h2 {
      border-left: 5px solid #800000;
      padding-left: 10px;
      margin-top: 30px;
      color: #800000;
    }
    ul {
      list-style: none;
      padding: 0;
    }
    ul li {
      margin: 10px 0;
      padding: 10px;
      background: #f9f9f9;
      border-left: 4px solid #800000;
      transition: 0.3s;
    }
    ul li:hover {
      background: #fff2f2;
    }
    ul li a {
      text-decoration: none;
      color: #111;
      font-weight: bold;
    }
    .ads {
      text-align: center;
      margin: 20px 0;
      padding: 10px;
      background: #fafafa;
      border: 1px dashed #ccc;
    }
    footer {
      background: #800000;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 40px;
    }
    @media(max-width: 600px) {
      nav {
        flex-direction: column;
        align-items: center;
      }
      .search-box {
        flex-direction: column;
      }
      .search-box input, .search-box button {
        width: 100%;
        border-radius: 4px;
        margin-bottom: 10px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Sarkari Alert</h1>
    <p>भारत की सभी सरकारी नौकरियों की जानकारी एक जगह</p>
  </header>

  <nav>
    <a href="#">🏠 होम</a>
    <a href="#">📝 जॉब्स</a>
    <a href="#">📥 एडमिट कार्ड</a>
    <a href="#">📊 रिजल्ट</a>
    <a href="#">📚 सिलेबस</a>
    <a href="#">📢 Answer Key</a>
  </nav>

  <div class="ticker">
    <span>SSC CGL 2025 फॉर्म शुरू | UP Police भर्ती 2025 | CTET एडमिट कार्ड जारी | SSC GD रिजल्ट घोषित | RRB NTPC सिलेबस अपडेट | ...</span>
  </div>

  <div class="container">
      <!-- Search -->
  <div class="search-container">
    <input type="text" placeholder="सरकारी नौकरी खोजें...">
    <button type="submit">🔍 खोजें</button>
  </div>

</body>
</html>

