Hej!

En liten samling projekt jag skapat under årets gång under tiden jag lärt mig att programmera i främst Python.

FotbollStatistik:
Använder Selenium för att hämta statistik för en fotbollsspelare. Räcker med input på T. Ex. efternamnet på en spelare; "Pogba" hämtar statistiken för "Paul Pogba". Använder sedan mplsoccer för att visuellt framställa statistiken i ett pajdiagram uppdelat i tre olika statistikområden: offensiv/defensiv/spel med boll. Har även lagt till så att en ansiktsbild läggs till i mitten, samt en flagga till vänster om namnet.

LedigaPasstider:
Många av mina vänner och kollegor behövde boka pass inför sommaren men polisen valde att släppa tider "lite då och då". Denna använder också Selenium för att ta en skärmdump av lediga tider (ifall det finns lediga tider under den månad som parametern är inställd på). Denna skärmdump mailas sedan bifogat till en lista med mina vänners mailadresser. Laddade ursprungligen upp denna på min ordinarie github och fick en stor mängd trafik direkt, runt 600 visningar första dagarna. Fungerar tyvärr inte längre då Polisen lagt till MCaptcha som jag försökt, men inte lyckats ta mig förbi (använde då Tesseract-OCR vilken inte är tränad på captchas).

DiscordBot:
Ett av de första projekten jag påbörjade och som fick mig att bli intresserad av programmering. En bot jag och mina vänner har på ett par kanaler, ingen moderatorfunktionalitet på denna bot utan används för att ta fram gifs av olika slag, hämtar senaste metan av loadout till Call of Duty: Warzone, samt att jag även implementerat FotbollStatistik i denna (skriv !player pogba i chatten och botten svarar med bilden som tas fram).

DjangoBlogg:
Påbörjade bygget av en hemsida för att kunna visa mina projekt jag gjort i ett bloggformat. Ej färdig ännu då jag just nu väljer att lägga fokus på python istället för HTML/CSS/js.

PasswordManager:
En enkel lösenordshanterare byggd med tkinter. Kan generera random lösenord, uppgifterna sparas i json-format.

Pygame2DSpel:
Första projektet med Pygame. Simpel 2D med grafik som jag hämtat från nätet. Spelet går ut på att hoppa över olika hinder.

DjangoAktier:
Första projektet med Django. Går att lägga till och ta bort aktier med hjälp av aktiens "ticker". Visar sedan data så som pris/pris vid stängning etc etc.

PomodoroTimer:
En Pomodorotimer byggd med Tkinter. Lagt till lite ljud vid start/stopp och försökt få till lite snyggare UX med beskuren bild etc.

TkinterSpelGissaStaten:
Ett spel byggt i Tkinter. Klicka på en amerikansk stat på en karta och gissa vilken stat det är. Vid spelets slut sparas alla de stater man inte lyckades gissa, i csv-format.
