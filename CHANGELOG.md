# Historia zmian

## 0.18.0 — Dyski zamiast temperatur

- Panel DYSKI wykrywa dostępne lokalne woluminy i nośniki USB bez zewnętrznych programów.
- Wybór dysku z listy, procent zajętości, zajęte/wolne GB i pojemność; wybór zachowany po restarcie.
- Odświeżanie danych co 10 sekund i ręczny przycisk wykrywania nośników.
- Oddzielna historia każdego dysku, obsługa odłączenia i niedostępnego odczytu.
- Usunięto odczyty LHM i konfigurację czujników. Pole mocy CPU zastąpione czasem pracy komputera.

## 0.17.1 — Dopasowanie zegara do półki

- Tarcza zachowuje idealnie okrągłe proporcje i mieści się w ramce obok odczytu cyfrowego.
- Obudowa, tło tarczy, metal, wskazówki i napisy dopasowują się do wszystkich pięciu motywów półki.
- Motyw zmienia się od razu, bez zmiany pozycji zegara.

## 0.17.0 — Zegar i przestawianie widgetów

- Nowy zegar w drewnie i mosiądzu: analogowa tarcza, płynny sekundnik, cyfrowa godzina, data i strefa czasowa Windows.
- Monitor i zegar można przeciągać za górny pasek pomiędzy półkami i ustawiać poziomo.
- Wspólne skalowanie instrumentów na tej samej półce i zapamiętywanie indywidualnych pozycji.
- Dodawanie i ukrywanie zegara z menu obok zegara systemowego.

## 0.16.1 — Monitor na półce

- Monitor CPU/RAM jest osadzony bezpośrednio w regale, na własnej półce.
- Skaluje się wraz z aplikacją; dodanie przewija widok do monitora.
- Brak dodatkowego okna. Zachowane odczyty, wykresy i zapamiętywanie widoczności.

## 0.16.0 — Monitor komputera

- Nowy, niezależny widget CPU / RAM / temperatury w drewniano-metalowej obudowie.
- Rzeczywiste obciążenie procesora i pamięci, minutowe wykresy oraz płynne wskaźniki.
- Temperatury CPU, GPU i dysku oraz moc i taktowanie z działającego Libre Hardware Monitor (WMI). Brakujące odczyty pozostają oznaczone jako niedostępne.
- Przesuwanie za górny pasek, zmiana rozmiaru, zapamiętanie położenia, przywracanie przy starcie i opcja zawsze na wierzchu.
- Sterowanie z menu ARCADE obok zegara: Monitor komputera.

## 0.15.2 — 2026-10-25

- Naprawiono obsługę brakujących grafik: lokalny serwer zwraca błąd 404 i nadal działa, a po przywróceniu pliku ponownie go udostępnia.
- Dodano kontrolę wszystkich grafik kolekcji przy sprawdzaniu kodu i budowaniu paczki.
- Zachowano zapisane pozycje i widoczność figurek.

## 0.15.1 — usunięcie kociej serii inspirowanej grami

- Usunięte figurki Zephyr, Sora, Nyx, Brim, Kai, Luna, Mori, Pix, Neko i Vyra z menu, katalogu, animacji i paczki aplikacji.
- Pozostają realistyczny Czort w sześciu pozach oraz sześciu szczurzych antybohaterów.
- Ustawienia i pozycje pozostałych figurek oraz gier są zachowane. Stare zapisane wybory nie przywracają wycofanej serii.
- Instalator usuwa znane stare grafiki i materiały poprzedniej kolekcji.


## 0.15.0 — realistyczna kolekcja Czorta

- Sześć nowych figurek kota autora: Spokojny, Nastroszony, Na plecach, Przyczajony, Ziewający i Z łapką.
- Zachowany wygląd ciemnego futra, puszystego ogona i charakterystycznych oczu; grawer CZORT na każdej podstawie.
- Delikatne mruganie wyłącznie złotym okiem, bez zmiany wyglądu drugiego oka.
- Osobna seria w menu i dwie półki, indywidualna widoczność i przestawianie; zachowane ustawienia dotychczasowych figurek.
- Ostre grafiki i lekkie lokalne nakładki animacji, bez dodawania kolejnych kontekstów WebGL.


## 0.14.1 — wyraźniejsze figurki

