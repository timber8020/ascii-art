#ascii-art-generator

ASCIIArt Generator class generate ascii-art for your image.

[written in c++, microsoft visualstudio 2019 Comunity Edition.]

ascii-art example :


```cpp
 char BRIGHTNESS[256] = {

        32,32,32,32,32,32,32,46,46,46,46,46,46,46,96,96,
        96,96,96,96,45,45,45,45,45,45,39,39,39,39,39,39,
        44,44,44,44,44,95,95,95,95,95,58,58,58,58,58,34,
        34,34,34,34,59,59,59,59,108,108,108,108,124,124,124,124,
        126,126,126,126,105,105,105,105,33,33,33,94,94,94,73,73,
        73,114,114,114,61,61,61,42,42,42,60,60,62,62,116,116,
        106,106,49,49,47,47,118,118,102,102,93,93,91,91,92,92,
        43,40,41,122,63,110,120,115,99,117,125,123,76,55,101,74,
        111,97,70,121,84,107,104,50,53,54,51,112,89,98,69,52,
        57,100,90,90,113,113,85,85,80,80,86,86,48,48,56,56,
        119,119,103,103,75,75,83,83,83,67,67,67,65,65,65,88,
        88,88,72,72,72,68,68,68,66,66,66,66,35,35,35,35,
        82,82,82,82,37,37,37,37,109,109,109,109,71,71,71,71,
        71,36,36,36,36,36,78,78,78,78,78,79,79,79,79,79,
        38,38,38,38,38,38,81,81,81,81,81,81,77,77,77,77,
        77,77,87,87,87,87,87,87,87,64,64,64,64,64,64,64
    };

    Image plant("../out/photo_1.jpg");

    plant.resizeWrtWidth(80);

    ASCIIArt art(&plant,BRIGHTNESS);
    art.generateArt();
```

## output
<img src="./out/screenshot_1.jpg" />

