Pytania do Elektrotechniki
===
1.Podział elementów elektrotechnicznych
---

Czym charakteryzują się elementy bierne?
- Nie wytwarzają one energii ani nie zmieniają swoich parametrów.

Jakie zadania spełniają elementy bierne?
- Magazynują energię (cewka, kondensator), bądź ją „traci” (rezystor)

Czym charakteryzuje się element czynny?
- Wytwarza energię elektryczną, bądź jest w stanie zmienić swoje parametry zależnie od przyłożonego prądu/napięcia. np. tranzystory, układy i baterie.

2.Rezystor i prawa z nimi związane
---

Za co odpowiada rezystor?
- Ogranicza prąd płynący w obwodzie.

Czym się charakteryzuje?
- Posiada dwa wyprowadzenia (dwie nogi), między którymi występuje opór w omach [Ω]

Jakie główne rodzaje rezystorów wyróżniamy?
- SMD (powierzchniowe), THT, potencjometr  (pozwala na zmianę rezystancji za pomocą pokrętła), termistor, warystor

Jak działa termistor?
- Wyróżniamy trzy typy
* NTC – Im zimniej tym większa rezystancja
* PTC – Im cieplej tym większa rezystancja
* CTR – Rezystancja osiąga swój maks o konkretnej ustalonej temperaturze

Jak działa Warystor?
- Rezystancja jest nieliniowa, zależna od napięcia elektrycznego

Czym jest rezystor pull-up  i pull-down
- Pull-up – rezystor podłączany jest do wejścia układu w celu ustalenia wartości spoczynkowej
- Pull-down – rezystor podłączony do masy w celu pozbycia się zakłóceń

Co głosi prawo Ohma?
- Że Napięcie jest prostopadłe do Natężenia

Co głosi pierwsze i drugie prawo Kirchhoffa
- Pierwsze głosi iż z węzła wypływa tyle samo prądu co do niego wpływa, a węzłem nazywamy miejsca w których łączą się przewody, ścieżki lub wyprowadzenia
- Drugie głosi iż jeśli wybierzemy dowolną drogę zamkniętą w obwodzie, to suma napięć pochodzących od źródeł zasilania jest równa sumie napięć pozostałych elementów.

Na co pozwala połączenie obu praw Kirchhoffa?
- Na ustalenie wartości i kierunków prądu w obwodzie elektrycznym

Jakie metody rozwiązywania obwodów wyróżniamy?
    - Prądów oczkowych
    - praw Kirchhoffa
    - potencjałowa
    - superpozycji
    - Thevenina

3.Kondensatory
---
Jakie rodzaje kondensatorów wyróżniamy?
- Biegunowe i bezbiegunowe (spolaryzowane i niespolaryzowane)

Czym się różnią od siebie?
- Biegunowy należy podłączyć do układu dobrą stroną gdyż ten ładuje się jedynie od lewej do prawej
- Bezbiegunowy nie ma takiej potrzeby

Do czego służą i jak działają?
- Podobnie do akumulatorów magazynują energię i ją oddają gdy chwilowo zabraknie zasilania

Z jakich materiałów są tworzone?
- biegunowe najpopularniejsze są kondensatory elektrolityczne
- bezbiegunowe są produkowane np. z ceramiki lub folii
    * Wybór materiału ustala też parametry kondensatora. Foliiowe charakteryzują się dużą wytrzymałością napięć.

Czym wyrażamy pojemność kondensatora?
- Jednostką pojemności sa Farady (symbol F), jednak jest to ogromna jednostka i częściej spotyka się:
    * pikofaradami [pF] (1 pF = 0,000 000 000 001 F),
    * nanofaradami [nF] (1 nF = 0,000 000 001 F),
    * mikrofaradami [μF] (1 μF = 0,000 001 F).

Jak możemy łączyć kondensatory?
- Szeregowo i Równolegle
    * Równolegle to po prostu suma ich pojemności
    * Szeregowo sprawia że pojemność jest mniejsza niż pojemność najmniejszego z kondensatorów

