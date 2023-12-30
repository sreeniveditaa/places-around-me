# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Date: 

### Step 1:
Create a django admin interface.
### Step 2:
download your city map from google.
### step 3:
using ``` <map>``` tag name the map.
### step 4:
create clickable regions in the image using ``` <area>```tag.
### step 5:
WRite HTML programs for all the regions identified.
### step 6:
Execute the programs and publish them.
## Code:
```
map.html
<!DOCTYPE html>
<html>
    <head>
        <title>image maps devoloper</title>
    </head>
    <body>
        <h1>image maps demo </h1>
        <img src="nivi-hometown.png" usemap="#image_map">
<map name="image_map">
  <area alt="amaravathystores" title="amaravathystores" href="store.html" coords="735,332,900,448" shape="rect">
  <area alt="new prince school" title="new prince school" href="school.html" coords="108,274,536,657" shape="rect">
  <area alt="saravana print store" title="saravana print store" href="print.html" coords="614,131,755,260" shape="rect">
  <area alt="corporation park" title="corporation park" href="park.html" coords="1089,630,1250,708" shape="rect">
  <area alt="arya tatoos" title="arya tatoos" href="tatoo.html" coords="581,612,790,681" shape="rect">
</map>

    </body>
</html>

park.html
<!DOCTYPE html>
<html>
    <head>
        <title>corporation park</title>
    </head>
    <body>
        <h1>CORPORATION PARK</h1>
    </body>
</html>

print.html

<!DOCTYPE html>
<html>
    <head>
        <title>saravana print shop</title>
    </head>
    <body>
        <h1>SARAVANA PRINT STORE</h1>
    </body>
</html>

school.html

<!DOCTYPE html>
<html>
    <head>
        <title>new prince school</title>
    </head>
    <body>
        <h1>NEW PTRINCE SHRI BHAVANI SENIOR SECONDARY SCHOOL</h1>
    </body>
</html>

store.html

<!DOCTYPE html>
<html>
    <head>
        <title>amaravathy stores</title>
    </head>
    <body>
        <h1>AMARAVATHY STORES</h1>
    </body>
</html>

tatoo.html

<!DOCTYPE html>
<html>
    <head>
        <title>arya tatoos</title>
    </head>
    <body>
        <h1>ARYA TATTOOS</h1>
    </body>
</html>

```

## Output:
![0](https://github.com/sreeniveditaa/places-around-me/assets/147473268/a8661960-8b47-4098-bbea-d72b92dd731d)
![1](https://github.com/sreeniveditaa/places-around-me/assets/147473268/b554f5b2-416a-4eb4-9b24-9d254e51ef81)
![2](https://github.com/sreeniveditaa/places-around-me/assets/147473268/02425a70-639b-4ea8-9342-31718a9f238a)
![3](https://github.com/sreeniveditaa/places-around-me/assets/147473268/fcbe5e8e-f2e6-4e5c-bf2e-b17581fbbe21)
![4](https://github.com/sreeniveditaa/places-around-me/assets/147473268/e4c4ec6a-4119-4840-a6a3-43fca6555f47)
![5](https://github.com/sreeniveditaa/places-around-me/assets/147473268/b2a788ad-9a0f-47e7-b38e-84d09d3e112e)


## Result:
The image maps has been created successfully.
