# Ex04 Places Around Me
## Date: 05.12.2024

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
yuvaram.html :
<html>
    <head>
        <title>TRICHY</title>
    </head>
    <body>
        <div style="text-align: center;">
        <h1 > Explore My Neighbourhood</h1>
        <h2> Please click any of the pictures in the middle to know more about it</h2>
        
            <div style="text-align: center;">
            <img src="c:\Users\admin\OneDrive\Pictures\Screenshots\Screenshot 2024-12-04 113151.png" alt=""  usemap="#Landmark" style="width: fit-content;">
            </div>
         <map name="Landmark">
            <area shape="circle" coords="1319,291,12" title="Kallanai Dam" href="C:\Users\admin\NearMe\imgmap\imgapp\static\kall.html">
            <area shape="circle" coords="564,775,16" title="Tiruchirappalli InterNational Airport" href="C:\Users\admin\NearMe\imgmap\imgapp\static\airp.html">
            <area shape="circle" coords="485,591,17" title="Trichy" href="C:\Users\admin\NearMe\imgmap\imgapp\static\tri.html">
            <area shape="circle" coords="1239,806,14" title="NIT" href="C:\Users\admin\NearMe\imgmap\imgapp\static\nit.html">
            <area shape="circle" coords="316,181,16" title="Theppakulam" href="C:\Users\admin\NearMe\imgmap\imgapp\static\thep.html">
            <area shape="circle" coords="" title="Srirangam" href="">
         </map>
        </div>
    </body>
</html>

