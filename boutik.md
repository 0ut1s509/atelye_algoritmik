

#  Atelye 1 — Sistèm Fakti yon Boutik

## Objektif

Yon boutik bezwen prepare yon fakti pou kliyan li yo.

Ekri yon algoritm an **pseudocode LARP** ki pèmèt resevwa enfòmasyon sou yon kliyan ak pwodui li achte yo, epi afiche kantite total kliyan an dwe peye.


## Deskripsyon pwoblèm nan

Yon kliyan achte **3 pwodui** diferan.

Pou chak pwodui, boutik la bezwen konnen:

* non pwodui a;
* pri yon (1) inite pwodui a;
* kantite kliyan an achte.

Apre sa, algoritm lan dwe prepare fakti kliyan an.



## Rezilta yo dwe afiche

Nan fen egzekisyon an, algoritm lan dwe montre:

* non kliyan an;
* enfòmasyon sou chak pwodui;
* kantite lajan ki koresponn ak chak pwodui;
* kantite total kliyan an dwe peye.


## Egzanp rezilta

```text
========================
        FAKTI
========================

Kliyan : Marie

Diri
pri: 250
kantite: 2
total: 500

Lwil
pri: 600
kantite: 1
total: 600

Ji
pri: 75
kantite: 4
total: 300



------------------------
Total : 1400 goud
========================
```

## Konsiy

* Ekri algoritm lan dwe an **pseudocode LARP**.
* Chwazi varyab ki gen non ki klè epi siyifikatif.
* Algoritm lan dwe fonksyone pou nenpòt seri done itilizatè a antre.


#   2 — Amelyore Sistèm Fakti Boutik la

## Objektif

Nan premye atelye a, ou te kreye yon algoritm ki prepare fakti yon kliyan.

Koulye a, boutik la deside ajoute yon nouvo fonksyonalite: **yon rabè pou gwo acha**.

Modifye algoritm ou te ekri nan **Atelye 1** an pou li kapab aplike nouvo règ sa a.


## Nouvo règ boutik la

Apre algoritm lan fin kalkile **total fakti a**, li dwe verifye kondisyon sa:

* Si total fakti a **pi gran oswa egal ak 5 000 goud**, kliyan an resevwa yon **rabè 10 %**.
* Sinon, kliyan an pa resevwa okenn rabè.

Apre verifikasyon an, algoritm lan dwe afiche kantite final kliyan an dwe peye.




## Rezilta yo dwe afiche (Outputs)

Anplis enfòmasyon ki te deja sou fakti a, algoritm lan dwe montre:

* total fakti a;
* kantite rabè a (si genyen);
* kantite final kliyan an dwe peye.


## Egzanp 1

```text
========================
        FAKTI
========================

Kliyan : Marie

Total fakti : 6 200 goud

Rabè : 620 goud

Total pou peye : 5 580 goud
```


## Egzanp 2

```text
========================
        FAKTI
========================

Kliyan : Jean

Total fakti : 3 900 goud

Pa gen rabè.

Total pou peye : 3 900 goud
```


## Konsiy

* Kòmanse ak algoritm ou te ekri nan **Atelye 1** an.
* Ajoute sèlman sa ki nesesè pou aplike nouvo règ boutik la.



#  Atelye 3 — Sistèm Fakti ak Lis pwodui

## Objektif

Nan **Atelye 2**, algoritm ou a te prepare yon fakti pou yon kliyan ki te achte **3 pwodui**.

Koulye a, boutik la vle amelyore sistèm nan pou kliyan an ka achte **nenpòt kantite pwodui**.

Modifye algoritm ou a pou li kapab trete tout pwodui kliyan an achte, kèlkeswa kantite yo.


## Nouvo règ boutik la

Anvan antre enfòmasyon sou pwodui yo, algoritm lan dwe mande itilizatè a:

* **Konbyen pwodui kliyan achte?**

Apre sa, algoritm lan dwe repete menm operasyon yo pou chak pwodui.

Règ rabè ki te itilize nan **Atelye 2** rete menm jan an:

* Si total fakti a **pi gran oswa egal ak 5 000 goud**, kliyan an resevwa yon rabè **10 %**.
* Sinon, pa gen rabè.



## Rezilta yo dwe afiche (Outputs)

Nan fen egzekisyon an, algoritm lan dwe montre:

* non kliyan an;
* lis tout pwodui yo trete;
* total fakti a;
* kantite rabè a (si genyen);
* kantite final kliyan an dwe peye.

## Egzanp

```text
Konbyen pwodui kliyan an achte? 4

pwodui 1 : Diri
pwodui 2 : Lwil
pwodui 3 : Ji
pwodui 4 : Sik

...

Total fakti : 5 800 goud

Rabè : 580 goud

Total pou peye : 5 220 goud
```


