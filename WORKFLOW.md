### Tworzenie Issues
Jeśli chcesz dodać zadanie lub buga, utwórz nowy Issue z nastęnym numerem A/L/F-*. Następnie utwórz nowy branch dla tego problemu. Po zakończeniu prac zmień Issue na PR.

### Pomoc w używaniu Issues i Pull Request
[github/hub](https://github.com/github/hub)
oficjalne rozszerzenie do konsoli wspierające wiele funkcji GitHuba.

Po instalacji można używać w konsoli polecenia `hub` zamiast `git`

Pożądana przeze mnie funkcjonalność, to zamiana Issues na Pull Request, co zapobiega duplikowaniu zadań w tablicy.

W momencie, kiedy **ukończycie** pracę nad problemem i chcecie zrobić merge request, zróbcie z poziomu konsoli

        hub pull-request -i <GitHubowy numer Issue> -b master

gdzie ten GitHubowy numer Issue, to numer z kratką znajdujący się za nazwą issue np [#4](#4)

W ten sposób Issue zostanie zamieniony na Pull Request, z całą historią dyskusji itp.

Pamiętajcie o tym, PR zriobione w inny sposób **zostaną usunięte.**