- Pełna jakość oryginalnych grafik zamiast zastępowania całej sylwetki pomniejszonym płótnem animacji.
- Animowane oczy i efekty są osobnymi nakładkami; ich rozdzielczość uwzględnia skalowanie Windows i dodatkowe próbkowanie.
- Usunięte ciągłe rozciąganie sylwetek oraz cień wokół samych nakładek oczu.
- Dokładniejsze ustawianie figurek na siatce pikseli. Zachowane mruganie, dym, światła, grawerowane imiona i przestawianie.
- Sprawdzone skalowanie 100% i 150% oraz okna do 4K.


## 0.14.0 — szczurzy antybohaterowie

- Sześć nowych figurek: Operator, Don, Vigilante, Outlaw, Detective i Seeker.
- Mruganie odsłoniętymi oczami, dym i żar cygara/papierosa, pulsujący wizjer i radio, pustynny pył, światło latarni oraz artefakt i ekran detektora.
- Własne efekty przy rekwizytach każdej figurki, grawerowane imiona i niezależne przestawianie.
- Dwie serie w menu obok zegara; można pokazać lub ukryć całą serię. Dodatkowe półki mieszczą nową kolekcję bez przestawiania zapisanych gier.
- Animacje respektują ograniczenie ruchu i pauzują podczas otwierania gier.


## 0.13.1 — imiona grawerowane na podstawach

- Na figurkach pozostają tylko imiona, bez podpisów ról.
- Napisy znajdują się na metalowym froncie oryginalnej podstawy z efektem zagłębionego graweru.
- Imiona poruszają się razem z podstawą; usunięte osobne prostokątne etykiety i ich wariant w motywie Szlak Wilka.


## 0.13.0 — usunięcie petów i poprawka Brima

- Całkowicie usunięte pety z półki, menu, kodu uruchomieniowego i paczki aplikacji.
- Wycofane ustawienia petów są odrzucane podczas aktualizacji. Instalator usuwa znane stare pliki bez naruszania cache i układu gier.
- Usunięte dodatkowe trzecie ucho Brima; zachowane efekty ognia, mruganie i pozostałe figurki.

## 0.12.0 — Milka zamiast dotychczasowych petów

- Jedyny pet na półce: Milka, kotka 3D z dużymi zielonymi oczami i białymi łapkami, przygotowana na podstawie przesłanej planszy.
- Usunięte z menu i paczki aktywne grafiki poprzedniego kota, szczura, fretki oraz gekona. Wcześniejsze ustawienia zwierzaków przechodzą na Milkę; opcja bez peta pozostaje dostępna.
- Dwadzieścia pełnych klatek chodu, odpoczynek, sen, pielęgnacja, mruganie, przeciąganie oraz budzenie z ziewaniem.
- Delikatne strącanie pudełka przednią łapką. Bez osobnego wyginania łap ani przenikania kolejnych klatek chodu.
- Przetestowane dopasowanie do półek i ekranów do 4K, kontakt łapki, powrót pudełka oraz klikalność gier podczas ruchu.

## 0.11.0 — Szlak Wilka

- Nowy motyw dark fantasy inspirowany wiedźmińskim klimatem: przydymiony dąb, ciemne żelazo, srebrne okucia i spokojne światło.
- Autorska tekstura drewna, wektorowy medalion wilka, nagłówki w stylu dawnych ksiąg i czytelne tytuły pudełek.
- Spójna oprawa filtra biblioteki, tabliczek figurek, okien uruchamiania gry, Steam, GOG, aktualizacji oraz planszy powitalnej.
- Delikatna animacja światła półek z obsługą ograniczonego ruchu.
- Motyw dostępny obok pozostałych: menu obok zegara → Motyw graficzny → Dark fantasy · Szlak Wilka. Wybór jest zapamiętywany.

## 0.10.1 — podziękowanie wyłącznie na starcie aplikacji

- Plansza autora i Czorcika pojawia się automatycznie po uruchomieniu ARCADE, bez klikania gry.
- Nie pojawia się podczas wybierania ani uruchamiania gier. Pudełko i płyta startują od razu.
- Przycisk „Przejdź do półki”, automatyczne zamknięcie po 3,8 sekundy oraz jednokrotne pokazanie w danym uruchomieniu aplikacji.
- Sprawdzono pełny start, pomijanie, automatyczne zamknięcie, ponowne uruchomienie oraz brak podziękowania w pudełkach.