trichy.html :
<!DOCTYPE html>
<html lang="en">
<head>
    <title>History of Trichy</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
 
        section {
            max-width: 800px;
            margin: 20px auto;
            background: #fff;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

       h1, h2 {
            color: #333;
        }
        .image-container {
            text-align: center;
            margin: 20px 0;
        }
        .image-container2 {
            text-align: center;
            margin: 20px 0;
        }
        .image-container img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
    <header>
        <h1 style="text-align: center;">History of Trichy</h1>
    </header>
    <section>
        <div class="image-container">
            <img src="C:\Users\admin\OneDrive\Desktop\html folder\rockfort01.avif" alt="A beautiful view of Trichy">
        </div>
        <h2>About Trichy</h2>
        <p>
            Tiruchirappalli, commonly known as Trichy, is a historic city located in the southern state of Tamil Nadu, India. 
            It has a rich history that dates back to ancient times and has been an important center of political, cultural, 
            and religious significance.
        </p>
        <h2>Ancient History</h2>
        <p>
            Trichy has been mentioned in Tamil literature as early as the Sangam period (circa 3rd century BCE to 3rd century CE). 
            The city was ruled by various dynasties, including the Cholas, Pandyas, Pallavas, and later the Vijayanagara Empire.
        </p>
        <h2>Rockfort Temple</h2>
        <p>
            One of the most iconic landmarks in Trichy is the Rockfort Temple, a historic structure built atop a massive rock. 
            The site has been a fortress and a place of worship for centuries.
        </p>
        <h2>Colonial Era</h2>
        <p>
            During the colonial period, Trichy was an important British cantonment and played a significant role in the 
            South Indian freedom struggle.
        </p>
        <h2>Modern Trichy</h2>
        <p>
            Today, Trichy is a bustling city known for its educational institutions, temples, and industries. It is a vibrant 
            blend of historical heritage and modern development.
        </p>
        
    </section>
</body>
</html>

theppakulam.html :
<!DOCTYPE html>
<html lang="en">
<head>
    
    <title>Trichy Teppakulam</title>
    <style>
        body {
            font-family: 'Verdana', sans-serif;
            background-color: #f9f9f9;
            margin: 0;
            padding: 0;
        }
        
        .container {
            max-width: 1000px;
            margin: 20px auto;
            padding: 20px;
            background: #ffffff;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        }
        .image-container {
            text-align: center;
            margin-bottom: 20px;
        }
        .image-container img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        h1, h2 {
            color: #0077b6;
            text-align: center;
        }
        p {
            color: #333;
            line-height: 1.8;
            text-align: justify;
        }
        .highlight {
            background: #caf0f8;
            padding: 5px;
            border-radius: 5px;
            font-weight: bold;
        }
 
    </style>
</head>
<body>
    <header>
        <h1>Trichy Teppakulam</h1>
    </header>
    <div class="container">
        <div class="image-container">
            <img src="c:\Users\admin\OneDrive\Desktop\html folder\theppaku.jpg" alt="Trichy Teppakulam - A Sacred Tank in Tamil Nadu">
        </div>
        <h2>About Teppakulam</h2>
        <p>
            The <span class="highlight">Trichy Teppakulam</span>, also known as the Mariamman Teppakulam, is a sacred 
            tank located near the Rockfort Temple in Tiruchirappalli, Tamil Nadu. This magnificent tank is an 
            architectural and cultural landmark, believed to have been built during the Nayak period. It spans a vast area 
            and features a central mandapam with a shrine dedicated to Lord Vinayaka.
        </p>
        <h2>Historical Significance</h2>
        <p>
            Teppakulam was excavated by the orders of King Thirumalai Nayak in the 17th century, using soil from the tank 
            to construct the iconic Rockfort Temple. The tank symbolizes the ingenuity of ancient engineering and the 
            dedication to temple architecture during that era.
        </p>
        <h2>Float Festival (Teppam)</h2>
        <p>
            One of the main attractions of the Teppakulam is the annual <em>Teppam Festival</em>, celebrated with grandeur 
            and devotion. During this festival, deities from nearby temples are placed on ornately decorated floats and 
            taken around the tank. The sight of the illuminated floats on the water during the festival is mesmerizing and 
            attracts devotees and tourists alike.
        </p>
    </div>
    
</body>
</html>

nit.html :
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>National Institute of Technology, Trichy</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: blue;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        h1, h2, h3 {
            margin: 0;
        }
        .container {
            max-width: 900px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        img {
            width: 100%;
            border-radius: 8px;
            margin-bottom: 20px;
        }
        p {
            font-size: 1.1em;
            line-height: 1.6;
        }
        ul {
            list-style-type: disc;
            margin-left: 20px;
        }
       
    </style>
</head>
<body>

<header>
    <h1>National Institute of Technology, Trichy</h1>
</header>

<div class="container">
    <img src="c:\Users\admin\OneDrive\Desktop\html folder\nit1.jpeg" alt="NIT Trichy ">

    <h2>About NIT Trichy</h2>
    <p>The National Institute of Technology, Tiruchirappalli (NIT Trichy), established in 1964, is an Institute of National Importance located in Tamil Nadu, India. It is known for its academic rigor, vibrant campus life, and significant contributions to research and innovation. It has consistently ranked among the top engineering institutions in the country.</p>

    <h3>Academic Programs</h3>
    <p>NIT Trichy offers a wide range of academic programs:</p>
    <ul>
        <li><b>Undergraduate Programs:</b> Bachelor of Technology (B.Tech) in disciplines like Civil, Mechanical, Electrical, Computer Science, and more.</li>
        <li><b>Postgraduate Programs:</b> Master of Technology (M.Tech), Master of Science (M.Sc.), and Master of Business Administration (MBA).</li>
        <li><b>Doctoral Programs:</b> Research opportunities in engineering, sciences, humanities, and management.</li>
    </ul>

    <h3>Campus Facilities</h3>
    <p>The campus spans over 800 acres and boasts state-of-the-art infrastructure:</p>
    <ul>
        <li>Modern classrooms and well-equipped laboratories.</li>
        <li>Central Library with an extensive collection of books, journals, and digital resources.</li>
        <li>Hostels for boys and girls with recreational facilities.</li>
        <li>Sports complexes, auditoriums, and a student activity center.</li>
    </ul>
    <h3>NIT Library</h3>
    <img src="c:\Users\admin\OneDrive\Desktop\html folder\nit2.avif" alt="NIT Library">
    <h3>Research and Innovation</h3>
    <p>NIT Trichy is at the forefront of research and innovation:</p>
    <ul>
        <li>Collaborations with national and international research organizations.</li>
        <li>Active incubation center for startups and entrepreneurship.</li>
        <li>Regularly organizes workshops, conferences, and hackathons.</li>
    </ul>

    <h3>Achievements</h3>
    <p>NIT Trichy has earned accolades for:</p>
    <ul>
        <li>Consistent top rankings in engineering education by NIRF and other organizations.</li>
        <li>Alumni network with professionals in leading global organizations.</li>
        <li>Successful placement record with top recruiters visiting the campus every year.</li>
    </ul>
    <h3>NIT College Logo</h3>
    <img src="c:\Users\admin\OneDrive\Desktop\html folder\nit3.png" alt="NIT Trichy Logo">
    <h3>Location</h3>
    <p>NIT Trichy is strategically located in the city of Tiruchirappalli, Tamil Nadu, which is well-connected by road, rail, and air. The campus is situated about 20 kilometers from the city center, providing a serene and focused environment for students.</p>
</div>



</body>
</html>

kallanai.html :
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Kallanai Dam - Trichy</title>
    <style>
        body {
            font-family: 'Georgia', serif;
            margin: 0;
            padding: 0;
            background: #e3f2fd;
        }
        header {
            background: orangered;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        .hero-section {
            height: 10vh;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
        }       
        .content {
            max-width: 900px;
            margin: 20px auto;
            padding: 20px;
            background: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .content h2 {
            color: #1b5e20;
            margin-bottom: 10px;
        }
        .content p {
            line-height: 1.8;
            color: #333;
        }
        .content ul {
            margin: 10px 0;
            padding-left: 20px;
        }
        .content ul li {
            margin-bottom: 5px;
        }
        .image-container img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        
    </style>
</head>
<body>
    <header>
        <h1>Kallanai Dam</h1>
    </header>
    
        <h2 class="hero-section">An Ancient Marvel of Tamil Nadu</h2>

    <div class="content">
        <div class="image-container">
            <img src="c:\Users\admin\OneDrive\Desktop\html folder\kallanai.jpg" alt="Trichy Teppakulam - A Sacred Tank in Tamil Nadu">
        </div>
        <h2>About Kallanai Dam</h2>
        <p>
            Kallanai Dam, also known as the Grand Anicut, is one of the oldest water-regulation structures in the world, 
            located in Tiruchirappalli, Tamil Nadu. Built across the Kaveri River by the Chola King Karikala around the 
            2nd century CE, the dam showcases the ingenuity of ancient Indian engineering.
        </p>
        <h2>Features</h2>
        <ul>
            <li>Constructed with unhewn stone, showcasing durability and ancient expertise.</li>
            <li>Diverts water from the Kaveri River into canals for irrigation.</li>
            <li>Still operational and benefits thousands of farmers in the region.</li>
        </ul>
        <h2>Tourist Attractions</h2>
        <p>
            The dam is a popular tourist spot, offering scenic views and a serene atmosphere. It attracts visitors 
            for its historical significance, natural beauty, and as a great picnic destination.
        </p>
    </div>
    
</body>
</html>

airport.html :
<!DOCTYPE html>
<html lang="en">
<head>
 <title>Trichy International Airport</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        .container {
            max-width: 1000px;
            margin: 20px auto;
            padding: 20px;
            background: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }
        .image-container {
            text-align: center;
            margin-bottom: 20px;
        }
        .image-container img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        h1, h2 {
            color: #004aad;
            text-align: center;
        }
        .fo1{
            color: orange;
            text-align: center;
        }
        .fo2{
            color: blue;
            text-align: center;
        }
        .fo3{
            color: green;
            text-align: center;
        }
        p {
            color: #333;
            line-height: 1.8;
            text-align: justify;
        }
        
    </style>
</head>
<body>
    <header>
        <h1>Trichy International Airport</h1>
    </header>
    <div class="container">
        <div class="image-container">
            <img src="c:\Users\admin\OneDrive\Desktop\html folder\airport.jpg" alt="Trichy International Airport">
        </div>
        <h2 class="fo1">About Trichy International Airport</h2>
        <p>
            Tiruchirappalli International Airport, also known as Trichy International Airport, is one of the busiest and most important airports in Tamil Nadu, India. Located just 5 km south of the city center, the airport connects Trichy to major domestic and international destinations, making it a hub for travelers.
        </p>
        <h2 class="fo2">Facilities</h2>
        <p>
            The airport features modern facilities, including spacious terminals, duty-free shops, lounges, and parking facilities. It serves both domestic and international flights, with airlines offering connectivity to destinations in Southeast Asia, the Middle East, and other parts of India.
        </p>
        <h2 class="fo3">International Connectivity</h2>
        <p>
            Trichy International Airport is well-known for its frequent flights to countries such as Singapore, Malaysia, and the Gulf nations. It is particularly popular among the Tamil diaspora traveling between India and these regions.
        </p>
    </div>
    
</body>
</html>

```
## OUTPUT
 ![alt text](<Screenshot 2024-12-05 224528.png>)
 # Trichy
 ![alt text](<Screenshot 2024-12-05 224620.png>)
 ![alt text](<Screenshot 2024-12-05 224630.png>)
 # Theppakulam
 ![alt text](<Screenshot 2024-12-05 224603.png>)
 # NIT
 ![alt text](<Screenshot 2024-12-05 224758.png>)
 ![alt text](<Screenshot 2024-12-05 224810.png>)
 ![alt text](<Screenshot 2024-12-05 224819.png>)
 # Kallanai
 ![alt text](<Screenshot 2024-12-05 225354.png>)
 # Airport
 ![alt text](<Screenshot 2024-12-05 224700.png>)
## RESULT
The program for implementing image maps using HTML is executed successfully.
