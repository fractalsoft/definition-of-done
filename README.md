Definition of Done
==================

* Stosujemy BDD ([Behavior-driven development](http://en.wikipedia.org/wiki/Behavior-driven_development)).
* Spełniamy testy akceptacyjne klienta.
* Dana funkcjonalność jest **w pełni** przetestowana.
* Wszystkie testy w aplikacji są spełnione.
* Wszystkie testy manualne są opisane. Przypadki te są sprawdzone przed oddaniem kodu. Testy manualne to testy, których automatyzacja jest trudna lub nieefektywna.
* Spełniamy metryki:
  - [Sandi Meter](https://github.com/makaroni4/sandi_meter),
  - [RuboCop](https://github.com/bbatsov/rubocop),
  - [rails_best_practices](https://github.com/railsbp/rails_best_practices),
  - [Reek](https://github.com/troessner/reek)
* Działa tak samo w przeglądarkach:
  - [Google Chrome](http://www.google.pl/chrome/),
  - [Mozilla Firefox](http://www.mozilla.org/firefox/),
  - [Apple Safari](https://www.apple.com/safari/),
  - [Opera](http://www.opera.com/),
  - [IE 10](http://windows.microsoft.com/internet-explorer/)
  + urządzenia mobilne
* Nazwy klas, metod, zmiennych są znaczace (zrozumiałe), a kod jest samokomentujący.
* Stosujemy [prawo Demeter](http://en.wikipedia.org/wiki/Law_of_Demeter).
* Każdy fragment kodu jest sprawdzany przez 2 osoby. [Code Review](http://en.wikipedia.org/wiki/Code_review)
* Stosujemy [Git Flow](http://nvie.com/posts/a-successful-git-branching-model/). Branch master zawiera tylko stabilne wersje ukończonych funkcjonalności. Branch develop zawiera ukończoną funkcjonalność. Nowa funkcjonalność jest dodawana na lokalnym branchu utworzonym od brancha develop. Małe commity!
* Raz w miesiącu zapraszamy mugoli do przetestowania intuicyjności aplikacji.
* Generowanie dokumentacji po zakończeniu danej funkcjonalności:
  - aplikacje w [Ruby on Rails](http://guides.rubyonrails.org/command_line.html#doc)
* Zapisujemy w pliku *CHANGELOG.md* informacje o nowo dodanej funkcjonalności wraz z [numerem wersji](http://semver.org/).
* Nowa funkcjonalność bez grafiki tworzona jest z użyciem frameworku [Bootstrap](http://getbootstrap.com/).
* Zakupujemy odpowiednie obrazki po akceptacji klienta.
* Grafika w wersji końcowej jest w odpowiednim formacie (druk: pdf, web: png/jpg).
* Przygotowane animacje dołączone do projektu.
* Gotowe wszystkie podstrony dotyczące określonej funkcjonalności.
* Stosujemy [Zasadę spójności](http://en.wikipedia.org/wiki/Single_responsibility_principle). 1 klasa = 1 funkcjonalność