## 0.10.0 — autor, Czorcik i oprawa filtra

- Autorska ilustracja 3D przedstawiająca @powiedzmiszczerze z kotem Czorcikiem, przygotowana ze zdjęć referencyjnych.
- Krótkie podziękowanie przy wybieraniu gry, przed dotychczasową animacją pudełka i napędu: płynne pojawienie, delikatne zbliżenie, refleks światła i tekst.
- Przycisk „Przejdź do gry”, automatyczne przejście po 3,8 sekundy i obsługa ograniczonego ruchu. Zamknięcie okna anuluje przejście.
- Przełącznik „Wszystkie gry / Tylko zainstalowane” dobiera tło, obrys, tekst i aktywny stan do motywu: Klasyczny, Orzech i mosiądz, Gaming oraz Aurora.
- Skalowanie podziękowania od małego widgetu do Full HD, 1440p i 4K.

## 0.9.1 — ukrywanie niezainstalowanych gier

- Przełącznik „Wszystkie gry / Tylko zainstalowane” bezpośrednio na dole półki, dostępny w każdym motywie.
- Szybka opcja „Ukryj niezainstalowane gry” w głównym menu obok zegara.
- Wspólny filtr dla Steam i GOG, zapamiętywany po zamknięciu aplikacji. Przełączenie widoku zachowuje ustawienie pudełek.
- Połączenie z GOG zachowuje wybrany filtr zamiast automatycznie pokazywać całą bibliotekę.
- Pusta półka pokazuje komunikat zamiast przykładowych niezainstalowanych gier.

Sprawdzono przełączanie na mieszanej bibliotece Steam i GOG, zapis ustawienia, pustą bibliotekę oraz klikalność przycisku we wszystkich czterech motywach.

## 0.9.0 — biblioteka GOG i pobieranie gier

- Logowanie na oficjalnej stronie GOG w osobnym oknie i zapamiętywanie sesji lokalnie. Bez formularza hasła w ARCADE.
- Import posiadanych gier GOG, również ukrytych, oraz automatyczne okładki. Wspólna półka Steam i GOG z oznaczeniem sklepu.
- Wybór instalatorów Windows według języka i rozmiaru, pobieranie do wybranego folderu, postęp, anulowanie i pokazanie pobranego pliku.
- Wykrywanie gier zarejestrowanych przez instalatory GOG na Windows i ich uruchamianie z półki.
- Filtr wszystkich lub tylko zainstalowanych gier, zapisywanie ustawienia pudełek oraz panel skalujący się od małego widgetu do 4K.
- Odłączenie konta usuwa lokalną sesję i zaimportowaną listę.

Po aktualizacji: menu obok zegara → Biblioteka Steam i GOG → GOG · połącz konto / pobieranie. Po zalogowaniu wybierz grę na półce i kliknij „Pobierz z GOG”. Przy instalatorach wieloczęściowych pobierz .exe i wszystkie odpowiadające pliki .bin do jednego folderu, potem uruchom instalator.

Testy: import wielostronicowy, ukryte gry, zmiana konta, tryb offline, sprawdzenie uprawnień do plików oraz pobieranie pliku testowego w natywnym oknie. Sprawdzono otwarcie formularza GOG bez zalogowania; pełny import i pobieranie z rzeczywistego konta wymagają zalogowania użytkownika.

## 0.8.1 — oczy, woda i ogień figurek

- Indywidualnie dopasowane mruganie i subtelny ruch spojrzenia wszystkich dziesięciu kotów.
- Falowanie i refleksy na błękitnych smugach Zephyra oraz Kaia; migoczące płomienie, ciepłe światło i żar u Brima oraz Neko.
- Dopasowany ruch miętowej energii Sory, kryształów Nyx, duchów Luny, zieleni Mori, hologramów Pixa i kul Vyry.
- Efekty ograniczone do właściwych fragmentów ilustracji. Animacje wstrzymują się poza widokiem oraz podczas uruchamiania gry.

## 0.8.0 — pełna animowana kolekcja kotów

