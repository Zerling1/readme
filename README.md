# readme
Scrum składa się zaledwie z kilkunastu elementów podzielonych na Role, Wydarzenia (Ramy Czasowe), Narzędzia i Reguły.
-Zespół (Deweloperski, Development Team) – Jest odpowiedzialny za dostarczenie działającego produktu.
-Scrum Master (SM) – to coach Scrumowy. Pracuje zarówno z Zespołem, Product Ownerem jak i całą organizacją.
-Product Owner (PO) – jest “klientem zespołu” skupiającym się na stronie biznesowej przedsięwzięcia.
Wydarzenia 
Scrum Wszystkie wydarzenia w Scrumie są ograniczone czasowo
-Sprint – czyli Iteracja. To czas, kiedy Zespół będzie tworzył kolejny przyrost produktu. Sprint zawiera w sobie wszystkie inne wydarzenia. Każda Sprint posiada swój cel, ustalany przy planowaniu.
-Planowanie Sprintu (Sprint Planning) – służy do ustalenia celu i zakresu Sprintu
-Codzienne spotkania (Daily Scrum) – To krótkie (do piętnastu minut), codzienne spotkanie zespołu mające na celu synchronizację pracy i ustalenie stanu planu Sprintu.
-Przegląd Sprintu
Narzędzia : – Przyrost Produktu , -Rejestr Produktowy , – Rejestr Sprintu Reguły: Ograniczenia Czasowe
- Wartości – co jest dla nas ważne? Zasady – dlaczego robimy to co robimy? Ramy (Framework) – co i jak robimy? Dobre Praktyki – jakie techniki warto wypróbować?
Złe Praktyki – jakich technik lepiej unikać?
GIT
GIT vs SVN
1. Opracowany przez Linusa Torvaldsa do wspomagania zarządzaniem jądrem Linuxa
2. Rozproszony system kontroli wersji (a nie zcentralizowany – brak centralnego repozytorium)
3. Każda kopia projektu (tzw. klon/ang. clone), jest osobnym repozytorium (z historią itp.)
4. Każda kopia (klon) projektu jest jego gałęzią i pozostaje nią, dopóki nie połączy się (merge) 2 lub więcej klonów
5. Można mieć kopie zdalne lub lokalne
6. SVN: trunk/tags/branches; GIT: master branch (tags i branches – zawsze)

GIT – zalety
1. Podróże – brak dostępu do internetu
2. Brak centralnego serwera = brak hostingu
3. SVN=teamwork, GIT=(team)freelance
4. Brak hierarchii uprawnień do głównego repozytorium
5. Szybkość (w porównaniu do SVNa) – zoptymalizowany merge
6. Projekt w SVNie można pobrać do GITa (git svn clone… lub svn2git) oraz po czasie z powrotem wrzucić do SVNa (git svn dcommit…)

GIT – różnice
1. Przed commit’em należy dodać plik (git add…)
2. svn checkout = git clone
cechy
Dobre wsparcie dla rozgałęzionego procesu tworzenia oprogramowania
Praca off-line
Wsparcie protokołów sieciowych: HTTP, FTP, SSH.
Efektywna praca z dużymi projektami
Każda rewizja to obraz całego projektu
