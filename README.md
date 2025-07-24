<!DOCTYPE html>
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

    <div class="ads">
      <!-- AdSense Placeholder -->
      [यहां Google AdSense Code आएगा]
    </div>

    <h2>📝 लेटेस्ट जॉब्स</h2>
    <ul>
      <li><a href="#">SSC CGL 2025 ऑनलाइन फॉर्म – अभी आवेदन करें</a></li>
      <li><a href="#">UP Police कांस्टेबल भर्ती 2025 – 60,000 पद</a></li>
      <li><a href="#">रेलवे RRC ग्रुप D भर्ती – सभी ZONE में</a></li>
    </ul>

    <h2>📥 एडमिट कार्ड</h2>
    <ul>
      <li><a href="#">UPSC NDA 2 एडमिट कार्ड 2025 डाउनलोड करें</a></li>
      <li><a href="#">CTET जुलाई 2025 एडमिट कार्ड जारी</a></li>
    </ul>

    <h2>📊 रिजल्ट</h2>
    <ul>
      <li><a href="#">UP Board 10th/12th Result 2025 घोषित</a></li>
      <li><a href="#">SSC GD कांस्टेबल रिजल्ट 2025 देखें</a></li>
    </ul>

    <h2>📚 सिलेबस</h2>
    <ul>
      <li><a href="#">SSC CGL 2025 नया सिलेबस PDF</a></li>
      <li><a href="#">RRB NTPC CBT 2 सिलेबस</a></li>
    </ul>

    <h2>📢 Answer Key</h2>
    <ul>
      <li><a href="#">UP Police SI Answer Key 2025</a></li>
      <li><a href="#">SSC CHSL Tier 1 Answer Key</a></li>
    </ul>

  </div>

  <footer>
    © 2025 Sarkari Alert | सभी अधिकार सुरक्षित
  </footer>

  
  
  
  
  
  
  
  
  
  
  
  
  <h2>🗓️ लेटेस्ट अपडेट्स</h2>
    <ul>
      <li><strong>[24 जुलाई 2025]</strong> – <a href="#">SSC GD कांस्टेबल रिजल्ट घोषित</a></li>
      <li><strong>[23 जुलाई 2025]</strong> – <a href="#">CTET एडमिट कार्ड डाउनलोड करें</a></li>
      <li><strong>[22 जुलाई 2025]</strong> – <a href="#">UPSSSC PET 2025 नोटिफिकेशन जारी</a></li>
    </ul>

    <h2>🧭 महत्वपूर्ण लिंक</h2>
    <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 10px;">
      <a href="#" style="background:#ffe0b3; padding:10px; display:block; text-align:center; font-weight:bold;">All Govt Jobs</a>
      <a href="#" style="background:#e6f7ff; padding:10px; display:block; text-align:center; font-weight:bold;">Admit Card</a>
      <a href="#" style="background:#e6ffe6; padding:10px; display:block; text-align:center; font-weight:bold;">Result</a>
      <a href="#" style="background:#f9e6ff; padding:10px; display:block; text-align:center; font-weight:bold;">Answer Key</a>
      <a href="#" style="background:#fff2e6; padding:10px; display:block; text-align:center; font-weight:bold;">Syllabus</a>
    </div>

    <h2>📢 नोटिफिकेशन पैनल</h2>
    <ul>
      <li><a href="#">Bihar Police Sub Inspector 2025 Notification Out – 2300 Posts</a></li>
      <li><a href="#">Delhi DSSSB TGT PGT Teacher Bharti 2025 – Apply Online</a></li>
      <li><a href="#">Navy SSR/MR Agniveer 2025 Batch – Notification & Apply Link</a></li>
    </ul>

    <h2>🎯 फिल्टर द्वारा खोजें</h2>
    <div style="display:flex; flex-wrap:wrap; gap:10px;">
      <select>
        <option>शैक्षणिक योग्यता</option>
        <option>10वीं</option>
        <option>12वीं</option>
        <option>Graduation</option>
        <option>Diploma/ITI</option>
      </select>
      <select>
        <option>राज्य</option>
        <option>उत्तर प्रदेश</option>
        <option>बिहार</option>
        <option>राजस्थान</option>
        <option>मध्यप्रदेश</option>
      </select>
      <select>
        <option>श्रेणी</option>
        <option>Railway Jobs</option>
        <option>Bank Jobs</option>
        <option>Defence</option>
        <option>SSC</option>
      </select>
    </div>

    <br><br>

    <div class="ads">
      [AdSense Banner Placeholder]
    </div>

    <button onclick="scrollToTop()" style="position:fixed; bottom:20px; right:20px; padding:10px 15px; background:#800000; color:white; border:none; border-radius:5px; cursor:pointer;">⬆️ Top</button>
  
  
  <script>
  function scrollToTop() {
    window.scrollTo({ top: 0, behavior: 'smooth' });
  }
