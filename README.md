<h1>Hej!</h1>
<h2>Ett urval av de projekt jag skapat under årets gång under tiden jag lärt mig att programmera i främst Python.</h2>

[FotbollStatistik](https://github.com/TomasLehtela/FotbollStatistik)<br>
Använder Selenium för att hämta statistik för en fotbollsspelare. Räcker med en input på T. Ex. efternamnet på en spelare; "Pogba" hämtar statistiken för "Paul Pogba". Använder sedan mplsoccer för att visuellt framställa statistiken i ett pajdiagram uppdelat i tre olika statistikområden: offensivt/defensivt/bollinnehav. Har även lagt till så att en ansiktsbild läggs till i mitten, samt en flagga till vänster om namnet.

Exempel på output:<br>
<img src="https://github.com/TomasLehtela/FotbollStatistik/blob/main/exampleoutput.png" width="200" height="200">

[LedigaPasstider](https://github.com/TomasLehtela/LedigaPasstider)<br>
Många av mina vänner och kollegor behövde boka pass inför sommaren men polisen valde att släppa tider "lite då och då". Denna använder också Selenium för att ta en skärmdump av lediga tider (ifall det finns lediga tider under den månad som parametern är inställd på). Denna skärmdump mailas sedan bifogat till en lista med mina vänners mailadresser. Laddade ursprungligen upp denna på min ordinarie github och fick en stor mängd trafik direkt, runt 600 visningar första dagarna. Fungerar tyvärr inte längre då Polisen lagt till MCaptcha som jag försökt, men inte lyckats ta mig förbi (använde då Tesseract-OCR vilken inte är tränad på captchas).

[DiscordBot](https://github.com/TomasLehtela/Discordbot)<br>
Ett av de första projekten jag påbörjade och som fick mig att bli intresserad av programmering. En bot jag och mina vänner har på ett par kanaler, ingen moderatorfunktionalitet på denna bot utan används för att ta fram gifs av olika slag, hämtar senaste metan av loadout till Call of Duty: Warzone, samt att jag även implementerat FotbollStatistik i denna (skriv !player pogba i chatten och botten svarar med bilden som tas fram). Tanken är också att försöka få till någon slags röststyrning.

[DjangoBlogg](https://github.com/TomasLehtela/DjangoBlogg)<br>
Påbörjade bygget av en hemsida för att kunna visa mina projekt jag gjort i ett bloggformat. Fått lära mig mycket HTML och CSS här, i slutändan beslutade jag mig för att använda mig av Bootstrap 5 för simpliciteten. Detta projekt är fortfarande under konstruktion men grundfunktionaliteten finns där.

[PasswordManager](https://github.com/TomasLehtela/PasswordManager)<br>
En enkel lösenordshanterare byggd med tkinter. Kan generera random lösenord, uppgifterna sparas i json-format.

[Pygame2DSpel](https://github.com/TomasLehtela/Pygame2DSpel)<br>
Första projektet med Pygame. Simpel 2D med grafik som jag hämtat från nätet. Spelet går ut på att hoppa över olika hinder.

[DjangoAktier](https://github.com/TomasLehtela/DjangoAktier)<br>
Första projektet med Django. Går att lägga till och ta bort aktier med hjälp av aktiens "ticker". Visar sedan data så som pris/pris vid stängning etc etc.

[PomodoroTimer](https://github.com/TomasLehtela/PomodoroTimer)<br>
En Pomodorotimer byggd med Tkinter. Lagt till lite ljud vid start/stopp och försökt få till lite snyggare UX med beskuren bild etc.

[TkinterSpelGissaStaten](https://github.com/TomasLehtela/TkinterSpelGissaStaten)<br>
Ett spel byggt i Tkinter. Klicka på en amerikansk stat på en karta och gissa vilken stat det är. Vid spelets slut sparas alla de stater man inte lyckades gissa, i csv-format.
