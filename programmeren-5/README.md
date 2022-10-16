Beveiliging
• Inloggen: bepaalde functionaliteit is afgeschermd voor alleen ingelogde gebruikers, maakt 
niet uit welke gebruiker, als je maar bent ingelogd als rol ‘gebruiker’
• Validatie: bij invoervelden wordt gebruik gemaakt van verplichte velden, en/of velden met 
controle op inhoud (denk aan een postcode of emailadres), gebruiker krijgt foutmeldingen 
te zien (deze zijn NIET te omzeilen door bijv. javascript uit te zetten…)
• Verschillende rollen (dus meerdere soorten gebruikers), bijvoorbeeld
• Admin rol
• Gebruiker rol
• Verschillende rechten
• Admin gedeelte alleen toegankelijk voor ingelogde admin
• Gebruiker heeft eigen afgeschermde deel waarin hij zijn gegevens kan aanpassen. 
• Bij het aanmaken van een nieuw item (bijv. een schaakpuzzel) mag alleen de uploader het 
item wijzigen. Een andere gebruik kan hier niet bij (door er bijvoorbeeld naar te dieplinken).
• Zoeken & Filteren
• Vrije tekst: zoekveld met vrije tekst, zoekt in meerdere kolommen (bijvoorbeeld in naam 
en ‘bericht’), hoeft niet in het hele systeem te zoeken, mag ook voor een specifieke lijst met 
data (bijv. nieuwsberichten).
• filtermogelijkheid: dmv dropdownlist. Bijvoorbeeld alle nieuwsberichten van categorie 1 
of 2 zien
• combinatie van zoeken EN filteren, of filteren op meerdere categorieën levert een extra 
punt op
• Beveiliging
o OWASP top 10
 Schakelen van status met button in lijst
bijvoorbeeld aan/uit, actief/niet actief
o MOET via een post
o MOET naar aparte action in 
een controller
o mag ook via Ajax
Diepere validatie: 
Voer voor een actie naar keuze 
een extra validatie toe, waarbij de gebruiker deze actie pas mag uitvoeren nadat hij iets 
anders een x aantal keer heeft gedaan. (licht dit toe in je assessment)
a. Bijvoorbeeld bij een forum:
een gebruiker mag pas een topic openen als hij minimaal 5 reacties heeft gegeven.
b. Bijvoorbeeld bij review systeem:
een gebruiker mag een review plaatsen als hij minimaal op 5 verschillende dagen is 
ingelogd.
3. Voorbeeldvragen
• specifieke oplossingen vanuit jouw framework (ken je ze, waarom evt niet gekozen?)
• bijvoorbeeld: hoe gaat je framework om met beveiliging?
• bijvoorbeeld: hoe gaat je framework om met databases?
• bijvoorbeeld: aan welke eisen moet een ‘live’ server voldoen?
• bijvoorbeeld: toelichten waarom je iets niet volgens de richtlijn hebt gedaan.
• algemene MVC vragen (ken je ze, en hoe zit dat in jouw framework)
• bijvoorbeeld: wat zijn layouts/partials, en hoe zit dat in jouw framework?
• bijvoorbeeld: wat is de taak van een controller?
• bijvoorbeeld: wat is een sql injection, en hoe beveilig je hiertegen?
• specifieke vragen m.b.t. hoe je iets hebt gebouwd (technisch in je code)
• bijvoorbeeld: hoe heb je verschillende rollen geïmplementeerd