</script>
  
  
  
  
  
  
  <!-- Auto Popup -->
<div id="popup" style="display:none; position:fixed; bottom:20px; right:20px; background:#fff3cd; border:1px solid #ffeeba; padding:15px; border-radius:10px; box-shadow:0 0 10px rgba(0,0,0,0.2); z-index:9999;">
  📢 <strong>UP Police Form</strong> भरें आज ही! <br>
  <a href="#" style="color:#800000;">Apply Now</a>
  <span onclick="document.getElementById('popup').style.display='none'" style="cursor:pointer; float:right; font-weight:bold;">✖</span>
</div>

<script>
  setTimeout(() => {
    document.getElementById('popup').style.display = 'block';
  }, 3000); // Show after 3 seconds
</script>



<p id="datetime" style="text-align:center; font-size:0.9em; margin-top:10px;"></p>

<script>
  function updateTime() {
    const now = new Date();
    document.getElementById("datetime").innerText = "⏰ " + now.toLocaleString("hi-IN");
  }
  setInterval(updateTime, 1000);
</script>



<!-- WhatsApp / Telegram Floating -->
<a href="https://wa.me/91XXXXXXXXXX" target="_blank" style="position:fixed; bottom:80px; right:15px; background:#25D366; color:white; padding:12px; border-radius:50%; font-size:20px; z-index:1000; text-align:center;">💬</a>
<a href="https://t.me/yourchannel" target="_blank" style="position:fixed; bottom:130px; right:15px; background:#0088cc; color:white; padding:12px; border-radius:50%; font-size:20px; z-index:1000; text-align:center;">📢</a>



<button onclick="toggleDark()" style="position:fixed; top:10px; right:10px; background:#333; color:white; border:none; padding:8px 12px; border-radius:5px; cursor:pointer;">🌙 Dark</button>

<script>
  function toggleDark() {
    document.body.classList.toggle("darkmode");
  }
</script>

