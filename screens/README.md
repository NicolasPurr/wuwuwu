# Serwis w Django

## court - edytor tras

Screeny z edytora tras znajdują się w folderze court.

Postanowiłem trochę rozszerzyć to zadanie, aby było użyteczne dla mojej strony. Tutaj użytkownik może definiować animacje, składające się z wielu tras jednocześnie.

Na planszy, jaką jest boisko do koszykówki, znajduje się 14 pionów, zatem jedna animacja może obsługiwać 14 tras. Animacja składa się z klatek, podczas których użytkownik może przemieścić od 0 do 14 pionów.

Podczas wyświetlania jakiejś klatki, wyświetlana jest jego poprzednia pozycja i strzałka. Można to oczywiście rozwinąć tak, aby wyświetlane było kilka poprzednich pozycji, niemniej jednak jest to raczej mało pożądane z punktu widzenia użytkownika (plansza stałaby się mało czytelna).

## accounts - autoryzacja i autentykacja

Do tej funckjonalności włączam:
- logowanie,
- rejestracja,
- konto profilu użytkownika (obecnie służące do wylogowania i zmiany hasła)

Hasło musi spełniać rygorystyczne wymagania.

Po 5 nieudanych próbach logowania następuje blokada IP. Jeszcze nie miałem czasu pobawić się w VPN i ochronę przed canvas fingerprinting, żeby sprawdzić, jak się to sprawuje.

Planuję to mocno rozwinąć w kierunku 2FA i mailowego potwierdzenia przed zmianą hasła, ale to dopiero jak już zdecyduję się na to, gdzie to hostować.

## iot_manual

Już pokazywałem w poprzednim Bloku.
