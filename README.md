Projektauswertung & Reflexion

Was hat gut funktioniert?
•	Schneller Charakter-Wechsel: Der Wechsel zwischen den Figuren läuft komplett über CSS (:checked ~ .card). Das spart JavaScript, ist super schnell und läuft fehlerfrei.
•	Passendes Design: Die Farben (Orange, Schwarz, Gelb) und schrägen Formen passen perfekt zum Anime. Dank CSS-Variablen ist das Design überall einheitlich.
•	Barrierefreiheit: Wichtige ARIA-Hilfen für das Mobile-Menü und die Formular-Nachrichten wurden direkt im Code eingebaut.

Wo gab es Grenzen?
•	Video-Autoplay: Handys und Browser blockieren Videos mit automatischem Start sehr streng. Es brauchte extra JavaScript-Logik, damit der Trailer überall stumm und flüssig anläuft. Da musste ich länger daran herumstudieren, dass es klappte. 
•	Layout bei Tablets: Die schrägen Hintergründe und die Charakter-Bilder haben sich auf mittleren Bildschirmen anfangs mit dem Text überschnitten. Das musste mit genauen Media Queries repariert werden. Beim nächsten Mal achte ich von Anfang an darauf. 
•	Eine persönliche, technische Grenze war auch, dass bei mir zuhause das Netzwerk von Sunrise zu Swisscom wechselte und die Anschlüsse/ Internet nicht funktionierten. Daher musste ich bis heute Nachmittag immer mit dem Hotspot arbeiten.  

Was habe ich unerwartet gelernt?
•	Der IntersectionObserver: Diese JavaScript-Funktion ist genial. Sie startet Animationen und Videos erst genau dann, wenn der Nutzer zu der Sektion scrollt. Das spart extrem viel Rechenleistung. Zudem wirkt es sehr professionell. 
•	Nutzer-Erfahrung (scrollRestoration): Ich habe gelernt, wie man den Browser zwingt, bei einem Seiten-Refresh immer ganz oben (0,0) zu starten, anstatt an der alten Scroll-Position hängen zu bleiben. Dies macht das Ganze benutzerfreundlicher. 