- Dziesięć figurek: Zephyr, Sora, Nyx, Brim, Kai, Luna, Mori, Pix, Neko i Vyra.
- Subtelny ruch postaci przy nieruchomych podstawkach, animowane efekty dopasowane do żywiołu oraz krótka reakcja po kliknięciu podstawki.
- Poprawione, równo wyśrodkowane tabliczki z nazwą i rolą; napisy pozostają proste podczas przechylania figurki.
- Osobne przestawianie, zapisywanie i włączanie każdej figurki. Menu obok zegara pozwala pokazać lub ukryć cały zestaw.
- Zachowane ustawienia Zephyra z poprzedniej wersji, układanie wielu figurek bez nachodzenia na siebie i skalowanie do 4K.

## 0.7.0 — pierwsza figurka kolekcjonerska

- Zephyr · Strażnik Wiatru: autorska figurka białego kota na metalowej podstawce, z niebieskimi kryształami i efektem energii.
- Szczegółowy render z wyglądem 3D, delikatne przechylenie, połysk i cień na półce.
- Przeciąganie za podstawkę między półkami oraz zapisywanie pozycji.
- Menu obok zegara: Figurki kolekcjonerskie → pokaż/ukryj Zephyra lub przywróć pozycję.
- Skalowanie do wielkości półek; sylwetka figurki przepuszcza kliknięcia do gier, aktywna jest tylko podstawka.

## 0.6.12 — stabilny obszar klikania pudełek

- Naprawiono kliknięcia przy dolnej krawędzi pudełka: efekt najechania nie podnosi już przycisku spod kursora.
- Zachowano podświetlenie, obrys i rozjaśnienie gry w każdym motywie.
- Kliknięcie działa bez konieczności przenoszenia pudełka na inną półkę.
- Dodano testy górnej i dolnej krawędzi oraz środka pudełek na każdej półce w motywach Realistycznym, Gaming i Aurora.

## 0.6.11 — priorytet klikania pudełek przed petem

- Wciśnięcie myszy na grze natychmiast wstrzymuje peta, także podczas budzenia i przygotowania strącenia.
- Obsługa przeciągania przez przechwycenie wskaźnika wstrzymuje peta tak samo jak przeciąganie systemowe.
- Wszystkie elementy grafiki peta i efektów przepuszczają kliknięcia do półki.
- Dodano testy myszy podczas chodu, snu, budzenia i próby strącenia pudełka.

## 0.6.10 — pełnoekranowe pudełko i napęd

- Widok uruchamiania wypełnia całe okno aplikacji.
- Pudełko, napęd i płyta skalują się do szerokości oraz wysokości, bez stałego limitu wielkości.
- Czytelniejsze, skalowane przyciski i tekst; pionowy układ na wąskich ekranach.
- Zachowano wkładanie płyty od góry i jej nadruk.

## 0.6.9 — wkładanie płyty od góry

- Usunięto szufladkę napędu.
- Płyta unosi się z pudełka, ustawia nad napędem i delikatnie opada na trzpień.
- Osadzenie i docisk poprzedzają rozruch silnika; zachowano nadruk wybranej gry.

## 0.6.8 — duże pudełko i napęd

- Usunięto grafikę komputera z animacji uruchamiania gry.
- Powiększone pudełko po lewej i samodzielny napęd z obracającą się płytą po prawej.
- Tacka wysuwa się bezpośrednio z napędu; płyta zachowuje grafikę wybranej gry.
- Układ dopasowuje się do rozmiaru okna, a na wąskim ekranie elementy ustawiają się jeden pod drugim.

## 0.6.7 — natychmiastowy powrót pudełka

- Po upadku do dołu okna i odbiciach pudełko od razu pojawia się z powrotem na półce.
- Usunięto animację cofania w górę; pozycja pudełka pozostaje zachowana.

## 0.6.6 — pudełka spadają do samego dołu

- Pudełko strącone przez zwierzaka spada aż do dolnej krawędzi okna, niezależnie od półki i rozdzielczości.
- Przyspieszanie podczas upadku, obrót, dwa odbicia i krótki odpoczynek na dole.
- Cień na podłodze, subtelny efekt uderzenia i płynny powrót na miejsce.
- Zachowany układ pudełek; przerwanie animacji przywraca oryginał.

## 0.6.5 — nowy kot i mniejszy wybór petów