<style>
  .darkmode {
    background-color: #121212;
    color: white;
  }
  .darkmode a { color: #ffc107; }
</style>


<h2>📄 डाउनलोड नोटिस</h2>
<ul>
  <li><a href="notices/up-police-2025.pdf" target="_blank">UP Police भर्ती नोटिफिकेशन PDF डाउनलोड</a></li>
  <li><a href="notices/ssc-cgl-2025.pdf" target="_blank">SSC CGL 2025 PDF</a></li>
</ul>
<p id="counter" style="text-align:center; font-size:0.9em; margin-top:10px; color:gray;">👁️ Total Visitors: <span id="visits">0</span></p>

<script>
  if (localStorage.visits) {
    localStorage.visits = Number(localStorage.visits) + 1;
  } else {
    localStorage.visits = 1;
  }
  document.getElementById("visits").innerText = localStorage.visits;
</script>



  
  
  <h2>🔍 सर्च सरकारी नौकरी</h2>
<input type="text" id="searchInput" onkeyup="filterJobs()" placeholder="जैसे - SSC, Police, Teacher..." style="padding:10px; width:100%; margin-bottom:10px;">

<ul id="jobList">
  <li><a href="#">SSC CGL 2025 भर्ती</a></li>
  <li><a href="#">UP Police कांस्टेबल</a></li>
  <li><a href="#">Bihar Teacher Vacancy</a></li>
  <li><a href="#">Indian Navy SSR Agniveer</a></li>
</ul>

<script>
  function filterJobs() {
    let input = document.getElementById('searchInput').value.toUpperCase();
    let ul = document.getElementById("jobList");
    let li = ul.getElementsByTagName('li');
    for (let i = 0; i < li.length; i++) {
      let a = li[i].getElementsByTagName("a")[0];
      let txtValue = a.textContent || a.innerText;
      li[i].style.display = txtValue.toUpperCase().indexOf(input) > -1 ? "" : "none";
    }
  }
</script>

<h2>🗂️ कैटेगरी से खोजें</h2>
<div style="display:grid; grid-template-columns:repeat(auto-fit, minmax(150px, 1fr)); gap:15px;">
  <div style="background:#e0f7fa; padding:20px; border-radius:10px; text-align:center;">🏦 बैंक जॉब</div>
  <div style="background:#fff3e0; padding:20px; border-radius:10px; text-align:center;">🚆 रेलवे</div>
  <div style="background:#f3e5f5; padding:20px; border-radius:10px; text-align:center;">🛡️ डिफेंस</div>
  <div style="background:#e8f5e9; padding:20px; border-radius:10px; text-align:center;">🏫 टीचिंग</div>
  <div style="background:#fce4ec; padding:20px; border-radius:10px; text-align:center;">🧪 साइंस</div>
</div>


<a href="#contact" style="position:fixed; bottom:60px; left:15px; background:#007bff; color:#fff; padding:12px 16px; border-radius:50px; font-weight:bold; z-index:1000;">❓ सहायता</a>



<marquee behavior="scroll" direction="left" style="background:#ffeb3b; padding:10px; font-weight:bold;">
  📢 UPSSSC PET 2025 Form शुरू हो गया है! | SSC MTS 2025 Apply Now | CTET एडमिट कार्ड जारी |
</marquee>


<h2>📧 सरकारी रिजल्ट न्यूज़लेटर</h2>
<form onsubmit="alert('धन्यवाद! आपका ईमेल सेव हो गया है'); return false;">
  <input type="email" placeholder="अपना ईमेल डालें" required style="padding:10px; width:70%;">
  <button type="submit" style="padding:10px 20px; background:#800000; color:white;">सब्सक्राइब करें</button>
</form>





<!-- Loader -->
<div id="loader" style="position:fixed; top:0; left:0; width:100%; height:100%; background:white; display:flex; align-items:center; justify-content:center; z-index:9999;">
  <img src="https://i.gifer.com/ZZ5H.gif" alt="Loading..." style="width:60px;">
</div>

<script>
  window.addEventListener("load", function(){
    document.getElementById("loader").style.display = "none";
  });
</script>





<div id="google_translate_element" style="text-align:right; padding:10px;"></div>
<script type="text/javascript">
  function googleTranslateElementInit() {
    new google.translate.TranslateElement({pageLanguage: 'hi'}, 'google_translate_element');
  }
</script>
<script type="text/javascript" src="//translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>


<button onclick="topFunction()" id="topBtn" title="Go to top" style="position:fixed; bottom:20px; right:60px; display:none; background:#000; color:#fff; border:none; padding:10px 15px; border-radius:5px;">⬆️ ऊपर</button>

<script>
  var mybutton = document.getElementById("topBtn");
  window.onscroll = function() {
    if (document.body.scrollTop > 300 || document.documentElement.scrollTop > 300) {
      mybutton.style.display = "block";
    } else {
      mybutton.style.display = "none";
    }
  };
  function topFunction() {
    document.body.scrollTop = 0;
    document.documentElement.scrollTop = 0;
  }
</script>


<h2>❓ अक्सर पूछे जाने वाले सवाल</h2>
<button class="accordion">Sarkari Result क्या है?</button>
<div class="panel"><p>यह एक सरकारी नौकरी सूचना वेबसाइट है जहां लेटेस्ट जॉब्स, रिजल्ट, एडमिट कार्ड मिलते हैं।</p></div>

<button class="accordion">क्या यह फ्री है?</button>
<div class="panel"><p>हां, सभी जानकारी बिल्कुल मुफ्त उपलब्ध है।</p></div>

<style>
.accordion {
  background-color: #eee; padding: 10px; width: 100%; border: none; text-align: left; outline: none; cursor: pointer;
}
.panel {
  padding: 0 10px; display: none; background-color: #f1f1f1;
}
</style>
<script>
  var acc = document.getElementsByClassName("accordion");
  for (let i = 0; i < acc.length; i++) {
    acc[i].onclick = function() {
      this.classList.toggle("active");
      var panel = this.nextElementSibling;
      panel.style.display = (panel.style.display === "block") ? "none" : "block";
    };
  }
</script>





<h2>📌 महत्वपूर्ण लिंक</h2>
<div style="display:grid; grid-template-columns: repeat(auto-fit, minmax(160px, 1fr)); gap:10px;">
  <a href="#" style="background:#e0f2f1; padding:10px; display:block; text-align:center;">🎟️ Admit Card</a>
  <a href="#" style="background:#e8eaf6; padding:10px; display:block; text-align:center;">📜 Result</a>
  <a href="#" style="background:#fce4ec; padding:10px; display:block; text-align:center;">📝 Online Form</a>
  <a href="#" style="background:#fff3e0; padding:10px; display:block; text-align:center;">📚 Syllabus</a>
</div>




<footer style="background:#212121; color:white; padding:20px; margin-top:30px;">
  <div style="display:flex; flex-wrap:wrap; justify-content:space-between;">
    <div>
      <h3>🔗 Quick Links</h3>
      <ul style="list-style:none; padding:0;">
        <li><a href="#" style="color:#fff;">Home</a></li>
        <li><a href="#" style="color:#fff;">Latest Jobs</a></li>
        <li><a href="#" style="color:#fff;">Admit Card</a></li>
        <li><a href="#" style="color:#fff;">Result</a></li>
      </ul>
    </div>
    <div>
      <h3>📱 Follow Us</h3>
      <a href="#" style="color:#fff; margin-right:10px;">👍 Facebook</a>
      <a href="#" style="color:#fff; margin-right:10px;">📢 Telegram</a>
      <a href="#" style="color:#fff;">💬 WhatsApp</a>
    </div>
  </div>
  <p style="text-align:center; margin-top:20px;">© 2025 SarkariResultX.in | Developed by Abhishek Dubey</p>
</footer>



<!-- In <head> tag -->
<meta property="og:title" content="Sarkari Result 2025 - सरकारी नौकरियों की जानकारी">
<meta property="og:description" content="Apply Online, Admit Card, Result, Syllabus - All in One">
<meta property="og:image" content="https://yourdomain.com/og-image.jpg">
<meta property="og:url" content="https://yourdomain.com">
<meta name="twitter:card" content="summary_large_image">
  
  
  <p style="color:red; font-weight:bold; animation: blinker 1s linear infinite;">
  📣 Alert: SSC CGL Tier-1 Admit Card जारी हो गया है! अभी डाउनलोड करें!
</p>
<style>
@keyframes blinker {
  50% { opacity: 0; }
}
</style>
<h2>📌 लेटेस्ट नोटिस</h2>
<marquee behavior="scroll" direction="up" scrollamount="2" style="height:120px; background:#f9f9f9; padding:10px;">
  <p>📄 Bihar Police Admit Card 2025</p>
  <p>📄 SSC MTS 2025 Apply Link Active</p>
  <p>📄 UPTET 2025 Notification</p>
</marquee>

<h3>🔗 शेयर करें</h3>
<a href="https://wa.me/?text=Check%20latest%20Sarkari%20Jobs:%20https://yourwebsite.com" target="_blank">📲 WhatsApp</a> |
<a href="https://www.facebook.com/sharer/sharer.php?u=https://yourwebsite.com" target="_blank">📘 Facebook</a>




<!-- Trigger Button -->
<button onclick="document.getElementById('modal').style.display='block'" style="padding:10px;">🎯 Free Job Alert</button>

<!-- Modal -->
<div id="modal" style="display:none; position:fixed; top:0; left:0; width:100%; height:100%; background:rgba(0,0,0,0.6); z-index:9999;">
  <div style="background:#fff; margin:10% auto; padding:20px; width:300px; border-radius:10px; position:relative;">
    <span onclick="document.getElementById('modal').style.display='none'" style="position:absolute; right:10px; top:10px; cursor:pointer;">❌</span>
    <h3>🔔 फ्री जॉब अलर्ट</h3>
    <input type="text" placeholder="नाम" style="width:100%; padding:8px;"><br><br>
    <input type="email" placeholder="ईमेल" style="width:100%; padding:8px;"><br><br>
    <button style="padding:8px 16px; background:green; color:white;">सब्मिट</button>
  </div>
</div>

<!-- Add inside <head> tag -->
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "WebSite",
  "name": "SarkariResultX.in",
  "url": "https://sarkariresultx.in",
  "potentialAction": {
    "@type": "SearchAction",
    "target": "https://sarkariresultx.in/?s={search_term_string}",
    "query-input": "required name=search_term_string"
  }
}
</script>


