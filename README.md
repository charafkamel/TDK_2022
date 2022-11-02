# Anomália detektálás logfájlokban gépi tanulással

##### Szerző: Charaf Kamel
##### Konzulens: Dr. Horváth Gábor (HIT)

## Github tartalma

A main brachen megtalálható az általam implementált 2 algoritmus:

-> DeepLog alapú algoritumus: DeepLog_final.ipynb

-> KNN alapú algoritmus: KNN_final.ipynb 

Ezek mellett található számos txt fájl, ami a két algoritmusnak biztosítja, hogy azonos adatállományból dolgozzanak, így összehasonlíthatóak legyen.

Található még egy Értékelések mappa, amiben az egyes küszöbértékekre kapott eredmény található

## Github kezelési útmutató

Az egyes algoritmusok hivatkoznak a HDFS logfájlra, ami nagyobb méretű mint a Githubra feltölthető 100 MB-os állomány!
Ezt az alábbi linken lehet letölteni: https://zenodo.org/record/3227177#.Y15TzhaZOUk

#### 1. lépés: Feljebb található linkről a HDFS logfájl letöltése
#### 2. lépés: Leclone-ozni a projektet és a letöltött állományt azonos mappába helyezni a klónozott projekttel
#### 3. lépés  Lefuttatni az algoritmusokat és élvezni annak működését
