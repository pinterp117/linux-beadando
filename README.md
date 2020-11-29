# linux-beadando

Dalszöveg kereső beadandó feladat Linux ismeretek tantárgyra!

A program Bash scriptben íródott, ezenkívül a JSON kezelésére Pythont használtam. Több féle módon próbálkoztam a megoldással, természetesen figyelembe véve azt is, hogy tartalmilag megfeleljen a tárgy keretében tanult ismeretekhez, valamint terjedelmileg is helyt álljon egy beadandó feladat kapcsán.

Többször teszteltem a program funkcióit, remélem sikerült minden lehetséges hibát kezelnem, egyedül a használt API korlátaiba ütköztem.
Tesztelés közben észrevettem, hogy ha többször kérjük le egy szerző ugyan azon dalát gyorsan, akkor a felhasznált API nem fog válaszolni a kérésre, egy kis időnek el kell telnie a dal mégegyszeri lekérdezésére.

    Használat:
      -s  A dal szerzője
      -d  A dal címe
      -h  Használati útmutató
    Példa:
      ./szovegkereso -s Post Malone -d Better Now
