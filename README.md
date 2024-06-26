<!DOCTYPE html>
<html lang="el">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" href="meliston logo.png" type="image/x-icon">
    <style>
        body {
            font-family: Proxima Nova, Cambria;
            margin: 0;
            padding: 0;
            background-color: #F5EFEE;
            color: #17202A;
        }
        header {
            background-color: #F5EFEE;
            color: #17202A;
            padding: 20px 0;
            text-align: center;
        }
        header img {
            width: 50px;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
            padding: 10px 0;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            padding: 5px 10px;
        }
        nav a:hover {
            background-color: #575757;
            border-radius: 5px;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px 0;
        }
        h1, h2 {
            color: #444;
        }
        .products, .gallery, .articles {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .product, .photo, .article {
            flex: 1 1 calc(33.333% - 40px);
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            padding: 20px;
            background-color: #fff;
        }
        .contact {
            background-color: #2d2d2d;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        footer {
            background-color: #444;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>

<header>
    <img src="meliston logo.png" alt="MelistonLogo">
    <h1>MELISTON</h1>
    <p>Καλωσήρθατε στο MELISTON! Μαζί θα ανακαλύψουμε τον κόσμο των μελισσών!</p>
</header>

<nav>
      <li><a href="index.html" style="display: none;">Αρχική</a></li>
        <li><a href="products.html">Προϊόντα</a></li>
        <li><a href="about.html">Βιογραφικό</a></li>
        <li><a href="contact.html">Επικοινωνία</a></li>
        <li><a href="articles.html">Άρθρα</a></li>
</nav>

<div class="container" id="about">
    <h2>Ποιοι είμαστε</h2>
    <p>To MELISTON δημιουργήθηκε στην Τήνο, το 2011 η σχέση όμως της οικογένειάς μας με τη μελισσοκομία μετρά σχεδόν 100 χρόνια, όταν ο προπάππους του Αντώνη Δελλατόλα, ξεκίνησε από τους πρώτους τη μελισσοκομία στο νησί της Τήνου. Οι γνώσεις και η αγάπη για τις μέλισσες πέρασαν από γενιά σε γενιά και το 2011 γεννήθηκε το MELISTON.</p>
</div>

<div class="container" id="products">
    <h2>Προϊόντα</h2>
    <div class="products">
        <div class="product">
            <h3>Θυμαρίσιο Μέλι Τήνου</h3>
            <div id="image-container">
    <img src="thimarisio.jpg" alt="thyme honey">
</div>
            <p>Κάτω από τον ελληνικό ήλιο, μέσα στη δροσιά του Αιγαίου και στους καλύτερους θυμαρότοπους της Τήνου, παράγεται το μέλι MELISTON. Αυτούσιο από τη μέλισσα, το μέλι συλλέγεται εδώ και τρεις γενιές από την οικογένειά μας και χωρίς καμία επεξεργασία φτάνει στα χέρια σας αγνό, αρωματικό και πεντανόστιμο. 
            Η αρμονία της φύσης, η ευφυΐα των μελισσών και το ιδανικό ελληνικό κλίμα συνταντήθηκαν με το μεράκι και την πολυετή εμπειρία μας για να δημιουργήσουν ένα εξαιρετικό προϊόν υψηλής διατροφικής αξίας, που φημίζεται για τις αντισηπτικές και αντιοξειδωτικές του ιδιότητες. Άλλωστε, η περιορισμένη μας παραγωγή είναι και η εγγύηση, ότι κάθε βαζάκι MELISTON είναι πραγματικά άριστον.</p>
            
</div> <div class="container" id="products">
    <h2>Προϊόντα</h2>
    <div class="products">
        <div class="product">
            <h3>Θυμαρίσιο Μέλι Ερείκης</h3>
            <div id="image-container">
    <img src="ereikis.jpg" alt="heather honey">
</div>
            <p>Κάτω από τον ελληνικό ήλιο, μέσα στη δροσιά του Αιγαίου και στους καλύτερους ερεικότοπους της Τήνου, παράγεται το μέλι ερείκης MELISTON. Αυτούσιο από τη μέλισσα, το μέλι συλλέγεται εδώ και τρεις γενιές από την οικογένειά μας και χωρίς καμία επεξεργασία φτάνει στα χέρια σας αγνό, αρωματικό και πεντανόστιμο. 
            Η αρμονία της φύσης, η ευφυΐα των μελισσών και το ιδανικό ελληνικό κλίμα συνταντήθηκαν με το μεράκι και την πολυετή εμπειρία μας για να δημιουργήσουν ένα εξαιρετικό προϊόν υψηλής διατροφικής αξίας, που φημίζεται για τις αντισηπτικές και αντιοξειδωτικές του ιδιότητες. Άλλωστε, η περιορισμένη μας παραγωγή είναι και η εγγύηση, ότι κάθε βαζάκι MELISTON είναι πραγματικά άριστον.</p>
        </div>
<div class="container" id="gallery">
    <h2>Φωτογραφίες</h2>
    <div class="gallery">
        <div class="photo">
            <img src="beehive.JPG" alt="Φωτογραφία 1" style="width:100%">
        </div>
        <div class="photo">
            <img src="apiaryfir.jpeg" alt="Φωτογραφία 2" style="width:100%">
        </div>
       <div class="photo">
            <img src="beecomb.JPG" alt="Φωτογραφία 2" style="width:100%">
    </div>
</div>

<div class="container" id="articles">
    <h2>Άρθρα & Συνταγές</h2>
    <div class="articles">
        <div class="article">
            <h3>Τα οφέλη του μελιού στον οργανισμό μας</h3>
            <p>Περιγραφή άρθρου για τα οφέλη του μελιού.</p>
        </div>
        <div class="article">
            <h3>Συνταγή με Μέλι</h3>
            <p>Περιγραφή συνταγής με μέλι.</p>
        </div>
        <!-- Προσθέστε περισσότερα άρθρα εδώ -->
    </div>
</div>

<div class="contact" id="contact">
    <h2>Επικοινωνία</h2>
    <p>Τηλέφωνο: 123-456-7890</p>
    <p>Email: info@melistonhoney.com</p>
    <div>
        <!-- Instagram -->
<a href="https://www.instagram.com/melistonhoney" target="_blank"><img src="icons8-instagram-96.png" alt="Instagram"></a>

<!-- Facebook -->
<a href="https://www.facebook.com/melistonhoney" target="_blank"><img src="icons8-facebook-96.png" alt="Facebook"></a>

<footer>

<div>
    <Add index.htm>
    


    
    <p>&copy; 2024 MELISTON</p>
</footer>

</body>
</html>
# MELISTON
