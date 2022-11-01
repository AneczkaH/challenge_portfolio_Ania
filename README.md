# TASK 1

* [Subtask 1](#subtask-1)
* [Subtask 3](#subtask-3)
* [Subtask 4](#subtask-4)
* [Subtask 5](#subtask-5)

## Subtask 1
8 pkt :blush:

## Subtask 3
Cześć!!!

Jestem Ania :woman: zdecydowałam się na udział w challengu aby uporządkować dotychczas zdobytą wiedzę i wykorzystać ją w praktycę. 

Myślę, że uczestnictwo w tym projekcie pozwoli mi rozwinąć skrzydła i poznać wiele wspaniałych, ciekawych osób :smiley:.

Moim głownym celem jest jak najszybsze znalezienie pracy. :computer: :office:

## Subtask 4

### Scouts Panel
* [Opis aplikacji](#opis-aplikacji)
* [Lista funkcjonalności](#lista-funkcjonalności)
* [Ocena interfejsu](#ocena-interfejsu)
* [Ocena intuicyjności aplikacji](#ocena-intuicyjności)
* [Zauważone błędy](#zauważone-błędy)

#### Opis aplikacji
Aplikacja przeznaczona do zarządzania graczami piłki nożnej. 
Pozwala łowcom talentów przeglądać wskaźniki, umiejętności, raporty meczowe poszczególnych graczy.
Składa się ze strony głównej https://scouts-test.futbolkolektyw.pl/

Strona graczy

Strona konkretnego gracza

Strona meczów

Strona raportów

#### Lista funkcjonalności
- Logowanie
- Przypomnienie hasła
- Zmiana języka na Angielski
- Wylogowanie

Strona Główna
- Wyświetlenie statystyk: liczba graczy, liczba meczy, liczba raportów, liczba akcji.
- Wyświetlenie ostatnich aktywności - tutaj dodałabym ostatnio stworzony raport - wydaje się jakby go brakowało.
- Dodanie gracza - dodałabym przycisk na Stronie gracza, aktualnie tylko z poziomu strony głównej można dodać gracza.
- Wyświetlenie krótkiej informacji o aplikacji, jej Loga oraz link do kontaktu z DEV TEAM

Strona Graczy
- Wyświetlenie/wygenerowanie tabeli z listą graczy - fajnie gdyby można było ustawić więcej rekordów na stronę np. do wyboru 10/50/100?- teraz jest na sztywno 10 graczy.
- Dawnload CSV - wygenerowanie pliku csv - byłoby fajnie gdyby mozńa wyło wygenerować całą listę. Na ten moment generuje się tylko dla wyświetlonych na stronie.
- Print możliwość wydruku tabeli - byłoby fajnie gdyby można było wydrukować liste graczy w wierszach. Przy wydruku następuje formatowanie podobne jak wyświetlenie tabeli na urządzeniu mobilnym.
- view columns - Możliwość wyboru kolumn tabeli: |Imię | Nazwisko| Wiek| Klub | Pozycja | Recenzja | Mecze| Raporty|
- Sortowanie tabeli |Imię | Nazwisko| Wiek| Klub | Pozycja | Recenzja |
- Filtrowanie tabeli: Imię | Nazwisko| |Wiek min max| Klub | Pozycja| Recenzja min max|
- Reset ustawionych filtrów
- Wyszukiwanie
- Edycja Gracza - naciskając w wybrany wiersz tabeli. - bardziej intuicyjne byłoby wprowadzenie przycisku/ikony edycji tak jak jest zrobiona edycja meczu lub raportu.
A naciśnięcie w wybrany wiersz mogłoby powodować przeglądanie karty zawodnika i ewentualnie wewnątrz dodać przycisk edytuj.

Strona - MECZE
- Wyświetlenie tabeli meczów wybranego zawodnika
- Dodanie Meczu (poprzez przycisk "DODAJ MECZ")
- edycja Meczu (poprzez naciśnięcie ikony ołówka w kolumnie Akcje)
- rozpocznij mecz (poprzez naciśniecie ikony piłki w kolumnie Akcje)
- wygeneruj Raport (poprzez naciśnięcie ikony kartki w kolumnie Akcje)

Strona RAPORTY
- Wyświetlenie tabeli raportów wybranego zawodnika:
- dodanie raportu (poprez kliknięcie przycisku "DODAJ RAPORT")
- edycja raportu (przycisk ołówka w kolumnie Akcje)


Do tabeli graczy, meczy i raportów dodadałabym możliwość przeglądania bez wchodzena od razu do edycji. Np. klikając dany wiersza wchodzimy do karty a dopiero tam mamy edycję. Przycisk edycji mógłby być zarówno na liście jak i wewnątrz przegladanego rekordu.
Do kart edycji gracza, meczu, raportu dodałabym przycisk Anuluj.
Nie zauważyłam możliwości usunięcia gracza/meczu/raportu.
Może warto wprowadzić uprawnienia na zasadzie że zalogowany uzytkownik może usuwać i edytować tylko graczy których sam dodał (jest autorem).
Dobrze by było, aby system nie pozwalał duplikować graczy.
Do pól wypełnianych typu nazwa klubu/pozycja/ liga - użyłabym listę do wyboru, aby ograniczyć przypadkowych wpisów.
Do większości pól dodałabym jakiś pattern - regularne wyrażenia - (imie, nazwisko, mail, telefon)
Do pól typu waga, wzrost, wiek, czas gry dodałabym wartości brzegowe.
Do menu po lewej stronie dodałabym możłiwość wygenerowania listy meczów i listy raportów.
Dodałabym krótką instrukcję jak obsługiwać funkcjonalność "rozpocznij mecz" zauważyłam że w zależności co tam ustawimy pojawia się lista zdażeń podpięta pod konkretny mecz. 



#### Ocena interfejsu
Aplikacja wygląda na niedokończoną. Logo nie kojarzy się z tematyką aplikacji. Brakuje szaty graficznej, która nawiązywała by do piłki nożnej i zawodników.
Szczególnie Strona główna prezentuje się ubogo. Zbyt dużo wolnego miejsca między wyświetlonymi kartami. Za mało informacji do czego służy aplikacja. Plus za prostą formę. Układ kart lepiej prezentuje się na wyświetlaczu urządzenia mobilnego niż na laptopie.

#### Ocena intuicyjności
Intuicyjność na średnim poziomie. pewnych działań trzeba się domyśleć, nie są oczywiste, a czasami wręcz przypadkowe. 

Najtrudniejsza i nadal niezrozumiała jest dla mnie część "rozpocznij mecz" nie wiem jak należy ją wykorzystywać. :confused:

#### Zauważone błędy
Strona Główna:
-karta aktywności: jest literówka i wydaje się że brakuje linka do ostatnio utworzonego raportu.

Strona Gracze
- brak przycisku dodaj gracza hmm trochę dziwne,
- po wprowadzeniu filtra naciskając resen resetuje się tylko wpisane filtry, tabela nie zostaje odświerzona,
- po zmianie języka na polski w filtrach pozycja wiek i recencja jest nadal po angielsku.
Edycja Gracza
- pole waga i wzrost przyjmują wartości ujemne, 0, oraz nierealne - brakuje wartości brzegowych
- pole imię i nazwisko przyjmuje cyfry i znaki specjalne.
- data urodzenia - można wpisać rok 0001 co powoduje że zawodnik może mieć ponad 2000 lat można również wpisać rok 2023 lub aktualną datę co powoduje że zawodnik może mieć 0 lat :astonished:
-  szkoda że po błędnym wpisaniu maila i opuszczeniu kursorem pola nie pojawia się notyfikacja z prośbą o poprawne wpisanie maila. Otrzymujemy informację że akcja się nie powiodła. od serwera otrzymujemy odpowiedż o błędnym zapytaniu i status kod 400 z wiadomością validationError.
-  po zmianie na język angielski opis pola łączy nas piłka i 90 minut pozostaje po polsku.
-  po zmianie Imienia lub nazwiska i zapisaniu zmian po lewej stronie w menu imię i nazwisko nie odświeżają się automatycznie tylko dopiero po kliknięciu w te dane.

edycja meczu
- po zmianie na język polski - opis pola web match i general pozostaje po angielsku
- data gry przyjmuje podobnie jak data urodzin jakieś nierealne roczniki - należałoby wprowadzić wartości brzegowe. 
- pole czas gry należałoby ograniczyć do 90 min + dodatkowe minuty związane z karnymi lub przedłużeniem meczu przez sędziego.
- drużyna przeciwnika oraz drużyna zawodnika, kolor koszulki liga przyjmują znaki specjalne, cyfry  - należaloby wprowadzić jakieś ograniczenia, pattern lub wybór z listy.
- pole nr - przyjmuje wartości ujemne i bardzo duże liczby - należałoby wprowadzić wartości brzegowe.

strona raportów
- klikając przycisk "+DODAJ RAPORT" zostajemy przeniesieni do "strony MECZÓW" - nie otwiera się formularz raportu.
- aby przeglądać raport musimy wejść w przycisk edycji.
- edytując raport klikając w link www.futbolkolektyw.pl otrzymujemy status code 404 Page Not found. 



## Subtask 5

