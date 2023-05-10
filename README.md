# projekt
**Instalacja**
- Zainstalować `composer`
- Wpisać w terminal `composer install --ignore-platform-reqs`
- Utworzyć folder *img* w *pub*, czyli `./pub/img` (nie jest dodany przez [.gitignore](./.gitignore))
- Uruchomić Apache oraz MySQL (polecam XAMPP)
- Zmienić linijkę ';extension=gd' -> 'extension=gd' w `php.ini` poprzez wejście w program XAMPP, w serwisie Apache -> przycisk Config -> `php.ini`.
- Restart Apache i MySQL
- Dodać bazę danych o nazwie 'cms' z pliku `./sql/cms.sql`
- Do zarejestrowania się wejdź do `localhost/projekt/pub/register/`
- Do zalogownia się wejdź do `localhost/projekt/pub/login/`
- Do panelu admina wejdź do `localhost/projekt/pub/admin/`
- Do wgrania posta po prostu kliknij w przycisk `Wgraj mema` w `localhost/projekt/pub/`

**Dodatkowe**
- Do zmiany stylu strony, trzeba użyć języka CSS w pliku `./src/templates/header.html.twig`
