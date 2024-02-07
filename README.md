Stworzenie systemu wspomagającego działalność bistra.


Tabele:
Tabela 1 - CLIENTS
Tabela 2 - ROLES
Tabela 3 - USERS
Tabela 4 - RESERVATION STATUSES
Tabela 5 - RESERVATIONS
Tabela 6 - TABLES
Tabela 7 - RESERVATION DETAILS
Tabela 8 - ORDER TYPES
Tabela 9 - ORDER_STATUSES
Tabela 10 - PAYMENT STATUSES
Tabela 11 - ORDERS
Tabela 12 - CATEGORIES
Tabela 13 - PRODUCTS
Tabela 14 - ORDER DETAILS


Insert, Select:

Każda tabela została opatrzona odpowiednimi poleceniami INSERT oraz SELECT.


Funkcje:

Funkcja 1: Funkcja oblicza łączny koszt wszystkich zamówień dla określonego klienta.

Funkcja 2: Funckja sprawdza, czy określony klient ma aktywne rezerwacje o statusach "Potwierdzone"
(2) lub "Przybyłe" (4).

Funkcja 3: Funkcja, która zwraca liczbe klientów na dany dzień.


Procedura:

Procedura, która sprawdza czy klient ma na sobie rezerwacje czy nie.


Widoki:

Widok 1: Widok Klienci z niezapłaconymi zamowieniami.

Widok 2: Widok na klienta z łączną ilością zamówień.

Widok 3: Widok na odwołana rezerwacje.


Triggery:

Trigger 1: Trigger, który uniemożliwia wstawianie rezerwacji, jeśli data początkowa.

Trigger 3: Trigger aktualizujący pole Total_Amount w tabeli Orders po dodaniu nowego produktu do
zamówienia.
