CSS

background-color - ustalenie koloru tła, można go podać za pomocą nazwy koloru, za pomocą palety RGB rgb(255,0,0), 
lub za pomocą palety hex np #ff0000

width - szerokosc elementu, podajemy w "100%",  "100vw", "1000px"

height - wysokosc elementu, podajemy w "100%",  "100vh", "1000px"

display - nadanie elementowi sposobu wyświetlania się, w poziomie to "inline-block", w pionie to "block"

padding - dopełnienie czyli taki margines do środka elementu, podajemy np "5%", "20px"
padding: padding-top padding-right padding-bottom padding-left;

margin - margines do zewnątrz elementu, podajemy np "5%", "20px"
margin: margin-top margin-right margin-bottom margin-left;
margin: 0px 20% auto 10px;

color - kolor tekstu, podajemy np "red", "rgb(255,0,0)", "#ff0000"

text-decoration - sposób podkreślania tekstu, podajemy np "none", "undeline"

border - obramowanie elementu z każdej strony, podajemy np 1px solid black
border: (szerokość w pikselach = border-width) (rodzaj obramowania = border-style) (kolor obramowania = border-color)

border-top: 1px solid black; //tak samo jest z right, bottom left
border-top: (szerokość w pikselach) (rodzaj obramowania) (kolor obramowania)

border-radius: 20px  zaokrąglenie wszystkich rogów elementu
border-radius: border-top-left-radius border-top-right-radius border-bottom-right-radius border-bottom-left-radius   

font-style - styl czcionki np pochylenie czyli italic lub normal
font-weight - pogrubienie czcionki np. "100", "200", "300", "700", "900", "bold" "bolder" "lighter'

transition - stosowane w animacjach, czas przejścia w milisekundach lub sekundach np "3s"

opacity - przeźroczystoć elementu łącznie z czcionką
opacity:20%;

text-align - ustalenie pozycji elementu znajdującego się wewnątrz. Np wyśrodkowanie czcionki. Podajemy np "center", "right"

position - pozycja elementu w odniesieniu do elementów nad nim. "absolute", "static", "fixed", "relative"
