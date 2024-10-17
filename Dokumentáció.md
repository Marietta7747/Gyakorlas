<center>

# Vizsgaremek  

</center>

<br><br><br><br><br><br>
**Készítette: Falka Marietta & Bogdán László**
<br><br><br><br><br><br><br>


### <p style = "text-align: center ">Kaposvár</p>  


#### <p style = "text-align: center">2024</p>

<br><br><br><br><br><br><br><br>
<br><br><br><br><br><br><br><br>

## <p style=" text-align: center "> Kaposvári Szakképzési Centrum <br> Noszlopy Gáspár Közgazdasági Technikum 
<br><br><br><br><br><br><br>
# <p style="text-align: center">Ticket</p> 
<br><br><br><br><br><br><br>

 *Szoftverfejlesztő és tesztelő képzés*

---

## <p style = "text-align: center ">Tartalomjegyzék</p>

1. [Bevezetés](#bevezetés)
   - 1.1. [Köszönetnyilvánítás](#köszönetnyilvánítás)
   - 1.2. [Témaválasztás](#témaválasztás)
   - 1.3. [Témaválasztás indoklása](#témaválasztás-indoklása)
2. [Felhasználói dokumentáció](#felhasználói-dokumentáció)
   - 2.1. [Rendszerkövetelmények](#rendszerkövetelmények)
   - 2.2. [A program elindítása](#a-program-elindítása)
     - 2.2.1. [Program indítása exe fájlal](#program-indítása-exe-fájlal)
     - 2.2.2. [Program indítása fejlesztőkörnyezetből](#program-indítása-fejlesztőkörnyezetből)
   - 2.3. [Főmenü](#főmenü)
     - 2.3.1. [Start gomb](#start-gomb)
     - 2.3.2. [High Scores gomb](#high-scores-gomb)
     - 2.3.3. [Exit gomb](#exit-gomb)
   - 2.4. [A játék](#a-játék)
     - 2.4.1. [Játéktér](#játéktér)
     - 2.4.2. [Szövegdoboz](#szövegdoboz)
     - 2.4.3. [Irányítás](#irányítás)
     - 2.4.4. [Küldetések és Nem Játszható Karakterek](#küldetések-és-nem-játszható-karakterek)
     - 2.4.5. [Vége képernyő](#vége-képernyő)
   - 2.5. [Dicsőségtábla](#dicsőségtábla)
3. [Fejlesztői dokumentáció](#fejlesztői-dokumentáció)
   - 3.1. [Fejlesztői környezet](#fejlesztői-környezet)
   - 3.2. [Fájlok, osztályok, főprogramok, alprogramok, változók](#fájlok-osztályok-főprogramok-alprogramok-változók)
     - 3.2.1. [run.py](#runpy)
     - 3.2.2. [main_menu.py](#main_menupy)
     - 3.2.3. [name.py](#namepy)
     - 3.2.4. [game.py](#gamepy)
     - 3.2.5. [player_class.py](#player_classpy)
     - 3.2.6. [npc1.py, npc2.py, npc3.py, npc4.py, npc5.py](#npc1py-npc2py-npc3py-npc4py-npc5py)
     - 3.2.7. [hitbox.py](#hitboxpy)
     - 3.2.8. [gg.py](#ggpy)
     - 3.2.9. [high_score.py](#high_scorepy)
   - 3.3. [Fontosabb kódrészletek](#fontosabb-kódrészletek)
     - 3.3.1. [Gombok](#gombok)
     - 3.3.2. [Felhasználónév input](#felhasználónév-input)
     - 3.3.3. [Karakter mozgása, animációja](#karakter-mozgása-animációja)
     - 3.3.4. [Küldetések és NJK-k](#küldetések-és-njk-k)
     - 3.3.5. [Dicsőséglista](#dicsőséglista)
   - 3.4. [Grafikus elemek és képek](#grafikus-elemek-és-képek)
     - 3.4.1. [Főmenü háttérkép](#főmenü-háttérkép)
     - 3.4.2. [Játéktér kialakítása](#játéktér-kialakítása)
     - 3.4.3. [Szövegdoboz](#szövegdoboz)
     - 3.4.4. [Játékos karakter](#játékos-karakter)
     - 3.4.5. [Nem Játékos Karakterek](#nem-játékos-karakterek)
   - 3.5. [Betűtípusok](#betűtípusok)
     - 3.5.1. [Menüben felhasznált betűtípus](#menüben-felhasznált-betűtípus)
     - 3.5.2. [Játékban felhasznált betűtípus](#játékban-felhasznált-betűtípus)
   - 3.9. [Tesztdokumentáció](#tesztdokumentáció)
4. [Fejlesztési lehetőségek](#fejlesztési-lehetőségek)
5. [Irodalomjegyzék](#irodalomjegyzék)

---

## <p style ="text-align: center">Bevezetés</p>

### 1.1. Köszönetnyilvánítás

Szeretném megköszönni Bloch Tamás tanár úrnak, hogy segített a program elkészítésében. Továbbá szeretném megköszönni Teveli Norbert, Teveli Róbert, aki szintén végig támogatott a technikumi képzés ideje alatt.

### 1.2. Témaválasztás

A viszgaremek témája egy online vasúti, belföldi utastervező applikáció megújítása 

### 1.3. Témaválasztás indoklása

A mindennapokban használt utazás nehézségeinek leküzdése....

---

## 2. Felhasználói dokumentáció

<br>