- Usunięto smoka, Czorcika i lisa z wyboru zwierzaków oraz paczki aplikacji.
- Dodano nowego realistycznego srebrnego kota w pręgi z bursztynowymi oczami.
- Nowy kot porusza się pełnymi pozami: 24 klatki chodu, osobne pozy delikatnego strącania i ziewania.
- Dla kota wyłączono deformowanie oraz mieszanie łap między obrazkami.
- Zachowano sen, budzenie i ziewanie nowego kota.
- Dostępne pety: kot, szczur, fretka i gekon; poprzedni wybór usuniętego peta przełącza się na kota.

## 0.6.4 — płynniejszy chód wszystkich petów

- Nowy renderer chodu dla kota, szczura, smoka, fretki, gekona i lisa.
- Stały obszar rysowania oraz wyrównanie tułowia i grzbietu usuwają skoki położenia między klatkami.
- Pozycje pośrednie wyliczane z ruchu sylwetki; ograniczone podwójne kontury łap.
- Wygładzanie krawędzi, zachowane drobne krawędzie futra i delikatne wyostrzenie przy powiększeniu.
- Renderowanie dopasowane do DPI; obliczenia ruchu wykonywane w tle.
- Przewijanie widocznej półki nie restartuje już animacji zwierzaka.

## 0.6.3 — większe pety i budzenie Czorcika

- Czorcik jest większy o 85%, a pozostałe zwierzaki o 25%; skala nadal dopasowuje się do okna.
- 16 kolejnych klatek chodu kota zsynchronizowanych z przebytą odległością.
- Osiem klatek ruchu łapki: uniesienie, wyciągnięcie, dotknięcie pudełka i cofnięcie.
- Automatyczna sekwencja budzenia: podniesienie głowy, siad i ziewnięcie, potem spoczynek.
- Stała pozycja tułowia podczas animacji łapki i zatrzymanie animacji po otwarciu gry.

## 0.6.2 — Czorcik na półce

- Nowy realistyczny kot Czorcik, wzorowany na zdjęciach pupila autora, zastępuje poprzedniego kota.
- Czarne puszyste futro z brązowymi refleksami, charakterystyczne oczy i duży ogon.
- 16 póz: osiem faz chodu, siadanie, sen, dwie fazy strącania łapką, mycie, rozglądanie, przeciąganie i języczek.
- Chód zsynchronizowany z odległością, stała skala klatek i pełne sylwetki bez przycinania.

## 0.6.1 — poprawione klikanie gier

- Kliknięcie pudełka otwiera animację również przy drobnym ruchu myszy.
- Przeciąganie zaczyna się po wyraźnym ruchu; puszczenie pudełka zapisuje pozycję bez otwierania gry.
- Po przestawieniu gry można od razu ponownie otworzyć pudełko.

## 0.6.0 — aktualizowanie z GitHuba

- Sprawdzanie stabilnych wydań przy starcie, co godzinę i po wybudzeniu.
- Kafelek z nową wersją, zmianami i postępem pobierania; znika wraz z listą zmian po aktualizacji.
- Pobieranie instalatora, weryfikacja SHA-256 i rozmiaru, instalacja w obecnym folderze i ponowne uruchomienie.
- Zachowanie ustawień, autostartu i skrótów; ponowienie po błędach.
- Menu Sprawdź aktualizacje, bez konta GitHub i bez automatycznej instalacji bez kliknięcia.
- Testy wersji, pobierania, uszkodzonych plików, znikania kafelka i instalacji w miejscu.

## 0.5.0 — nadruki płyt i wnętrze napędu

- Okładka wybranej gry drukowana na płycie w czterech etapach sceny, z otworem i plastikowym rantem.
- Otwierane na zawiasie pudełko z wkładką, zaczepami, uchwytem i animowanym zwolnieniem płyty.
- Nowy fotograficzny korpus komputera retro oraz grafika otwartego mechanizmu CD-ROM.
- Przeniesienie płyty po łuku, wysunięcie i schowanie tacki, docisk, rozruch obrotów i głowica odczytu.
- Pomijanie, anulowanie, tytuł przy brakującej okładce i systemowe ograniczenie ruchu.
- Sprawdzone kliknięcia, żądanie Steam oraz dopasowanie sceny do małych okien i 4K.

