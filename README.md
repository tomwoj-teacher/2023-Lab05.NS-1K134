# 2023-Lab05.NS-1K134

# --------

Lab05.NS - rozszrzony dla grup niestacjonarnych

Tematem zajęć jest stworzenie skrytpów do tematyki zajęć laboratoryjnych, ale i nie tylko.

0. Student(-ka) musi posiadać konto na GITHUB (jeśli nie ma to je sobie zakłada-najlep[iej konto związane z adresem uczelnianym). Student zgłasza zarejestrowany mail do wykładowcy przez SUSZI celem dopisania do osób mogących pracować na repozytorium.
1. Jest założony projekt o nazwie 2023-Lab05.NS-1K131. Link podesłany jest przez SUSZI przez wykładowcę. Należy wejść w link i poprosić o dostęp.
2. Studenci klonują sobie repozytorium projektu lokalnie i pracują u siebie lokalnie na swojej gałęzi - nazwa zgodna z loginem w SUSZI
3. Utworzony i wgrany w gałęzi main jest skrypt manu.bash, który zawiera pozycje do wykonania. Student(ka) po sklonowaniu wybiera zadanie, które będzie wykonywał(a) i wpisuje swoje nazwisko i imię jako komentarz w odpowiednim miejscu.
3. Następnie komituje zmiany w projekcie i wykonuje push do repozytorium.
4. Przez interfejs graficzny wykonuje pull-request swojej gałęzi do gałęzi main i robi od razu merge (ale tylko w przypakdu zaminy w pliku menu.bash).
5. Przed rozpoczęciem tworzenia skryptu należy uaktualnić (pull/fetch) gałąź main w swojej lokalnej kopii repozytorium.
6. Następuje tworzenie skryptu pod nazwą zaproponowaną przez studenta, jednak końcówka nazwy powinna być: .bash
7. Skrypty tworzymy dla powłoki bash, więc pierwsze dwie linie mają wyglądać tak:
#!/bin/wybrana_powłoka
#Nazwisko i imie Studenta(-ki) wykonującego/wykonującej skrypt
8. Po zakończeniu pisania skryptu Student(ka) wykonuje commit i push swojej gałęzi do projektu, a następnie pull request i tyle. Merge wykonuję tutaj ja.

Kolejna wskazówka: skyrpty własne można umieszczać w projekcie w podfolderach o nazwach wynikających np. z waszych loginów wszibowych.

Jednak ja bym propronował, aby były one podzielone tylko na katalogi, których nazwa wynika z powłoki: bash, tcsh, zsh (itd.), czyli wszystkie skrypty lądowałby we wspólnym miejscu (u nas będzie to /bash). To powoduje, że nauczycie się kolejnego elementu współpracy - że pewne rzeczy trzeba uzgodnić w zespole (tutaj grupie), aby unikać nadpisywania swoich rozwiązań.

Zasada ostatnia:
każdy skrypt wykonuje jedną rzecz (skrypt np. A zakłada użytkownika; skrypt np. b zakłada grupę; skrypt np. C dodaje użytkownika do grupy; itd.)

Nazewnictwo czegolokwiek - proszę raczej stosować język angielski.

T.W.