## Konsiy

* Kòmanse ak algoritm ou te ekri nan **Atelye 2**.
* Kontinye aplike règ rabè boutik la.



#  Atelye 4 — Konsève epi Afiche Fakti a

## Objektif

Nan **Atelye 3**, algoritm ou a te kapab trete nenpòt kantite pwodui epi kalkile kantite total kliyan an dwe peye.

Koulye a, boutik la vle amelyore sistèm nan pou li kapab **enprime yon fakti detaye** ki montre tout pwodui kliyan an te achte.

Modifye algoritm ou te ekri nan **Atelye 3** pou li kapab re-afiche enfòmasyon sou tout pwodui yo apre kalkil la fini.


## Nouvo bezwen boutik la

Apre kliyan an fin antre tout pwodui yo, sistèm nan dwe kapab montre ankò:

* non chak pwodui;
* pri yon inite;
* kantite kliyan an achte;
* total pou chak pwodui;
* total jeneral fakti a;
* rabè a (si genyen);
* kantite final kliyan an dwe peye.




## Rezilta yo dwe afiche (Outputs)

Nan fen egzekisyon an, algoritm lan dwe montre yon fakti ki gen:

* non kliyan an;
* lis tout pwodui yo;
* pri chak pwodui;
* kantite chak pwodui;
* total chak pwodui;
* total fakti a;
* rabè a (si genyen);
* kantite final kliyan an dwe peye.


## Egzanp

### Antre

```text
Non kliyan : Marie

Konbyen pwodui kliyan an achte? 4

pwodui 1
Non : Diri
Pri : 250
Kantite : 2

pwodui 2
Non : Lwil
Pri : 600
Kantite : 1

pwodui 3
Non : Ji
Pri : 75
Kantite : 4

pwodui 4
Non : Sik
Pri : 150
Kantite : 3
```

### Sòti

```text
==============================
          FAKTI
==============================

Kliyan : Marie

Diri
Pri: 250
Kantite: 2

Lwil
Pri: 600
Kantite: 1

Ji
Pri: 75
Kantite: 4

Sik
Pri: 150
Kantite: 3

------------------------------
Total fakti : 1 850 goud

Rabè : 0 goud

Total pou peye : 1 850 goud
==============================
```


## Konsiy

* Kòmanse ak algoritm ou te ekri nan **Atelye 3**.
* Modifye algoritm lan pou li kapab **konsève enfòmasyon sou tout pwodui yo** pandan y ap antre yo.
* Nan fen egzekisyon an, afiche yon fakti ki montre tout pwodui kliyan an te achte.
* Pa mande kliyan an antre menm enfòmasyon yo de fwa.



#  Atelye 5 — Chèche yon pwodui sou Fakti a

## Objektif

Nan **Atelye 4**, sistèm nan te kapab konsève enfòmasyon sou tout pwodui kliyan an achte.

Koulye a, boutik la vle pèmèt kesye a chèche yon pwodui sou fakti a pou li ka jwenn enfòmasyon sou li.

Modifye algoritm ou te ekri nan **Atelye 4** pou ajoute nouvo fonksyonalite sa.


## Nouvo bezwen boutik la

Apre fakti a fin prepare, sistèm nan dwe mande itilizatè si a si li vle chache yon pwodui si wi antre **non pwodui a**.

Algoritm lan dwe verifye si pwodui sa egziste sou fakti kliyan an.

* Si pwodui a egziste, algoritm lan dwe montre enfòmasyon ki asosye ak li.
* Sinon, li dwe fè itilizatè a konnen pwodui a pa sou fakti a.



## Rezilta yo dwe afiche (Outputs)

Si pwodui a ladann, algoritm lan dwe montre omwen:

* non pwodui a;
* pri yon inite;
* kantite kliyan an achte;
* total pwodui a.

Sinon, algoritm lan dwe afiche yon mesaj ki endike pwodui a pa egziste sou fakti a.


## Egzanp 1

### Antre

```text
pwodui pou chèche : Ji
```

### Sòti

```text
pwodui.

Non       : Ji
Pri       : 75 goud
Kantite   : 4
Total     : 300 goud
```


## Egzanp 2

### Antre

```text
pwodui pou chèche : Pen
```

### Sòti

```text
pwodui "Pen" pa sou fakti kliyan an.
```

## Konsiy

* Kòmanse ak algoritm ou te ekri nan **Atelye 4**.
* Chèche pwodui a nan lis pwodui kliyan an.
* Si pwodui a ladann, afiche tout enfòmasyon ki konsène li.
* Si pwodui a pa ladann, afiche yon mesaj ki apwopriye.