<!-- Add in <head> -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">



<i class="fa-solid fa-bell"></i> Notification
<i class="fa-solid fa-envelope"></i> Email

  
    
    
    <div style="position:fixed; top:0; width:100%; background:#d32f2f; color:white; text-align:center; padding:8px; z-index:9999;">
  🚨 नोटिस: SSC CHSL 2025 के Admit Card जारी हो चुके हैं!
</div>
<div style="height:40px;"></div> <!-- spacing to avoid overlap -->

<h3>🔍 कैटेगरी के अनुसार नौकरियां खोजें</h3>
<select onchange="window.location.href=this.value" style="padding:10px;">
  <option selected disabled>-- Select Category --</option>
  <option value="#defence">🏹 Defence Jobs</option>
  <option value="#teaching">📚 Teaching Jobs</option>
  <option value="#bank">🏦 Bank Jobs</option>
  <option value="#railway">🚆 Railway Jobs</option>
</select>


<a href="tel:919999999999" style="position:fixed; bottom:190px; right:15px; background:#4CAF50; color:white; padding:12px; border-radius:50%; font-size:20px; z-index:1000;">📞</a>


<!-- Place this where you want ads -->
<div style="width:100%; text-align:center; background:#f5f5f5; padding:10px; border:1px dashed #ccc;">
  🔲 Your Google Ad Will Appear Here
