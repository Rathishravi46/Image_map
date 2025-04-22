# Ex04 Places Around Me
# Date:22/04/2025
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```
location1.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IMAGE MAPPING</title>
   
</head>
<body>
    <h1>Explore Locations Around My House</h1>
    <P>Click on the marked locations to learn more about each place.</P>

<img src="location1.png" usemap="#image-map">
<map name="image-map">
    <area target="" alt="Meenakshi Sundararajan Engineering college" title="Meenakshi Sundararajan Engineering college" href="meenakshi_college.html" coords="613,279,124" shape="circle"></area>
    <area target="" alt="Mahalingapuram Sree Ayyappan" title="Mahalingapuram Sree Ayyappan" href="temple.html" coords="993,218,94" shape="circle"></area>
    <area target="" alt="The Soorya Residency " title="The Soorya Residency " href="hotel.html" coords="1299,384,107" shape="circle"></area>
    <area target="" alt="kodambakkam fish market" title="kodambakkam fish market" href="fishmarket.html" coords="896,347,1092,461" shape="rect"></area>
    <area target="" alt="kodambakkam railway station" title="kodambakkam railway station" href="railwaystation.html" coords="920,563,90" shape="circle"></area>

</map>
    
</body>
</html>

meenakshi_college.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meenakshi Sundararajan Engneering College</title>
</head>
<body>
    <h1>Meenakshi Sundararajan Engneering College </h1>
    <img src="meenakshi.png"usemap="#image-map"style="width: 1000px;height:500px;">
    <p>The Engineering College was founded in 2001 by the educationist of South India, Professor K.R.Sundararajan. Meenakshi Sundararajan Engineering College is a part of the KRS Group of Institutions which includes the Indian Institute of Technical Education (IIET, est. 1947), Meenakshi College for Women and the Meenakshi Sundararajan School of Management. Institutions dedicated to impart qualitative education and research for both under-graduate and post-graduate education in the fields of Engineering, Arts, Science, Commerce and Management.</p>
</body>
</html>

temple.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mahalingapuram Sree Ayyappan</title>
</head>
<body>
    <h1> Mahalingapuram Sree Ayyappan Temple</h1>
    <img src="temple.png"usemap="#image-map"style="width: 1000px;height: 500px;">
    <p>Mahalingapuram Ayyappan Temple or Mahalingapuram Ayyappan - Guruvayurappan Temples is an Ayyappan Temple located at Mahalingapuram in the neighbourhood of Nungambakkam in Chennai district in the state of Tamil Nadu in the peninsular India with the geographical coordinates of 13°03′23.0″N 80°13′54.5″E (i.e., 13.056400°N, 80.231800°E) and at an altitude of about 34 m above the mean sea level. This temple complex contains Ayyappan temple and Guruvayurappan temple adjacent to each other. And is built based on Kerala Architecture. Swamy Ayyappan appears to devotees as in a sitting posture on Srichakra with the symbol of chinmuthra, the height being about 2 ft. The temple is constructed in the year 1974.</p>
    
</body>
</html>

hotel.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Soorya Residency</title>
</head>
<body>
    <h1>The Soorya Residency</h1>
    <img src="hotel.png"usemap="#image-map"style="width: 1000px;height:500px ;">
    <p>The Soorya Residency is a beautiful banquet hall in Chennai, Tamil Nadu. Weddings are a milestone and event that happens once in a lifetime. Everyone wants everything at their wedding to be memorable and perfect. The wedding venue speaks volumes about the event you wish to have. They are a name you should consider if you are looking for a suitable wedding venue in the city. The Soorya Residency will provide you with the best services to ensure that your wedding and its other functions are the most memorable ones. It is one of the best banquet halls in chennai</p>

</body>
</html>

fishmarket.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kodambakkam Fish Market</title>
</head>
<body>
    <h1>Kodambakkam Fish Market </h1>
    <img src="kodambakkam fish market.png"usemap="#image-map" style="width: 1000px;height:500px ;">
    <p>A fish market is a marketplace for selling fish and fish products. It can be dedicated to wholesale trade between fishermen and fish merchants, or to the sale of seafood to individual consumers, or to both. Retail fish markets, a type of wet market, often sell street food as well.

        Fish markets range in size from small fish stalls to large ones such as the great Tsukiji fish market in Tokyo, which turns over about 660,000 tonnes a year.[1]
        
        The term fish market can also refer to the process of fish marketing in general, but this article is concerned with physical marketplaces.</p>
    
</body>
</html>

railwaystation.html

<!DOCTYPE html>
<html lang="en">![6](https://github.com/user-attachments/assets/37bc1420-af3c-4c2d-a564-dada15c28be6)

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kodambakkam railway station</title>
</head>
<body>
    <h1>Kodambakkam railway station </h1>
    <img src="kodambakkam railway station.png"usemap="#image-map"style="width:900px;height:500px;">
    <p> Kodambakkam Railway Station is a railway station on the Chennai Beach–Chengalpattu section of the Chennai Suburban Railway Network. It serves the neighbourhood of Kodambakkam, Vadapalani, and Ashok Nagar. The railway station was already in existence when the Chennai Egmore-Kanchipuram suburban railway was opened in 1911.</p>
</body>
</html>
```
# OUTPUT
![image](https://github.com/user-attachments/assets/f93d9108-1d0c-4f16-820c-10e0bb05cd44)
![image](https://github.com/user-attachments/assets/227771c4-122e-4c88-824b-a66ce85c8cdc)
![image](https://github.com/user-attachments/assets/d0fbb51c-119b-463f-8aba-a021aa2e0400)
![image](https://github.com/user-attachments/assets/a0ebd2a2-5894-4c56-89d0-ccf507a52616)
![image](https://github.com/user-attachments/assets/abccce99-de55-4f93-91ee-257e1c46e24b)
![image](https://github.com/user-attachments/assets/d6e7ef21-729f-422b-855d-89bdaab4d3c1)

# RESULT
The program for implementing image maps using HTML is executed successfully.
