# A leírás címe
##Az első alcím helytelenül
## Az első alcím helyesen

Miért nem volt helyes a "\#\#Az első alcím helytelenül" írása?
Mert nem tettünk szóköz a két \# után.

A \# - nek fontos szerepe van a Markdown nyelvben.
1 darab belőle az egyes szintű címsort vezeti be. Kettő a 2-es szintű címsort.
Ahhoz, hogy az ilyen speciális karaktereket láthatóan be tudjuk írni, tehát nem a speciális jelentésében használjuk, a szerkesztéskor elé kell írnunk egy \\ jelet. 
Látjuk, hogy a \\ jel is speciális, tehát, hogy ezt láthassuk, 2-t kell belőle egymás mellé írni szerkesztéskor.

Figyeljük meg, hogy a szerkesztéskor **kihagyott üres sor** új bekezdést fog jelenteni, a következő sor írásával.

Az előbbi bekezdésbeli vastag betűs írásmódot úgy értük el, hogy két csillag karakter után írtuk *szóköz kihagyása nélkül* a vastagítandó szöveget, majd 2 csillag zárta. . 
A dőlt írásmódot 1 csillaggal kezdve 1-gyel befejezte hasonlóan írtuk.

Érdemes megnézni, hogy mi történik, ha szóközt írunk a két csillag után, utána egy szövegrész, majd megint 2 csillagot.
(és ugyanezt 2 helyett 1 csillaggal)

Mit néztünk meg eddig? 
-címsorok
- bekezdések
- vastag betűs írásmód
- dőlt betűs írásmód
- speciális karakterek beírása eredeti értelemven

Nézzük meg a Markdown kódot. 
Vajon miért nem szerepel a felsorolásban a "címsorok" ugyanolyan módon mint a többi? 
Mert nem tettünk szóköz a - jel után. 
Amúgy azt is láthatjuk tehát, hogy a számozatlan felsorolást a - jel vezeti be, de utána szóköz jön. 

