# waste-collection-and-recycling-network
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Waste Management & Recycling Platform</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&family=Montserrat:wght@700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            color: #ffffff;
            position: relative;
            background-color: #1a1a1a;
            background-image: url('https://www.transparenttextures.com/patterns/asfalt-dark.png');
            background-size: cover;
        }

        .slideshow-container {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            overflow: hidden;
            z-index: -1;
        }

        .mySlides {
            display: none;
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        header, nav, .content, footer {
            background-color: transparent;
            padding: 20px;
            text-align: center;
            border-radius: 10px;
            margin-bottom: 20px;
        }

        header h1 {
            font-family: 'Montserrat', sans-serif;
            font-size: 3em;
            font-weight: bold;
            margin: 0;
        }

        nav a {
            margin: 0 15px;
            text-decoration: none; 
            color: #ffffff; 
        }

        nav a:hover {
            color: #4CAF50;
        }

        .cta-button {
            padding: 15px 30px;
            background-color: #4CAF50;
            color: white;
            text-decoration: none;
            font-size: 1.2em;
            border-radius: 5px;
            display: inline-block;
            transition: background-color 0.3s ease;
        }

        .cta-button:hover {
            background-color: #45a049;
        }

        #imageDisplay {
            display: none;
            margin-top: 20px;
            cursor: pointer;
        }

        #imageDisplay img {
            max-width: 100%;
            height: auto;
        }

        footer p {
            font-size: 0.9em;
            margin-top: 20px;
            color: #ccc;
            font-weight: bold;
        }

        /* Notification Styles */
        #notification {
            display: none;
            position: fixed;
            top: -100px;
            left: 50%;
            transform: translateX(-50%);
            background-color: #4CAF50;
            color: white;
            padding: 15px;
            width: 80%;
            max-width: 500px;
            border-radius: 5px;
            text-align: center;
            font-weight: bold;
            font-size: 1.1em;
            z-index: 1000;
            transition: top 0.5s ease;
        }

        #notification.show {
            display: block;
            top: 20px;
        }

        /* Location Button Style */
        .location-button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 15px;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.1em;
            transition: background-color 0.3s ease;
            display: inline-flex;
            align-items: center;
        }

        .location-button i {
            margin-right: 5px;
        }

        .location-button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

    <!-- Notification Panel -->
    <div id="notification">Don't forget to schedule your next waste pickup! ON MONDAY Residential Waste (Green Bin) 7:00 AM - 10:00 AM</div>

    <div class="slideshow-container">
        <img class="mySlides" src="https://www.deskera.com/blog/content/images/2022/09/zibik-iR4mClggzEU-unsplash.jpg" alt="Recycling bins in a park">
        <img class="mySlides" src="https://www.conserve-energy-future.com/wp-content/uploads/2014/04/waste-disposal-management-landfills-garbage.jpg" alt="Waste disposal management">
        <img class="mySlides" src="https://bardalevillage.co.za/wp-content/uploads/2017/05/Recycling-at-Home.jpg" alt="Recycling at home">
    </div>

    <header>
        <h1>Waste Management & Recycling Platform</h1>
        <p>Helping you reduce, reuse, and recycle for a greener tomorrow</p>
    </header>

    <nav>
        <a href="#scheduling">Schedule Pickup</a>
        <a href="#education">Learn to Recycle</a>
        <a href="#community">Join the Community</a>
        <a href="https://www.google.com/maps/d/edit?mid=13qjvbTJtPPZ0fFxPibz8fODunWSMnTY&usp=sharing" class="location-button" target="_blank">
            <i class="fas fa-map-marker-alt"></i> Location
        </a>
    </nav>

    <div class="content" id="scheduling">
        <h2>Schedule Your Waste Pickup</h2>
        <p>Our platform allows you to easily schedule waste and recycling pickups. Just enter your address and select the services you need.</p>
        <a href="https://1drv.ms/w/c/98fea545bc0bf105/Ec2QBSYU1CpInozMLmLCIZoBIC7n60DWDuXNTI1G2fDYSQ?e=3m1uxo" class="cta-button" target="_blank">Schedule Pickup</a>
    </div>

    <div class="content" id="education">
        <h2>Learn How to Recycle</h2>
        <p>Recycling is a key part of reducing waste and conserving resources. Our educational resources will help you understand which materials can be recycled, how to properly sort your waste, and the environmental impact of recycling.</p>
        <a href="https://1drv.ms/p/c/98fea545bc0bf105/EdzjphJUEl1GjIFnBEMzlVMBgyR2FiFbfWj8PXDQc8kn2g?e=VLEUhx/" class="cta-button" target="_blank">Explore Educational Resources</a>
    </div>

    <div class="content" id="community">
        <h2>Join the Recycling Community</h2>
        <p>Track your recycling habits, earn rewards, and participate in community challenges. Together, we can make a difference!</p>
        <a href="https://forms.office.com/pages/responsepage.aspx?id=NU4Ei1EsukGT89GhB8p8UKUFLGT8j29Fl9nuJ2Of0eJUMlUwQ1RWS0Q4WDBRMUQxUDYyWlVZV0k0QS4u&origin=lprLink&route=shorturl" class="cta-button" target="_blank">Join Now</a>
    </div>

    <footer>
        <p>&copy; 2024 Waste Management & Recycling Platform | All Rights Reserved</p>
        <p>Contact: 9573611420, 9182174754 | Email: md.junaid211234@gmail.com</p>
    </footer>

    <script>
        var slideIndex = 0;
        showSlides();

        function showSlides() {
            var slides = document.getElementsByClassName("mySlides");
            for (var i = 0; i < slides.length; i++) {
                slides[i].style.display = "none";  
            }
            slideIndex++;
            if (slideIndex > slides.length) {slideIndex = 1}    
            slides[slideIndex-1].style.display = "block";  
            setTimeout(showSlides, 2000);
        }

        function showNotification() {
            var notification = document.getElementById("notification");
            notification.classList.add("show");
            setTimeout(function() {
                notification.classList.remove("show");
            }, 5000); // Hide after 10 seconds
        }

        // Trigger notification on page load
        window.onload = function() {
            setTimeout(showNotification, 3000); // Show notification after 3 seconds
        };
    </script>
</body>
</html>
