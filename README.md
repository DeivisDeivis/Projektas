# Debug Dash

![Gameplay Screenshot](Packages/MainMeniu.png)

## Mūsų projekto komandos nariai
Kauno Technologijos Universiteto Informatikos fakulteto studentai:

- Požerskas Saulius
- Vilnius Martynas
- Arnas Šaltupis
- Paulauskis Deividas


## Projekto aprašymas
Debug Dash yra 2D begalinio bėgimo žanro žaidimas, kuriame žaidėjo tikslas yra išgyventi kuo įmanoma ilgesnį laiką neatsitrenkiant į kliūtį, bent vienas atsitrenkimas į kliūtį reiškia automatinę žaidėjo mirtį. Žaidėjas žadimo metu taip pat renka bonusus, kurie padeda jam ilgiau išgyventi ir auksines monetas kurias galima keisti į prekes žaidimo parduotuvėje. Žaidimo sudėtingumas didėja bėgant laikui.

## Techninis aprašymas

Žaidimas buvo sukurtas pasinaudojus Unity žaidimų kūrimo įrankių. Projekto valdymui ir komandos darbui buvo pasitelktos priemonės: „JIRA“, „Discord“, „Unity Version Control“. Pasiekti pagrdindiniai techniniai tikslai žaidimo kūrimo metu (ne eilės tvarka):

- Sukurti begalinį takelio generavimą
- Suprogramuoti veikėjo UI
- Priskirti žaidimui muziką ir kitus garso efektus
- Priskirti žaidimui vaizdinius efektus, bėgimo, mirties, šuolio, pritūpimo animacijas
- Suprogramuoti Box Collider veikimo įpatumus su kliūtimis ir bonusais
- Sukurti veikėjų, kliūčių, bonusų vaizdus
- Suprogramuoti taškų skaičiavimo ir bonusų veikimo sistemą
- Suprogramuoti kliūčių ir bonusų atsitiktinį atsiradimą žaidimo metu
- Sukurti perėjimus tarp scenų
- Suteikti žaidimui arkadinį stilių
- Sukurti žaidimui parduotuvę
- Suprogramuoti prekių pirkimo sistemą ir jų realizacija
- Sukurti žaidimui pradini menių su įvairiomis funkcijomis
- Sukurti mygtukų dizainus
- Suprogramuoti mygtukų funkcionalumą

## Projekto testavimas

----

## Žaidimo taisyklės

Žaidimas pradedamas iš pradinio meniu lango paspaudžius „Play“. Po to pereinama į sceną kurioje žmogeliukas automatiškai jau bėga:
![Gameplay Screenshot](Packages/Zmogeliukas.png)


Žaidimo scenoje yra matomos įvairios kliūtys, kurios sukelia automatinę mirtį, šių kliūčių galima išvengti tik peršokus per jas, spaudžiant SpaceBar klaviatūroje:
- Pabaisa 1
![Gameplay Screenshot](Packages/Pabaisa4.png)
- Pabaisa 2
![Gameplay Screenshot](Packages/Pabaisa5.png)
- Pabaisa 3
![Gameplay Screenshot](Packages/Pabaisa6.png)

Taip pat yra kitokio tipo kliūtys, kurių žaidėjas gali išvengti tik tūpdamas, spaudžiant Down Arrow ↓ :
- Laidas
- Virus
![Gameplay Screenshot](Packages/virus.png)

Žaidėjas, vengdamas kliūčių taip pat stengiasi surinkti bonusus:
- vanish (Bonusas, kuris duoda žaidėjui atsparumą kliūtims 2 sekundes)
![Gameplay Screenshot](Packages/vanish.png)
- jump (Bonusas, kuris duoda žaidėjui dvigubai aukštesnį šokimo efektą 2 sekundes)
![Gameplay Screenshot](Packages/jump.png)
- ExtraGold (Bonusas, kuris duoda žaidėjui +10 auksinių monetų)
![Gameplay Screenshot](Packages/lightning.png)

## Vartotojo dokumentacija

Žaidimo pradžioje yra matoma pradinė MainMeniu scena su pasirinkimais: Play, Shop, Options, Help, Quit:

![image](https://github.com/user-attachments/assets/242b29b9-ef2c-42bc-b48e-05cd531f9650)

Pasirinkus Play, pereiname į žaidimo sceną kurioje žmogeliukas jau bėga:

![image](https://github.com/user-attachments/assets/1f5c270f-6a57-4752-b005-4d2747ef8aad)

Mirstaa:

![image](https://github.com/user-attachments/assets/c7237121-193a-432b-8eb5-d4b24f55c17f)


Kai žaidėjas pasirenka vanish bonusą, žaidime atsiranda laiko juosta kuri parodo bonuso veikimo trukmę:

![image](https://github.com/user-attachments/assets/ec9c0232-8f63-4f2e-878a-df0787ae6a8c)








