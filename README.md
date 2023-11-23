Uputstvo za simulaciju 


Nakon što otvorimo sve potrebne periferije potrebno je otvoriti prozor kanala 0. U polje označeno sa 'T1', unesite 'i', a u polje označeno sa 'R1' unesite, na primjer, 'I8000.'Zatim da bi se to potvrdilo stisnite 'ok1' i štiklirajte 'Auto1'. Na taj način će automatski pristizati informacije o inkrementima.
Dalje u prozoru serijskog kanala jedan potrebno je u polje lijevo od opcije 'SEND CODE' upisati poruku u obliku \00OM150\0d gdje nam broj 150 predstavlja obim točka.
Za prikaz ukupnog puta na sedmosegmentnom displeju potrebno je pet cifri, pa prilikom pokretanja iz cmd-a treba dodati argument 5 na seg.exe.
Za led bar koji se takođe pokreće iz cmd-a potrebno je dodati 'bbbR', pri čemu će se otvoriti led bar sa tri ulazna stuba u plavoj boji i jednim izlaznim stubom crvene boje. 
Poslije pripremljenih periferija pokrenuti program. Nakon pokretanja u prozoru serijske komunikacije kanala 1 pritisnuti prethodno spomenutu naredbu 'SEND CODE' sa čime ćemo poslati podatak o obimu. Zatim u prozoru programa kreće ispisivanje podataka o brzini, trenutnom pređenom putu i broju inkremenata.Za to vrijeme će se u prozoru kanala 1 ispisivati trenutni put.

Što se tiče led bara, nekoliko dioda ima svoju funkciju gdje se ponašaju kao taster(lijevim klikom miša se aktiviraju, a desnim klikom ugase).

Prva dioda od dole u prvom stupcu služi za restart puta, odnosno vraćanje na nulu(promjenu mozemo pratiti na sedmosegmentnom displeju).
Druga dioda od dole u prvom stupcu služi za ispisivanje puta na prozoru serijskog kanala 1.

Paljenjem i gašenjem prve diode od dole u drugom stupcu započinjemo mjerenje, pri čemu će nam zasvjetliti četvrta dioda u četvrtom stubcu. Za kraj mjerenja pritisnemo i ugasimo drugu diodu od dole u drugom stubcu što će označiti kraj mjerenja.Nakon ovog možemo pritisnuti treću diodu u trećem stupcu da vidimo izmjereni put na sedmosegmentnom displeju. 

Prva dioda od dole u trećem stupcu služi za prikaz trenutnog puta na sedmosegmentnom displeju.

Druga dioda od dole u trećem stupcu služi za prikaz brzine na sedmosegmentnom displeju.

Treća dioda od dole u trećem stupcu služi za prikaz trenutnog puta na sedmosegmentnom displeju.


