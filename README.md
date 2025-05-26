<!DOCTYPE html>
<html lang="mr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Historical Fort Guide</title>
  <link rel="stylesheet" href="style.css"/>

  <Language Switcher Dropdown ></Language>
<select id="languageSwitcher" style="position: fixed; top: 10px; right: 10px; z-index: 1000;">
  <option value="mr">मराठी</option>
  <option value="en">English</option>
</select>

</head>
<body>
  <header>
    <nav>
      <div class="logo">शिलेदार</div>
      <ul class="nav-links">
        <li><a href="#home">मुखपुष्ट </a></li>
        <li><a href="#locations">बघण्यासारखी ठिकाणे </a></li>
        <li><a href="#history">इतिहास </a></li>
        <li><a href="#gallery">छायाचित्रे</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="home" class="hero">
      <h1>शिवनेरी गडावर आपले स्वागत आहे......</h1>
      <p>प्राचीन किल्ल्याचा समृद्ध इतिहास आणि वास्तुकला अनुभवा......</p>
      <img src="images/shivneri fort map.jpeg" alt="Palace"/>
    </section>

    <section id="locations" class="locations">
      <h2>गडावरील ऐतिहासिक वास्तू</h2>
      <div class="location-grid">
        <div class="location-card">
          <img src="images/buruj.jpeg" alt="Main Gate"/>
          <a href="buruj.html"><h3>बुरुज </h3></a>
          <p>बुरुज म्हणजे किल्ल्याच्या तटबंदीवर बांधलेले उंच संरक्षक मनोरे...</p>
        </div>

        <div class="location-card">
          <img src="images/chorwat.jpg" alt="Main Gate"/>
          <a href="chordarvaja.html"><h3>शौचालय व चोरवाट </h3></a>
          <p>पूर्वीच्या काळात देखील सैनिकांसाठी शौचालय होते...</p>
        </div>

        <div class="location-card">
          <img src="images/mahadarvaja.jpeg" alt="Palace"/>
          <a href="alldoors.html"><h3> महादरवाजा</h3></a>
          <p>हा गडाचा मुख्य दरवाजा आहे...</p>
        </div>

        <div class="location-card">
          <img src="images/hattidaravaja.jpeg" alt="Main Gate"/>
          <a href="alldoors.html"><h3>हत्तीदरवाजा </h3></a>
          <p>हत्तीदरवाजा हा किल्ल्याच्या मुख्य प्रवेशद्वारांपैकी एक आहे...</p>
        </div>

        <div class="location-card">
          <img src="images/ganeshdarvaja.png" alt="Palace"/>
          <a href="alldoors.html"><h3>गणेश दरवाजा</h3></a>
          <p>हा सर्वात प्राचीन दरवाजा आहे...</p>
        </div>

        <div class="location-card">
          <img src="images/shivai mandir.jpg" alt="Main Gate"/>
          <a href="shivai mandir.html"><h3>शिवाई देवी मंदिर </h3></a>
          <p>हे मंदिर खास महत्त्वाचे ठरते कारण...</p>
        </div>

        <div class="location-card">
          <img src="images/badami take.jpeg" alt="Palace"/>
          <a href="badami take.html"><h3>बदामी टाके</h3></a>
          <p>शिवनेरी किल्ल्यावर असलेली एक प्राचीन जलसंचय व्यवस्था...</p>
        </div>

        <div class="location-card">
          <img src="images/kadelot.jpeg" alt="Palace"/>
          <a href="kadelot.html"><h3>कडेलोट </h3></a>
          <p>"कडेलोट" म्हणजे गुन्हेगार किंवा शत्रूला किल्ल्याच्या कड्यावरून फेकण्याची शिक्षा...</p>
        </div>

        <div class="location-card">
          <img src="images/shivkunj1.jpg" alt="Main Gate"/>
          <a href="Shivkunj.html"><h3>शिवकुंज</h3></a>
          <p>शिवनेरी किल्ल्यावर बालशिवाजी आणि जिजाऊ यांच्या सुंदर मूर्ती आहेत...</p>
        </div>

        <div class="location-card">
          <img src="images/janmthikan of maharaj.JPG" alt="Main Gate"/>
          <a href="janmsthan.html"><h3>छत्रपती शिवाजी महाराजांचे जन्मस्थान</h3></a>
          <p>१९ फेब्रुवारी १६३० रोजी शिवाजी महाराजांचा जन्म याच गडावर झाला...</p>
        </div>
      </div>
    </section>

    <section id="history" class="history">
      <h2>गडाचा इतिहास</h2>
      <div class="timeline">
        <p>शिवनेरी गड हा सातवाहन कालखंडातही महत्त्वाचा होता...</p><br>
        <a href="history.html" class="timeline-link">
          <h3>अधिक जाणून घेण्यासाठी येथे क्लिक करा..</h3>
        </a>
      </div>
    </section>

    <br/>

    <section id="gallery" class="gallery">
      <h2> छायाचित्रे </h2>
      <div class="gallery-grid">
        <div><img src="images/shivneri fort1.jpeg" alt="Fort View 1"/></div>
        <div><img src="images/fort8 (1).jpeg" alt="Fort View 3"/></div>
        <img src="images/shivneri fort3.jpeg" alt="Fort View 4"/>
        <img src="images/fort8 (2).jpeg" alt="Fort View 5"/>
      </div>
    </section>
    
    <!-- ✅ Google Translate Dropdown (Top Right Corner) -->
  <div id="google_translate_element" style="position: fixed; top: 10px; right: 10px; z-index: 1000;"></div>

  <script type="text/javascript">
    function googleTranslateElementInit() {
      new google.translate.TranslateElement(
        {
          pageLanguage: 'mr',
          includedLanguages: 'en,mr',
          layout: google.translate.TranslateElement.InlineLayout.SIMPLE
        },
        'google_translate_element'
      );
  }
  </script>

  <script type="text/javascript" src="//translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>

  </main>

  
  <footer>
    <p>&copy; 2024 Historical Fort Guide. All rights reserved.</p>
  </footer>

 <script src="script.js"></script> 
 
</body>
</html>
