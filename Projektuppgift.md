﻿## Projektuppgift: DummyChat
Du ska använda DummyApi-webbtjänsten för att bygga en chat-klient.
Denna applikation ska byggas med hjälp av AngularJS, Bootstrap och jQuery UI.

Meddelanden kommer finnas tillgängliga här: http://dummyapi.kodalagom.se/api/messages<br>
Kanaler kommer finnas här: http://dummyapi.kodalagom.se/api/channels

DummyApi docs: https://github.com/JohnFChas/DummyApi/wiki

## Uppgifter
Följande är minimum för godkänt betyg.

- Använd AngularJS med routing
- Använd bootstraps grid för layout och responsivitet
- Skapa en service som hanterar alla HTTP-requests
- Navigation
	- Använd till exempel bootstrap navbar eller tabs
- "Channel"-view
	- Visa alla meddelanden som tillhör kanalen
	- Skriva nya meddelanden
	- Se till att listan med meddelanden håller sig uppdaterad (till exempel genom polling)
	- Formatera datumen på alla posts med ett filter eller directive
- "Admin"-view
	- Skapa nya kanaler
	- Ta bort kanaler
	- Lägg till favorit-kanaler

## Extrauppgifter
Följande uppgifter ger poäng mot betyget väl godkänt, för väl godkänt betyg krävs minst 10 VG-poäng.

Utöver dessa uppgifter kommer jag dessutom att titta på kodstruktur och design av gränssnitt för högre betyg.
När det gäller design är det först och främst struktur och användarvänlighet jag är ute efter.

- Skriv väl strukturerad och genomtänkt kod (0-4 VG-poäng)
- Användarvänligt och strukturerat gränssnitt (0-4 poäng)
- "Channel"-view
	- Skapa components eller directives för: (1-5 VG-poäng)
		1. Meddelanden
		2. Input-fält (där man skriver sitt meddelande)
		3. Alternativt andra valfria saker
	- Implementera en bättre lösning än polling för att uppdatera chatten, servern stödjer SignalR (5 VG-poäng)
		1. Servern kallar funktionen recieveMessage varje gång ett nytt meddelande postas,
		   undersök hur du kan konfigurera din klient för att ta emot meddelandet
		2. Serverns SignalR hub heter chatHub.
- "Admin"-view
	- Använd jQueryUI draggable och droppable för att: (1-2 VG-poäng)
		1. Flytta kanaler till favoriter
		2. Ta bort kanaler
- Använd någon cool jQueryUI effekt när: (1-2 VG-poäng)
	1. Nya meddelanden läggs till i chatten
	2. När man tar bort kanaler med draggable/droppable
- Skapa valfria directives, components, filters och/eller services (0-5 VG-poäng)
- Skapa valfri widget med widget factory eller AngularJS component/directive (och använd den på något meningsfullt sätt) (0-5 VG-poäng)
- Labbar/inlämningar (0-2 VG-poäng)

## Inlämning
Det är individuell inlämning för detta projekt.
Deadline för inlämning: 4 november 2016, kl 23:59

- Skapa ett GIT repository, till exempel på github.com.
- Pusha upp ert projekt till ert repository.
- Maila länken till repositoryt till mig på john.fristedt@chas.se.

Vet ni inte hur man gör detta så säg till mig så ska jag förklara.