Jakie zastosowanie mają kondensatory?
- Korzystamy z nich w celu filtracji zasilania, pozbycia się zakłóceń spowodowanych przerwami w zasialniu bądź nagłymi skokami natężenia.

Jakich kondensatorów powinno się do tego używać?
- Zaleca się korzystać z ceramicznego 100 nF
    * Kondensatory elektrolityczne nie najlepiej sobie radzą z filtrowaniem sygnałów o bardzo dużych częstotliwościach.
    * Natomiast ceramiczne mają problem z zakłóceniami o niewielkich częstotliwościach 
        * Dlatego najlepszym rozwiązaniem jest połączenie równoległe obu kondensatorów

4.Cewka/Dławik
---
Jak wygląda cewka?
- Jest to spirala stworzona z drutu, która może być nawinięta na magnetyczny materiał bądź na powietrze jeśli drut jest dość sztywny. Jest też możliwe owinieńcię na papierze ale jest to nazywane też owinięciem powietrznym gdyż papier jest obojętny magnetycznie.

Jak zachowuje się cewka?
- Jeśli przepuscimy przez cewkę prąd i naglę go odłączymy to wygeneroway zostanie skok napięcia gdyż cewka chce podtrzymać przepływ prądu.

Czym charakteryzuje się cewka?
- Przy przeływie prądu Cewka wywtarza pole magnetyczne, a moc cewki określamy `indukcyjnością` wyrażaną w henrach `[H]`, nanohenrach `[nH]`, mikrohenrach `[μH]` i milihenrach `[mH]`.

W jaki sposób włączamy Cewke do układu?
- Wpinamy je szeregowo z zasilanym urządzeniem. 

Czemu?
- Gdyż Ceka/Dławik stanowi bardzo mały opór dla prądu stałego, natomiast dla zmiennego znacznie większy

Od czego jest zależna indukcyjność Cewki?
- Od ilości zwojów (obrotów) drutu. 
    * Co ważne dla większej indukcyjności korzysta się z cieńszych drutów bo rozmiar `karkasu` (tego na czym owija się drut) jest ograniczony. Jednak im cieńszy drut tym mniejszy jest maksymalny prąd.
    * Wniosek: Maksymalny prąd jest przeciw proporcjonalny do indukcyjności i na odwrót

5.Diody
---
Jakiego typu diody wyróżniamy?
- Krzemowe
- Świecące

Jaka jest wspólna cecha diod?
- Pozwalają aby prąd przepływał tylko w jednym kierunku

Jakie 4 wartości posiadia dioda?
- Maksymalne napięcie wsteczne - czyli maksymalne napięcię jakie może znieść dioda bez ryzyka jej uszkodzenia
- Maksymalny prąd przewodzenia - maksymalna wartość prądu, jej przekroczenie grozi zniszczeniem
- Maksymalna moc strat - dioda ulega nagrzaniu przy przewodzeniu prądu, zbytnie nagrzanie może spowodować spalenie diody
- Napięcie przewodzenia - napięcie występujące miedzy końcami diody, a jego wartośc jest zależna od natężenia prądu przepływającego przez diodę

Jak można podłączyć wiele diod?
- Przy połączeniu równolege ale powinny składać się one z par rezystor-dioda
- Drugą opcją jest szeregowo ale należy wtedy zwięszyć napięcie niż założone

6.Tranzysotry bipolarne
---
Czym jest tranzysotr?
- Elementem półprzewodnikowym mającym zazywyczaj trzy wyprowadzenia

Jakie elementy tranzysotra wyróżniamy?
- Wyrózniamy trzy elementy
    * Emiter (E)
    * Baza (B)
    * Kolektor (C lub K)

Co robi tranzystor?
- Efektem jego działania jest wzmnocnienie prądowe

7.Stabilizatory
---
Na co pozwalają?
- Na uzyskanie stabilnego napięcia stałego, którego wartość jest niezależna.