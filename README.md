/* Mobilos nézet */
@media (max-width: 768px) { 

    header {
        font-size: 100px; /* Kisebb címsor betűméret */
        text-align: center;
        padding: 0px; /* Nincs extra padding */
        display: flex; /* Flexbox a logó és a cím rendezéséhez */
        flex-direction: column; /* Az elemek egymás alatt */
        justify-content: center; /* Középre igazítás */
        align-items: center; /* Középre igazítás */
    }
    
    footer {
        display: flex;
    }
    header .logo {
        height: 100px; /* Nagyobb logó magasság */
        width: auto; /* Arányosan igazodik a szélesség */
        margin-bottom: -10px; /* A logó alatti margó csökkentése, hogy a cím közelebb kerüljön */
    }
    
    h1 {
        font-size: 30px; /* Kisebb címsor betűméret */
        margin-top: 10px; /* Kicsi margó a cím tetején, hogy lejjebb kerüljön */
        margin-bottom: -30px; /* A margó csökkentése alul */
        text-align: center; /* Cím középre igazítása */
    }
    
    .left-section {
        display: flex; /* Flexbox a gyerekek elrendezéséhez */
        align-items: center; /* Függőleges középre igazítás */
        gap: 5px; /* Távolság az `img` és a `p` között */
        margin-right: auto;
        font-size: 12px;
        margin-top: -40px;
    }
    
    .left-section img {
        width: 25px; /* Kép szélessége */
        margin: 0; /* Margók eltávolítása a pontos igazításhoz */
    }
    
    .left-section p {
        font-size: 0;
        color: none;
        margin: 0; /* Margók eltávolítása a pontos igazításhoz */
    }

    .right-section {
        display: flex; /* Flexbox az `img` és `p` egymás mellé rendezéséhez */
        align-items: center; /* Függőleges középre igazítás */
        gap: 5px; /* Távolság az `img` és a `p` között */
        margin-top: -42px; /* Távolság a `header-top` alatt */
        font-size: 12px; /* Betűméret */
        width: 100%; /* Teljes szélesség */
        justify-content: flex-end; /* Balra igazítás */
       
    }
    
    .right-section img {
        width: 20px; /* Szélesség fixen */
        margin: 0; /* Margók eltávolítása */
    }

    #bottom {
        position: fixed;
        bottom: 5px;
        right: 5px;
        border-radius: 25px; /* Arányosan kisebb görbület */
    }
    
    button {
        padding: 0px 2px; /* Csökkentett padding */
        background-color: #efc1ba;
        color: black;
        border: none;
        cursor: pointer;
        border-radius: 15px; /* Csökkentett görbület */
        box-shadow: -4px -4px 6px #fed7d1,
                    4px 4px 6px #a78782; /* Árnyék csökkentése */
        font-size: 12px; /* Kisebb betűméret */
    }
    
    button:hover {
        background-color: #efc1ba;
        box-shadow: 1px 1px 1px #fed7d1,
                    -1px -1px 1px #a78782; /* Hover árnyék is kisebb */
    }
    
    .dropdown button {
        background-color: #fff;
        border: none;
        width: 20px; /* Csökkentett szélesség */
        font-size: 1px; /* Kisebb betűméret */
        cursor: pointer;
        border-radius: 3px; /* Kisebb görbület */
        
    }

    footer {
        background-image: url("Márvány.jpg");
        color: black;
        text-align: center;
        font-size: 15px;
        padding: 20px;
        margin: 10px;
        margin-top: 1800px;
    }

    .card {
        margin: 0; 
        margin-top: 652px;
        position: absolute; 
        left: 50%; 
        top: 65%; 
        transform: translate(-50%, -50%); 
        width: 250px;
        height: 250px;
        background-image: url("Márvány.jpg");
        display: flex;
        overflow: hidden;
        transition: 0.5s ease-in-out; 
        border-radius: 20px;
        box-shadow: -6px -6px 10px #ffe8e4,
                    6px 6px 10px #a78782;
    }
    
    .card:hover {
        width: 450px;
        background: #efc1ba;
        padding: 6px 6px;
        box-shadow: 2px 2px 2px #ffe8e4,
                    -2px -2px 2px #a78782;
        border-radius: 20px;
        transition: all 0.3s ease;
    }
    
    .card .imgBx {
        position: relative;
        display: flex; 
        justify-content: center; 
        align-items: center; 
        width: 250px;
        height: 250px; 
        background-image: url("Márvány.jpg");
        background: #bf808077;
        padding: 2px 20px;
        border-radius: 20px;
        transition: all 0.3s ease;
    }
    
    .card .imsrc {
        width: 20px;
        height: 20px;
        border-radius: 20px;
    }
    
    .card h3 {
        font-size: 18px;
        text-align: center;
        padding: 2px 6px;
        margin: 3px;
    }
    
    .card h4 {
        font-size: 16px;
        text-align: flex;
        padding: 2px 6px;
        margin: 0px;
    }
    
    .card p {
        font-size: 14px;
        text-align: center;
        padding: 2px 6px;
        margin: 12px;
    }
    
    .card li {
        font-size: 13px;
        text-align: center;
        justify-content: center;
        align-items: center;
        padding: 2px 6px;
        margin: -20px;
    }
    
    .card h2 {
        font-size: 22px;
        text-align: center;
        padding: 2px 6px;
        margin: 40px;
    }
    
    .card2 {
        margin: 0; 
        margin-top: 652px;
        position: absolute; 
        left: 50%; 
        top: 110%; 
        transform: translate(-50%, -50%); 
        width: 250px;
        height: 250px;
        background-image: url("Márvány.jpg");
        display: flex;
        overflow: hidden;
        transition: 0.5s ease-in-out; 
        border-radius: 20px;
        box-shadow: -6px -6px 10px #ffe8e4,
                    6px 6px 10px #a78782;
    }
    
    .card2:hover {
        width: 450px;
        background: #efc1ba;
        padding: 6px 6px;
        box-shadow: 2px 2px 2px #ffe8e4,
                    -2px -2px 2px #a78782;
        border-radius: 20px;
        transition: all 0.3s ease;
    }
    
    .card2 .imgBx2 {
        position: relative;
        display: flex; 
        justify-content: center; 
        align-items: center; 
        width: 250px;
        height: 250px; 
        background-image: url("Márvány.jpg");
        background: #bf808077;
        padding: 2px 55px;
        border-radius: 20px;
        transition: all 0.3s ease;
    }
    
    .card2 .imsrc {
        width: 20px;
        height: 20px;
        border-radius: 20px;
    }
    
    .card2 h3 {
        font-size: 18px;
        text-align: center;
        padding: 2px 6px;
        margin: 3px;
    }
    
    .card2 h4 {
        font-size: 16px;
        text-align: flex;
        padding: 2px 6px;
        margin: 0px;
    }
    
    .card2 p {
        font-size: 14px;
        text-align: center;
        padding: 2px 6px;
        margin: 12px;
    }
    
    .card2 li {
        font-size: 13px;
        text-align: center;
        justify-content: center;
        align-items: center;
        padding: 2px 6px;
        margin: -20px;
    }
    
    .card2 h2 {
        font-size: 18px;
        text-align: center;
        padding: 2px 6px;
        margin: 30px;
    }
    
    .card3 {
        margin: 0; 
        margin-top: 652px;
        position: absolute; 
        left: 50%; 
        top: 155%; 
        transform: translate(-50%, -50%); 
        width: 250px;
        height: 250px;
        background-image: url("Márvány.jpg");
        display: flex;
        overflow: hidden;
        transition: 0.5s ease-in-out; 
        border-radius: 20px;
        box-shadow: -6px -6px 10px #ffe8e4,
                    6px 6px 10px #a78782;
    }
    
    .card3:hover {
        width: 450px;
        background: #efc1ba;
        padding: 6px 6px;
        box-shadow: 2px 2px 2px #ffe8e4,
                    -2px -2px 2px #a78782;
        border-radius: 20px;
        transition: all 0.3s ease;
    }
    
    .card3 .imgBx3 {
        position: relative;
        display: flex; 
        justify-content: center; 
        align-items: center; 
        width: 250px;
        height: 250px; 
        background-image: url("Márvány.jpg");
        background: #bf808077;
        padding: 2px 15px;
        border-radius: 20px;
        transition: all 0.3s ease;
    }
    
    .card3 .imsrc {
        width: 20px;
        height: 20px;
        border-radius: 20px;
    }
    
    .card3 h3 {
        font-size: 22px;
        text-align: center;
        padding: 2px 6px;
        margin: 3px;
    }
    
    .card3 p {
        font-size: 14px;
        text-align: center;
        padding: 2px 6px;
        margin: 12px;
    }
    
    .card3 h2 {
        font-size: 22px;
        text-align: center;
        padding: 2px 6px;
        margin: 40px;
    }
    
    .card4 {
        margin: 0; 
        margin-top: 652px;
        position: absolute; 
        left: 50%; 
        top: 200%; 
        transform: translate(-50%, -50%); 
        width: 250px;
        height: 250px;
        background-image: url("Márvány.jpg");
        display: flex;
        overflow: hidden;
        transition: 0.5s ease-in-out; 
        border-radius: 20px;
        box-shadow: -6px -6px 10px #ffe8e4,
                    6px 6px 10px #a78782;
    }
    
    .card4:hover {
        width: 450px;
        background: #efc1ba;
        padding: 6px 6px;
        box-shadow: 2px 2px 2px #ffe8e4,
                    -2px -2px 2px #a78782;
        border-radius: 20px;
        transition: all 0.3s ease;
    }
    
    .card4 .imgBx4 {
        position: relative;
        display: flex; 
        justify-content: center; 
        align-items: center; 
        width: 250px;
        height: 250px; 
        background-image: url("Márvány.jpg");
        background: #bf808077;
        padding: 2px 10px;
        border-radius: 20px;
        transition: all 0.3s ease;
    }
    
    .card4 .imsrc {
        width: 25px;
        height: 25px;
        border-radius: 20px;
    }
    
    .card4 h3 {
        font-size: 22px;
        text-align: center;
        padding: 2px 6px;
        margin: 3px;
    }
    
    
    .card4 p {
        font-size: 14px;
        text-align: center;
        padding: 2px 6px;
        margin: 12px;
    }
    
    .card4 h2 {
        font-size: 22px;
        text-align: center;
        padding: 2px 6px;
        margin: 40px;
    }
    
    .card5 {
        margin: 0; 
        margin-top: 652px;
        position: absolute; 
        left: 50%; 
        top: 245%; 
        transform: translate(-50%, -50%); 
        width: 250px;
        height: 250px;
        background-image: url("Márvány.jpg");
        display: flex;
        overflow: hidden;
        transition: 0.5s ease-in-out; 
        border-radius: 20px;
        box-shadow: -6px -6px 10px #ffe8e4,
                    6px 6px 10px #a78782;
    }
    
    .card5:hover {
        width: 450px;
        background: #efc1ba;
        padding: 6px 6px;
        box-shadow: 2px 2px 2px #ffe8e4,
                    -2px -2px 2px #a78782;
        border-radius: 20px;
        transition: all 0.3s ease;
    }
    
    .card5 .imgBx5 {
        position: relative;
        display: flex; 
        justify-content: center; 
        align-items: center; 
        width: 250px;
        height: 250px; 
        background-image: url("Márvány.jpg");
        background: #bf808077;
        padding: 2px 2px;
        border-radius: 20px;
        transition: all 0.3s ease;
    }
    
    .card5 .imsrc {
        width: 20px;
        height: 20px;
        border-radius: 20px;
    }
    
    .card5 h3 {
        font-size: 22px;
        text-align: center;
        padding: 2px 6px;
        margin: 3px;
    }
    
    .card5 p {
        font-size: 14px;
        text-align: center;
        padding: 2px 6px;
        margin: 12px;
    }
    
    .card5 h2 {
        font-size: 22px;
        text-align: center;
        padding: 2px 6px;
        margin: 40px;
    }
    .card6 {
        margin: 0; 
        margin-top: 652px;
        position: absolute; 
        left: 50%; 
        top: 290%; 
        transform: translate(-50%, -50%); 
        width: 250px;
        height: 250px;
        background-image: url("Márvány.jpg");
        display: flex;
        overflow: hidden;
        transition: 0.5s ease-in-out; 
        border-radius: 20px;
        box-shadow: -6px -6px 10px #ffe8e4,
                    6px 6px 10px #a78782;
    }
    
    .card6:hover {
        width: 450px;
        background: #efc1ba;
        padding: 6px 6px;
        box-shadow: 2px 2px 2px #ffe8e4,
                    -2px -2px 2px #a78782;
        border-radius: 20px;
        transition: all 0.3s ease;
    }
    
    .card6 .imgBx6 {
        position: relative;
        display: flex; /* Flexbox engedélyezése */
        justify-content: center; /* Vízszintes középre helyezés */
        align-items: center; /* Függőleges középre helyezés */
        width: 250px;
        height: 250px; /* Magasság (egyezik a szélességgel) */
        background-image: url("Márvány.jpg");
        background: #bf808077;
        padding: 2px 45px;
        border-radius: 20px;
        transition: all 0.3s ease;
    }
    
    .card6 .imsrc {
        width: 20px;
        height: 20px;
        border-radius: 20px;
    }
    
    .card6 h3 {
        font-size: 22px;
        text-align: center;
        padding: 2px 6px;
        margin: 3px;
    }
    
    
    .card6 p {
        font-size: 14px;
        text-align: center;
        padding: 2px 6px;
        margin: 12px;
    }
    
    .card6 h2 {
        font-size: 18px;
        text-align: center;
        padding: 2px 6px;
        margin: 40px;
    }

} 
/* Laptop nézet (1024px és nagyobb) */
@media (min-width: 1024px) {
    header {
        background-image: url("Márvány.jpg");
        color: black;
        font-weight: 1000;
        font-size: 100px;
        display: center; /* Flexbox a logó és a cím rendezéséhez */
        align-items: center; /* Függőleges középre igazítás */
        justify-content: flex-start; /* A logó bal oldalon marad */
        padding: 10px 20px;
    }

    .header-top {
        display: center; /* Flexbox a logó és a h1 elrendezéséhez */
        align-items: center; /* Középre igazítás vertikálisan */
        justify-content: center; /* Balra igazítás a logónak és a címnek */
        width: 100%; /* Teljes szélesség */
        gap: 5px; /* Távolság a logó és a h1 között */
    }

    header .logo {
        height: 200px; /* A logó magassága */
        width: auto; /* Arányos szélesség */
        margin-right: -30px; /* Hézag a logó és a cím között */
        display: inline-block; /* Azonos sorban tartja a logóval */
        vertical-align: middle;
    }
    
    h1 {
        font-size: 70px; /* A cím fontmérete */
        margin: 0; /* Hézagok eltávolítása */
        display: inline-block; /* Azonos sorban tartja a logóval */
        text-align: center; /* A cím balra igazítása */
        flex-grow: 1; /* A címsor kitölti a fennmaradó helyet */
    }
    
    .címsor1 {
        font-family: 'English', sans-serif;
        font-weight: 1000;
        color: black;
        text-align: center;
        font-size: 32px;
    }

    .left-section {
        display: flex; 
        align-items: center; 
        gap: 10px; 
        margin-top: 40px; 
        font-size: 12px; 
        width: 100%; 
        justify-content: flex-start; 
        vertical-align: middle;
    }
    
    .left-section img {
        height: auto; 
        width: 40px; 
        margin: 0; 
        vertical-align: middle;
        display: inline-block;
    }
    
    .left-section p {
        font-size: 15px; /* Betűméret */
        color: black; /* Szöveg színe */
        margin: 0; /* Margók eltávolítása */
        vertical-align: middle;
        display: inline-block;
    }
    .right-section {
        display: flex; /* Flexbox az `img` és `p` egymás mellé rendezéséhez */
        align-items: center; /* Függőleges középre igazítás */
        gap: 10px; /* Távolság az `img` és a `p` között */
        margin-top: -50px; /* Távolság a `header-top` alatt */
        font-size: 12px; /* Betűméret */
        width: 100%; /* Teljes szélesség */
        justify-content: flex-end; /* Balra igazítás */
    }
    
    .right-section img {
        height: auto; /* Magasság automatikus */
        width: 35px; /* Szélesség fixen */
        margin: 0; /* Margók eltávolítása */
    }

    #bottom {
        position: fixed;
        bottom: 20px;
        right: 20px;
        border-radius: 100px;
    }
    
    
    button {
        padding: 1px 20px;
        background-color: #efc1ba;
        color: black;
        border: none;
        cursor: pointer;
        border-radius: 25px;
        box-shadow: -6px -6px 10px #fed7d1,
                    6px 6px 10px #a78782;
    
    }
    
    button:hover {
        background-color: #efc1ba;
        box-shadow: 2px 2px 2px #fed7d1,
                    -2px -2px 2px #a78782;
    }
    
    .dropdown button {
        background-color: #fff;
        border: none;
        width: 120px;
        height: 40px;
        font-weight: bold;
        cursor: pointer;
        border-radius: 5px;
        box-shadow: white;
        text-align: center; 
    }
    

    footer {
        background-image: url("Márvány.jpg");
        color: black;
        text-align: center;
        font-size: 15px;
        padding: 20px;
        margin: 10px; 
    }

    .card-container {
        display: flex;
        flex-wrap: wrap; /* Több sorban jelenjenek meg a kártyák, ha szükséges */
        justify-content: center; /* Középre igazítás */
        gap: 20px; /* Távolság a kártyák között */
        padding: 20px;
        margin: 0 auto;
    }
    
    .card {
        margin: 30px;
        margin-top: 40px;
        position: relative;
        width: 250px;
        height: 250px;
        background-image: url("Márvány.jpg");
        display: flex;
        overflow: hidden;
        transition: 0,5s ease-in-out;
        border-radius: 20px;
        box-shadow: -6px -6px 10px #ffe8e4,
                        6px 6px 10px #a78782;
                        
    }
    
    .card:hover {
        width: 450px;
        background: #efc1ba;
        padding: 2px 2px;
        box-shadow: 2px 2px 2px #ffe8e4,
                    -2px -2px 2px #a78782;
        border-radius: 20px;
        transition: all 0.3s ease;
    }
    
    .card .imgBx {
        position: relative;
        min-width: 250px;
        background-image: url("Márvány.jpg");
        background:#bf808077;
        padding: 2px 2px;
        border-radius: 20px;
        transition: all 0.3s ease;
        
    }
    
    .card .imsrc {
        width: 20px;
        height: 20px;
        border-radius: 20px;
    }
    
    .card h3 {
        font-size: 22px;
        text-align: center;
        padding: 2px 6px;
        margin: 3px;
    }
    .card h4 {
        font-size: 18px;
        text-align: flex;
        padding: 2px 6px;
        margin: 0px;
    }
    .card p {
        font-size: 14px;
        text-align: center;
        padding: 2px 6px;
        margin: 12px;
    }
    
    .card li {
        font-size: 13px;
        text-align: center;
        justify-content: center;
        align-items: center;
        padding: 2px 6px;
        margin: -20px;
    }
    
    .card h2 {
        font-size: 22px;
        text-align: center;
        padding: 2px 6px;
        margin: 40px;
    }
    
    .card2 {
        margin: 30px;
        position: relative;
        width: 250px;
        height: 250px;
        background-image: url("Márvány.jpg");
        display: flex;
        overflow: hidden;
        transition: 0,5s ease-in-out;
        border-radius: 20px;
        box-shadow: -6px -6px 10px #ffe8e4,
                        6px 6px 10px #a78782;
                        
    }
    
    .card2:hover {
        width: 450px;
        background: #efc1ba;
        padding: 2px 2px;
        box-shadow: 2px 2px 2px #ffe8e4,
                    -2px -2px 2px #a78782;
        border-radius: 20px;
        transition: all 0.3s ease;
    }
    
    .card2 .imgBx2 {
        position: relative;
        min-width: 250px;
        background-image: url("Márvány.jpg");
        background:#bf808077;
        padding: 2px 2px;
        border-radius: 20px;
        transition: all 0.3s ease;
        
    }
    
    .card2 .imsrc {
        width: 20px;
        height: 20px;
        border-radius: 20px;
    }
    
    .card2 h3 {
        font-size: 22px;
        text-align: center;
        padding: 2px 6px;
        margin: 3px;
    }
    .card2 h4 {
        font-size: 18px;
        text-align: flex;
        padding: 2px 6px;
        margin: 0px;
    }
    .card2 p {
        font-size: 14px;
        text-align: center;
        padding: 2px 6px;
        margin: 12px;
    }
    
    .card2 li {
        font-size: 13px;
        text-align: center;
        justify-content: center;
        align-items: center;
        padding: 2px 6px;
        margin: -20px;
    }
    
    .card2 h2 {
        font-size: 22px;
        text-align: center;
        padding: 2px 6px;
        margin: 40px;
    }
    
    .card3 {
        margin: 15px;
        margin-top: 635px;
        position: absolute; 
        right: 20px; /* Az elem távolsága a jobb széltől */
        top: 50%; /* Az elem középre igazítása a függőleges tengelyen */
        transform: translateY(-50%); 
        width: 250px;
        height: 250px;
        background-image: url("Márvány.jpg");
        display: flex;
        overflow: hidden;
        transition: 0.5s ease-in-out; 
        border-radius: 20px;
        box-shadow: -6px -6px 10px #ffe8e4,
                    6px 6px 10px #a78782;
    }
    
    .card3:hover {
        width: 450px;
        background: #efc1ba;
        padding: 2px 2px;
        box-shadow: 2px 2px 2px #ffe8e4,
                    -2px -2px 2px #a78782;
        border-radius: 20px;
        transition: all 0.3s ease;
    }
    
    .card3 .imgBx3 {
        position: relative;
        min-width: 250px;
        background-image: url("Márvány.jpg");
        background: #bf808077;
        padding: 2px 2px;
        border-radius: 20px;
        transition: all 0.3s ease;
    }
    
    .card3 .imsrc {
        width: 20px;
        height: 20px;
        border-radius: 20px;
    }
    
    .card3 h3 {
        font-size: 22px;
        text-align: center;
        padding: 2px 6px;
        margin: 3px;
    }
   
    
    .card3 p {
        font-size: 14px;
        text-align: center;
        padding: 2px 6px;
        margin: 12px;
    }
    
    .card3 h2 {
        font-size: 22px;
        text-align: center;
        padding: 2px 6px;
        margin: 40px;
    }
    
    .card4 {
        margin: 15px;
        margin-top: 915px;
        position: absolute; 
        right: 20px; 
        top: 50%; 
        transform: translateY(-50%); 
        width: 250px;
        height: 250px;
        background-image: url("Márvány.jpg");
        display: flex;
        overflow: hidden;
        transition: 0.5s ease-in-out; 
        border-radius: 20px;
        box-shadow: -6px -6px 10px #ffe8e4,
                    6px 6px 10px #a78782;
    }
    
    .card4:hover {
        width: 450px;
        background: #efc1ba;
        padding: 2px 2px;
        box-shadow: 2px 2px 2px #ffe8e4,
                    -2px -2px 2px #a78782;
        border-radius: 20px;
        transition: all 0.3s ease;
    }
    
    .card4 .imgBx4 {
        position: relative;
        min-width: 250px;
        background-image: url("Márvány.jpg");
        background: #bf808077;
        padding: 2px 2px;
        border-radius: 20px;
        transition: all 0.3s ease;
    }
    
    .card4 .imsrc {
        width: 20px;
        height: 20px;
        border-radius: 20px;
    }
    
    .card4 h3 {
        font-size: 22px;
        text-align: center;
        padding: 2px 6px;
        margin: 3px;
    }
    
    .card4 p {
        font-size: 14px;
        text-align: center;
        padding: 2px 6px;
        margin: 12px;
    }
    
    .card4 h2 {
        font-size: 22px;
        text-align: center;
        padding: 2px 6px;
        margin: 40px;
    }

    .card5 {
        margin: 0; 
        margin-top: 635px;
        position: absolute; 
        left: 50%; 
        top: 50%; 
        transform: translate(-50%, -50%); 
        width: 250px;
        height: 250px;
        background-image: url("Márvány.jpg");
        display: flex;
        overflow: hidden;
        transition: 0.5s ease-in-out; 
        border-radius: 20px;
        box-shadow: -6px -6px 10px #ffe8e4,
                    6px 6px 10px #a78782;
    }
    
    .card5:hover {
        width: 450px;
        background: #efc1ba;
        padding: 2px 2px;
        box-shadow: 2px 2px 2px #ffe8e4,
                    -2px -2px 2px #a78782;
        border-radius: 20px;
        transition: all 0.3s ease;
    }
    
    .card5 .imgBx5 {
        position: relative;
        display: flex; 
        justify-content: center; 
        align-items: center; 
        width: 250px;
        height: 250px; 
        background-image: url("Márvány.jpg");
        background: #bf808077;
        padding: 2px 2px;
        border-radius: 20px;
        transition: all 0.3s ease;
    }
    .card5 .imsrc {
        width: 20px;
        height: 20px;
        border-radius: 20px;
    }
    
    .card5 h3 {
        font-size: 22px;
        text-align: center;
        padding: 2px 6px;
        margin: 3px;
    }
    
    .card5 p {
        font-size: 14px;
        text-align: center;
        padding: 2px 6px;
        margin: 12px;
    }
    
   
    .card5 h2 {
        font-size: 22px;
        text-align: center;
        padding: 2px 6px;
        margin: 40px;
    }

    .card6 {
        margin: 0; /* Margin nullázása, hogy ne befolyásolja a pozícionálást */
        margin-top: 915px;
        position: absolute; 
        left: 50%; /* Vízszintesen a középpontba */
        top: 50%; /* Függőlegesen a középpontba */
        transform: translate(-50%, -50%); /* Finomhangolás, hogy pontosan középen legyen */
        width: 250px;
        height: 250px;
        background-image: url("Márvány.jpg");
        display: flex;
        overflow: hidden;
        transition: 0.5s ease-in-out; 
        border-radius: 20px;
        box-shadow: -6px -6px 10px #ffe8e4,
                    6px 6px 10px #a78782;
    }
    
    .card6:hover {
        width: 450px;
        background: #efc1ba;
        padding: 2px 2px;
        box-shadow: 2px 2px 2px #ffe8e4,
                    -2px -2px 2px #a78782;
        border-radius: 20px;
        transition: all 0.3s ease;
    }
    
    .card6 .imgBx6 {
        position: relative;
        display: flex; 
        justify-content: center; /* Vízszintes középre helyezés */
        align-items: center; /* Függőleges középre helyezés */
        width: 250px;
        height: 250px; 
        background-image: url("Márvány.jpg");
        background: #bf808077;
        padding: 2px 45px;
        border-radius: 20px;
        transition: all 0.3s ease;
       
    }
    
    .card6 .imsrc {
        width: 20px;
        height: 20px;
        border-radius: 20px;
    }
    
    .card6 h3 {
        font-size: 22px;
        text-align: center;
        padding: 2px 6px;
        margin: 3px;
    }
    
    .card6 p {
        font-size: 14px;
        text-align: center;
        padding: 2px 6px;
        margin: 12px;
    }
    
   
    .card6 h2 {
        font-size: 18px;
        text-align: center;
        padding: 2px 6px;
        margin: 40px;
    }
   
}

/* Általános stílusok */
header {
    background-image: url("Márvány.jpg");
    color: black;
    font-weight: 1000;
    font-size: 80px;
    display: flex; /* Flexbox a logó és a cím rendezéséhez */
    align-items: center; /* Függőleges középre igazítás */
    justify-content: center; /* A logó bal oldalon marad */
    padding: 20px 30px;
}

body {
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #efc1ba;
    color: black;
    text-align: center;
    font-size: 20px;
    
}

header, nav, section {
    padding: 10px;
    margin: 10px;
}

.head {
    display: inline;
    color: black;
    text-align: center;
    font-weight: 1000;
    font-size: 30px;
}

.head p {
    display: inline-block;
    margin-right: 20px;
    font-size: 100px;
}

.head img {
    width: 20px;
    height: 20px;
    vertical-align: middle;
}

figure {
    margin: 10px auto;
    text-align: center;
}

figure img {
    width: 200px; /* Fix szélesség */
    height: auto; /* Arányos magasság */
}