## 0.4.2 — same grzbiety i naprawione kliknięcia

- Usunięty widok okładek przodem oraz jego przełącznik; stare ustawienia przechodzą na grzbiety.
- Usunięte modele i powierzchnie frontów 3D.
- Nowe kliknięcie czyści pozostałości po przerwanym przeciąganiu, bez trwałego blokowania gier.
- Test rzeczywistych zdarzeń myszy: grzbiet → otwarcie pudełka → płyta → przycisk Graj → żądanie Steam.
- Sprawdzone ponowne otwarcie po urwanym dragend i pomijanie animacji.

## 0.4.1 — fronty pudełek 3D

- Okładki przodem jako bryły z oddzielnym frontem, zadrukowanym grzbietem i górną powierzchnią.
- Perspektywa, plastikowe ranty, refleksy, cień i lekkie wysunięcie po najechaniu.
- Zachowane przeciąganie, widok grzbietów i skalowanie od małego widgetu po 4K.

## 0.4.0 — Aurora Circuit i instalator Windows

- Polski instalator EXE: instalacja dla bieżącego użytkownika, skróty, opcjonalny autostart, aktualizacja i odinstalowanie.
- Czwarty motyw Aurora Circuit: animowana zorza, obwody, cząsteczki i sygnały świetlne na półkach.
- Pauza animacji w tle i respektowanie ograniczenia ruchu w Windows.
- Chód sześciu petów sterowany przebytą drogą; długość kroku rośnie wraz ze skalą postaci.
- Krótkie przyspieszenie i hamowanie, przenoszenie ciężaru ciała, bez niezależnego przesuwania i zegara kroków.
- Testy rzeczywistego ruchu wszystkich petów, motywu, ograniczenia animacji oraz instalacji / aktualizacji / odinstalowania.

## 0.3.1 — fretka i pełny ekran

- Wycinanie całych sylwetek petów zamiast obcinania ogona i pyszczka na granicach siatki klatek.
- Usunięcie ograniczenia szerokości szafki i proporcjonalne skalowanie aż do 4K.
- Przeciąganie belki rozpoczyna się po ruchu kursora, dzięki czemu dwuklik poprawnie powiększa i przywraca okno.
- Testy okien Full HD, 1440p i 4K w obu widokach, powiększania i przywracania oraz animacji petów.

## 0.3.0 — skalowanie i dynamiczne okno

- Większe pudełka i czytelniejsze tytuły dopasowywane do ich długości.
- Wspólne skalowanie petów, pudełek i półek do dostępnej wysokości okna.
- Zmiana rozmiaru za osiem krawędzi i narożników oraz aktualne wymiary podczas przeciągania.
- Przezroczysty podgląd dopasowania do ekranu, poprawna obsługa wielu monitorów.
- Poziome przewijanie zatłoczonych półek zamiast nieczytelnych miniatur.
- Testy geometrii, ośmiu kombinacji rozmiaru / widoku, petów i podglądu.

## 0.2.0 — pety fantasy i zwierzęta

- Smok, fretka, gekon i lis do wyboru w zasobniku Windows.
- Po 16 póz na nową postać, w tym osiem klatek chodu i dwie klatki strącania.
- Wspólny katalog petów dla menu, ustawień i animacji; zapis wyboru po ponownym uruchomieniu.
- Stała skala animacji oraz wyrównywanie klatek do podłoża na podstawie przezroczystości.
- Osobne tempo spaceru, pozy specjalne i dymek smoka.

## 0.1.0 — pierwsza wersja poglądowa

- Półka Steam jako bezramkowy widget Windows.
- Motywy Gaming · Night Shift, Orzech i mosiądz oraz Klasyczny.
- Okładki lub grzbiety pudełek i przeciąganie na półkach.
- Automatyczne wykrywanie instalacji Steam i pobieranie okładek.
- Filtr wszystkich posiadanych gier po połączeniu przez Steam Web API.
- Instalowanie niezainstalowanych gier przez klienta Steam.
- Animacja pudełka, płyty i napędu PC z lat 90.
- Kot i szczur, dodatkowe pozy, spacer i strącanie pudełka łapką.
- Autostart, zapis układu, menu w zasobniku i podpis autora.






