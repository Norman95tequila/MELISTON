<!DOCTYPE html>
<html lang="el">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MELISTON</title>
    <link rel="icon" href="favicon.ico" type="image/x-icon">
    <style>
        body {
            font-family: Raleway, sans-serif;
            margin: 0;
            padding: 0;
            background-color: ##F5EFEE;
            color: #808000;
        }
        header {
            background-color: #F5EFEE;
            color: #808000;
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
    <a href="#about">Ποιοι είμαστε</a>
    <a href="#products">Προϊόντα</a>
    <a href="#gallery">Φωτογραφίες & Βίντεο</a>
    <a href="#articles">Άρθρα & Συνταγές</a>
    <a href="#contact">Επικοινωνία</a>
</nav>

<div class="container" id="about">
    <h2>Ποιοι είμαστε</h2>
    <p>ο MELISTON δημιουργήθηκε στην Τήνο, το 2011 η σχέση όμως της οικογένειάς μας με τη μελισσοκομία μετρά σχεδόν 100 χρόνια, όταν ο προπάππους του Αντώνη Δελλατόλα, ξεκίνησε από τους πρώτους τη μελισσοκομία στο νησί της Τήνου. Οι γνώσεις και η αγάπη για τις μέλισσες πέρασαν από γενιά σε γενιά και το 2011 γεννήθηκε το MELISTON.</p>
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
        </div>
        <div class="product">
            <h3>Μέλι Ερείκης Τήνου</h3>
             <div id="image-container">
    <img src="ereikis.jpg" alt="heather honey">
            <p>Κάτω από τον ελληνικό ήλιο, μέσα στη δροσιά του Αιγαίου και στους καλύτερους ερεικότοπους της Τήνου, παράγεται το μέλι ερείκης MELISTON. Αυτούσιο από τη μέλισσα, το μέλι συλλέγεται εδώ και τρεις γενιές από την οικογένειά μας και χωρίς καμία επεξεργασία φτάνει στα χέρια σας αγνό, αρωματικό και πεντανόστιμο. 
            Η αρμονία της φύσης, η ευφυΐα των μελισσών και το ιδανικό ελληνικό κλίμα συνταντήθηκαν με το μεράκι και την πολυετή εμπειρία μας για να δημιουργήσουν ένα εξαιρετικό προϊόν υψηλής διατροφικής αξίας, που φημίζεται για τις αντισηπτικές και αντιοξειδωτικές του ιδιότητες. Άλλωστε, η περιορισμένη μας παραγωγή είναι και η εγγύηση, ότι κάθε βαζάκι MELISTON είναι πραγματικά άριστον.</p>
        </div>
        <!-- Προσθέστε περισσότερα προϊόντα εδώ -->
    </div>
</div>

<div class="container" id="gallery">
    <h2>Φωτογραφίες & Βίντεο</h2>
    <div class="gallery">
        <div class="photo">
            <img src="photo1.jpg" alt="Φωτογραφία 1" style="width:100%">
        </div>
        <div class="photo">
            <img src="photo2.jpg" alt="Φωτογραφία 2" style="width:100%">
        </div>
        <!-- Προσθέστε περισσότερες φωτογραφίες εδώ -->
    </div>
</div>

<div class="container" id="articles">
    <h2>Άρθρα & Συνταγές</h2>
    <div class="articles">
        <div class="article">
            <h3>Οφέλη του Μελιού</h3>
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
    <p>Email: info@melissokomiki-epixeirisi.gr</p>
    <div>
        <a href="https://www.facebook.com" target="_blank">
            <img src="facebook-icon.png" alt="Facebook" style="width:30px">
        </a>
        <a href="https://www.instagram.com" target="_blank">
            <img src="instagram-icon.png" alt="Instagram" style="width:30px">
        </a>
    </div>
</div>

<footer>
    <p>&copy; 2024 Μελισσοκομική Επιχείρηση</p>
</footer>

</body>
</html>
# MELISTON
