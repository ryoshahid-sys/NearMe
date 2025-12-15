# Ex04 Places Around Me
## Date: 

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
### home.html
```
<img src="Screenshot 2025-12-15 092729.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Hotel Hills" title="Hotel Hills" href="hotel.html" coords="217,214,409,290" shape="rect">
    <area target="" alt="Vegrov" title="Vegrov" href="vegrov.html" coords="599,310,418,255" shape="rect">
    <area target="" alt="Kalika Alayam" title="Kalika Alayam" href="temple.html" coords="621,366,681,512,844,435,844,328,698,343,673,332,670,284" shape="poly">
</map>
```
### hotel.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <IMG SRC="hotel.jpg"HEIGHT="500"WIDTH="1000"BORDER=6>
        <p>Short & Simple

Hotel Hills, Hosur offers comfortable accommodation with warm hospitality, making it an ideal choice for business and leisure travelers. Conveniently located, the hotel provides easy access to major industrial areas and city attractions.

Professional / Website Style

Hotel Hills, Hosur is a well-appointed hotel designed to provide a relaxing and convenient stay. With comfortable rooms, modern amenities, and attentive service, the hotel caters to corporate guests, families, and tourists seeking a pleasant experience in Hosur.

Marketing / Promotional

Experience comfort and convenience at Hotel Hills, Hosur. Nestled in a prime location, the hotel combines elegant interiors, modern facilities, and friendly service to ensure a memorable stay for both business and leisure travelers.

Hospitality-Focused

At Hotel Hills, Hosur, guests are welcomed with comfort, cleanliness, and care. The hotel features thoughtfully designed rooms, essential amenities, and a peaceful atmosphere, making it a perfect retreat after a busy day in the city. </p>
</body>
</html>
```

### temple.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <IMG SRC="temple.jpg"HEIGHT="500"WIDTH="1000"BORDER=6>
    <p>Here are some **description options for Kalika Alayam Temple, Hosur**, in different styles:

 Short & Simple

Kalika Alayam Temple, Hosur** is a revered spiritual place dedicated to Goddess Kalika, known for its peaceful atmosphere and traditional worship practices.

Devotional / Spiritual

Kalika Alayam Temple, Hosur** is a sacred shrine where devotees seek the blessings of Goddess Kalika. The temple is known for its serene surroundings, divine energy, and regular poojas that attract devotees from nearby areas.

 Informative / Cultural

Kalika Alayam Temple, Hosur** stands as an important spiritual landmark, reflecting rich religious traditions and cultural heritage. Devotees visit the temple to offer prayers, participate in festivals, and experience spiritual calm.

 Peaceful / Visitor-Focused

Nestled in a calm environment, **Kalika Alayam Temple, Hosur** offers a tranquil space for prayer and meditation. The temple’s spiritual ambiance and devotion-filled atmosphere make it a cherished place for workship.
</p>
</body>
</html>
```

### vegrov.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <IMG SRC="vegrov.jpg"HEIGHT="500"WIDTH="1000"BORDER=6>
    <p>Short Description

Vegrov Aquarium, Hosur is a one-stop destination for aquarium lovers, offering a wide variety of ornamental fish, aquariums, and accessories to create and maintain beautiful aquatic setups.

Professional / Business Style

Vegrov Aquarium, Hosur specializes in ornamental fish, aquariums, and complete aquarium accessories. With quality products and expert guidance, the store caters to beginners and experienced aquarium enthusiasts alike.

Customer-Friendly / Marketing Style

Discover the beauty of aquatic life at Vegrov Aquarium, Hosur. From colorful ornamental fish to stylish aquariums and essential accessories, we provide everything you need to build and maintain a healthy, vibrant aquarium.

Detailed Description

Vegrov Aquarium, Hosur offers a wide range of freshwater fish, aquariums, fish food, filters, plants, and accessories. Known for quality and reliable service, the store helps customers create stunning and well-maintained aquariums for homes and offices.</p>
</body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2025-12-15 104414.png>)
![alt text](<Screenshot 2025-12-15 104425.png>)
![alt text](<Screenshot 2025-12-15 104505.png>)
![alt text](<Screenshot 2025-12-15 104436.png>)





## RESULT
The program for implementing image maps using HTML is executed successfully.