</div>



<!-- Google Site Verification -->
<meta name="google-site-verification" content="YOUR-VERIFICATION-CODE" />

<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>


<h3>📬 Newsletter - Free Job Alert Email पर पाएं</h3>
<form action="mailto:your-email@example.com" method="post" enctype="text/plain">
  <input type="email" name="Email" placeholder="अपना ईमेल डालें" required style="padding:10px; width:250px;">
  <button type="submit" style="padding:10px; background:#2196F3; color:white;">सब्सक्राइब करें</button>
</form>

    
    
    <div style="
  backdrop-filter: blur(8px);
  background: rgba(255, 255, 255, 0.1);
  border-bottom: 1px solid rgba(255,255,255,0.2);
  padding: 20px;
  color: #fff;
  font-size: 24px;
  text-align: center;
  position: sticky;
  top: 0;
  z-index: 999;
">
  🌐 SarkariResultX.in – सरकारी नौकरियाँ सबसे पहले!
</div>

<button style="
  background: linear-gradient(45deg, #ff5722, #ff9800);
  color: white;
  padding: 12px 24px;
  border: none;
  border-radius: 30px;
  font-size: 16px;
  cursor: pointer;
  transition: all 0.3s ease;">
  🔎 Check Latest Jobs
</button>


<div style="
  border:1px solid #ccc;
  padding:20px;
  margin:10px;
  border-radius:15px;
  transition: transform 0.3s, box-shadow 0.3s;
" onmouseover="this.style.transform='scale(1.03)'; this.style.boxShadow='0 5px 15px rgba(0,0,0,0.2)'" onmouseout="this.style.transform='scale(1)'; this.style.boxShadow='none'">
  <h4>📋 UP Police Constable 2025</h4>
  <p>Form Last Date: 31 July 2025</p>
  <a href="#" style="color:blue;">Apply Now</a>
</div>

<!-- In <head> tag -->
<link href="https://fonts.googleapis.com/css2?family=Poppins&display=swap" rel="stylesheet">

<!-- In CSS -->
<style>
  body {
    font-family: 'Poppins', sans-serif;
  }
</style>
<!-- Smooth Scroll -->
<style>
  html { scroll-behavior: smooth; }
</style>

<!-- Scroll-To-Top -->
<button onclick="window.scrollTo({top: 0, behavior: 'smooth'});" style="position:fixed; bottom:20px; left:20px; background:#000; color:#fff; padding:10px 15px; border:none; border-radius:50%; font-size:18px;">⬆</button>


<div style="display:grid; grid-template-columns:repeat(auto-fit, minmax(250px, 1fr)); gap:15px;">
  <div style="background:#f4f4f4; padding:15px; border-radius:10px;">
    <h4>SSC GD 2025</h4><p>Apply Online</p>
  </div>
  <div style="background:#f4f4f4; padding:15px; border-radius:10px;">
    <h4>Railway Group D</h4><p>Admit Card</p>
  </div>
</div>


<div style="position:fixed; bottom:0; width:100%; background:#fff; border-top:1px solid #ccc; display:flex; justify-content:space-around; padding:10px 0; z-index:1000;">
  <a href="#" style="text-align:center; font-size:14px;">🏠<br>Home</a>
  <a href="#" style="text-align:center; font-size:14px;">📝<br>Form</a>
  <a href="#" style="text-align:center; font-size:14px;">📃<br>Result</a>
  <a href="#" style="text-align:center; font-size:14px;">📞<br>Contact</a>
</div>




    
    
    
    
    
  
</body>

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>All India Sarkari Jobs 2025</title>
  <style>
    body { font-family: Arial, sans-serif; margin:20px; background:#f9f9f9; }
    h1,h2 { color:#003366; }
    section { margin-bottom:30px; }
    ul { list-style:none; padding:0; }
    li { background:#fff; padding:10px; margin:5px 0; border-left:4px solid #003366; }
    a { color:#003366; text-decoration:none; font-weight:bold; }
    a:hover { text-decoration:underline; }
  </style>
</head>
<body>
  <h1>All India Sarkari Jobs 2025</h1>

  <section id="central">
    <h2>🧾 Central Government Jobs</h2>
    <ul>
      <li><a href="#">UPSC Civil Services 2025 – Apply from Feb 14; Exam June 2</a></li>
      <li><a href="#">SSC CGL 2025 – Tier I Application Mar 1–Jul 4; Exam Aug 13‑30</a></li>
      <li><a href="#">SSC CHSL 2025 – ~3,131 posts; Registration closes Jul 18</a></li>
      <li><a href="#">SSC MTS 2025 – ~1,075 vacancies; Apply by Jul 24</a></li>
      <li><a href="#">SSC JE 2025 – ~1,340 posts; Apply by Jul 21</a></li>
      <li><a href="#">IBPS PO 2025 – ~5,208 posts; Apply by Jul 21</a></li>
      <li><a href="#">IBPS Specialist Officer – ~1,007 posts; Apply by Jul 21</a></li>
      <li><a href="#">RBI Grade‑B Officer 2025 – Exam Jun 21</a></li>
      <li><a href="#">DRDO – ~152 Scientist B posts; Deadline Jul 18</a></li>
      <li><a href="#">RRB Technician/Group D – ~6,180+ posts; Apply by Jul 28</a></li>
      <li><a href="#">NPCIL – ~391 posts; Apply by Mar 2025</a></li>
      <li><a href="#">CISF Constable Tradesman – ~1,161 posts; Apply by Apr 3</a></li>
    </ul>
  </section>

  <section id="railway">
    <h2>🚆 Railway Jobs (RRB, etc.)</h2>
    <ul>
      <li><a href="#">RRB Assistant Loco Pilot – ~9,970 vacancies</a></li>
      <li><a href="#">RRB Apprentice & Technician – GM/ICF/BLW region</a></li>
      <li><a href="#">Railway Group D – ~32,243 posts</a></li>
    </ul>
  </section>

  <section id="defence">
    <h2>🛡️ Defence Jobs</h2>
    <ul>
      <li><a href="#">Indian Army Agniveer/Pharma/Havildar – ~10,000+ posts</a></li>
      <li><a href="#">CAPF Assistant Commandant (UPSC) – ~357 posts</a></li>
    </ul>
  </section>

  <section id="banking">
    <h2>🏦 Banking Sector Jobs</h2>
    <ul>
      <li><a href="#">SBI PO – ~541 vacancies; Apply by Jul 14</a></li>
      <li><a href="#">Bank of Baroda Apprentices – ~2,500 posts</a></li>
    </ul>
  </section>

  <section id="statepsc">
    <h2>🏛️ State PSC & State Jobs</h2>
    <ul>
      <li><a href="#">RPSC Recruitment – ~12,121 posts across departments; Apply Jul‑Sep (Rajasthan)</a></li>
      <li><a href="#">TNPSC Group I & TRB – ~645 & ~1,996 posts (Tamil Nadu)</a></li>
      <li><a href="#">Bihar Police Constable – Apply Jan 10; Exam Apr 20</a></li>
      <li><a href="#">MPESB PRT – ~18,650 posts; Apply by Aug 1 (Madhya Pradesh)</a></li>
      <li><a href="#">UP Lekhpal – ~5,000+ posts; Notification Feb‑Mar</a></li>
      <li><a href="#">MP Anganwadi – ~19,500 posts; Apply by Jul 4</a></li>
    </ul>
  </section>

  <section id="others">
    <h2>📌 Other Departments / PSU / Health / Education</h2>
    <ul>
      <li><a href="#">AIIMS – ~3,501 posts across multiple specialties</a></li>
      <li><a href="#">Education Recruit Punjab PTI – ~2,000 posts; Apply Aug 22</a></li>
      <li><a href="#">CSIR‑CDRI JSA / Steno posts</a></li>
      <li><a href="#">FCI & PSU roles across sectors (SAIL, BHEL, ONGC)</a></li>
      <li><a href="#">India Post GDS – ~21,413 posts (Gramin Dak Sevak)</a></li>
    </ul>
  </section>

  <footer>
    <p style="text-align:center; margin-top:40px;">© 2025 All India Sarkari Jobs Portal</p>
  </footer>
  
  
  
  <h2>SSC CGL 2025</h2>
<p><strong>Notification:</strong> 9 जून 2025 | <strong>Posts:</strong> 14,582</p>
<p><strong>Apply Online:</strong> 9 जून – 4 जुलाई (₹100 fee, correction window 9–11 जुलाई)</p>
<p><strong>Tier‑1 Exam:</strong> 13–30 अगस्त 2025, CBT (100 questions, negative marking 0.5)</p>
<p><strong>Eligibility:</strong> Graduate, Age 18‑32 (Category-wise relaxation)</p>
  
</body>
</html>
  
  
  
  
  
