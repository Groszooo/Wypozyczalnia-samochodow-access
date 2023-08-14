# Wypozyczalnia-samochodow-access
Baza danych wypożyczalni samochodów w programie Microsoft Access


Wypożyczalnia samochodowa to firma zajmująca się udostępnianiem samochodów osobowych klientom w zamian za ustaloną opłatę. W ofercie mojej wypożyczalni znajduje się wiele pojazdów, tak aby każdy klient mógł wybrać coś dla siebie. 
Podczas tworzenia aplikacji założyłem, że za oddanie samochodu po terminie kara wynosi podwójną opłatę dzienną za każdy dzień zwłoki.
Aplikacja otwiera się formularzem z informacją o autorach bazy danych i pozwala przejść do menu. W menu jest dostęp do wielu funkcji zaimplementowanych przez twórcę aplikacji. Znajdziemy tam formularze umożliwiające m. in.:

- przegląd całej bazy danych, wszystkich istniejących tabel i rekordów w nich zapisanych,
- otwarcie opisu bazy,
- przejście do kolejnego formularza "Raporty i zestawienia"
- wypożyczenie samochodu,
- zwrot samochodu,
- oddanie samochodu do naprawy,
- dodanie nowego klienta,
- dodanie nowego samochodu,
- dodanie nowego modelu samochodu,
- zamknięcie całej aplikacji.

W formularzu "Raporty i zestawienia" mamy możliwość wyświetlenia raportów i zestawień, które zostały przygotowane przez twórcę aplikacji. Dostępne są:
- zestawienie sumy opłat, które klienci zapłacili za auta wypożyczone w zadanym przedziale czasu,
- znalezienie najczęściej psującego się samochodu,
- znalezienie samochodów, które nigdy nie były w naprawie,
- znalezienie samochodów, które były wypożyczane najczęściej,
- znalezienie samochodów, które były wypożyczane najdłużej,
- zestawienie samochodów wypożyczonych w dowolnie zadanym przedziale czasu,
- zestawienie wszystkich samochodów, które psuły się w dowolnie zadanym przedziale czasu, wraz z podsumowaniem ilości napraw dla każdego z tych samochodów,
- zestawienie wszystkich klientów bazy danych, którzy wypożyczali samochody, wraz z wyświetleniem łącznej kwoty, za jaką każdy klient wypożyczył samochody.

Zestawienia zostały zrealizowane za pomocą kwerend w języku SQL, natomiast funkcje wypożyczenia, zwrotu oraz oddania samochodu do naprawy zostały zrealizowane za pomocą VBA.
