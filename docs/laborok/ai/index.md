# Labor 5 - AI

## Bevezetés

A labor során az Androidon elérhető MI szolgáltatásokkal ismerkedhetünk meg.

## Előkészület

A feladatok megoldása során ne felejtsd el követni a feladatbeadás folyamatát [Github](../../tudnivalok/github/GitHub.md).

### Git repository létrehozása és letöltése

1. Moodle-ben keresd meg a laborhoz tartozó meghívó URL-jét és annak segítségével hozd létre a saját repository-dat.
2. Várd meg, míg elkészül a repository, majd checkout-old ki.
3. Hozz létre egy új ágat `megoldas` néven, és ezen az ágon dolgozz.
4. A neptun.txt fájlba írd bele a Neptun kódodat. A fájlban semmi más ne szerepeljen, csak egyetlen sorban a Neptun kód 6 karaktere.

## 1. feladat: Sudoku alkalmazás elkészítése Gemini segítségével


### Projekt létrehozása

Indítsuk el az Android Studio-t, majd:

1. Hozzunk létre egy új projektet, válasszuk az *Empty Activity* lehetőséget.
1. A projekt neve legyen `GeminiGame`, a kezdő package pedig `hu.bme.aut.android.geminigame`.
1. Nyelvnek válasszuk a *Kotlin*-t.
1. A minimum API szint legyen API24: Android 7.0.
1. A *Build configuration language* Kotlin DSL legyen.

!!!danger "FILE PATH"
	A projekt mindenképpen a repository-ban lévő GeminiGame könyvtárba kerüljön, és beadásnál legyen is felpusholva! A kód nélkül nem tudunk maximális pontot adni a laborra!

Ellenőrizd, hogy elérhető-e a Gemini a projektből! *(View > Tool Windows > Gemini)*  
Szükség esetén jelentkezz be a Google Accountoddal, valamint engedélyezd a projektben a kontextus használatát.

Az előbb létrehozott projektben valósíts meg egy aknakereső játékot a Gemini segítségével!

!!! example "1a. feladat beadandó (1 pont)"
    * Készíts egy képernyőképet a futó alkalmazásról *játék közben* (emulátoron vagy saját készüléken), és mentsd el a repository gyökerébe **`f1a.png`** néven.

!!! example "1b. feladat beadandó (1 pont)"
    * Készíts egy képernyőképet a használt promptok listájáról, és mentsd el a repository gyökerébe **`f1b.png`** néven.

## 2. feladat: Generatív modellt használó alkalmazás

### Projekt létrehozása

Mentsük el a korábbi projektet, majd

1. Hozzunk létre egy új projektet, válasszuk a *Gemini API Starter* lehetőséget.
1. A projekt neve legyen `GeminiApiDemo`, a kezdő package pedig `hu.bme.aut.android.geminiapidemo`.
1. Nyelvnek válasszuk a *Kotlin*-t.
1. A minimum API szint legyen API24: Android 7.0.
1. A *Build configuration language* Kotlin DSL legyen.
1. A következő ablakban a linkre kattintva generáljunk magunknak API kulcsot, majd másoljuk be.

!!!danger "FILE PATH"
	A projekt mindenképpen a repository-ban lévő GeminiApiDemo könyvtárba kerüljön, és beadásnál legyen is felpusholva! A kód nélkül nem tudunk maximális pontot adni a laborra!

Vizsgáljuk meg a létrejött projekt kódját, majd próbáljuk meg futtatni a létrejött projektet!

A projekt nagy valószínűséggel nem fog elindulni, mert több helyen elavult hivatkozásokat tartalmaz.  

A fejlesztőkörnyezet által kiírt Error üzenetek alapján próbáld meg kijavítani a projekt működését!  
Futás idejű hibák esetén használd a *Logcat* nézetet!

!!! tip "Model overload"
    Ha az alkalmazás használata során az API-tól a "Model overloaded" hibaüzenet kapod vissza, próbálkozz egy későbbi időpontban. Ha ez sem segít, készítsd el így a képernyőképeket.

!!! example "2. feladat beadandó (1 pont)"
    * Készíts egy képernyőképet a futó alkalmazásról *a második kép alapján generált szöveggel* (emulátoron vagy saját készüléken), és mentsd el a repository gyökerébe **`f2.png`** néven.


## 3. feladat: CameraX és MLKit technológiák

Készíts egy új alkalmazást, amely egy vizuális MLKit szolgáltatást használ bármilyen MI alapú funkció megvalósítására, CameraX Preview segítségével!  
A megvalósítás során használhatod segítségként a Geminit, vagy más nagy nyelvi modellt, illetve természetesen a hivatalos dokumentációt.

!!!danger "FILE PATH"
	A projekt mindenképpen a repository-ban lévő MlkitProject könyvtárba kerüljön, és beadásnál legyen is felpusholva! A kód nélkül nem tudunk maximális pontot adni a laborra!

!!! example "3a. feladat beadandó (2 pont)"
    * Készíts egy képernyőképet az elkészült alkalmazás felületéről, ahol látszik, hogy mi a megvalósított funkció és mentsd el **`f3.png`** néven a repository gyökerébe.