#Aplikacja Webowa do predykcji obciążenia resteuracji na podstawie danych historycznych.

---

##Autorzy

	* Mateusz Tasz
	* Łukasz Wiącek
	* Łukasz Michałuszko

---

#Główne Założenia projektu.

##Cel: 

Stworzenie aplikacji webowej umożliwiającej przewidywanie poziomu obciążenia resteuracji na podstawie danych z poprzednich tygodni.

##Sposób przedstawienia danych:

Aplikacja wyświetla wykres, który przestawia obciążenie resteuracji w poprzednich tygodniach aż do dnia dzisiejszego, następnie tworzy dalszą część wykresu na podstawie danych historycznych stara się przewidzieć obciążenie resteuracji w najbliższych dniach.

---

# Funkcjonalność

Główną funkcją aplikacji jest wyświetlenie wykresu obciążenia resteuracji w poprzednich tygodniach na podstawie danych z bazy danych.
Na podstawie tych danych aplikacja tworzy dalszą część wykresu, przewidującą obciązenie resteuracji w następnych dniach.

Aplikacja powinna być przejrzysta oraz ma jasno przestwiać użytkownikowi potrzebne informacje.

---

# Wykorzystana Technologia

	*Język programowania: Python
	*Framework: Django
	*Baza danych: MySQL
	*Dodatkowe Biblioteki

---

#Metody testowania

Testowanie będzie polegać na uzupełnieniu bazy danych przykładowymi danymi.
Aplikacja pobierze dane do wykresu oraz predykcji.
Po analizie wyników będzie można określić prawidłowość wyświetlanych danych, oraz sposób ich wyświetlania.
