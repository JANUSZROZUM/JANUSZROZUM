TDD w pierwszej kolejności pisanie testów do nieistniejących funkcjionalności  a potem pisanie kodu implementująego tę funkcjonalność

programowanie ekstemalne 
cykle napisanie przypadku testowego^uruchomenienie tego -napisanie minimalnego kodu do przejścia testu^ Refaktoryzacja kodu
zakaz kodu produktu jeśłi nie napiszesz testu który nie zostaje zaliczony
nie można pisać testu jednostkowego w więszej ilości jeśli jest zbędny

SOLID 5 zasad
SRP-zasada pojedynczej odpowiedzialnosc- kazda klasa odpowiedzialna jest za jedną rzecz  klasa o nazwie student jedeny powod zmiany to to ze student się zmienił klasa odpowieada za jedną rzecz
OCP- zasada otwarte zamknięte- klasa powinna być zamknięta na aktualizacje a otwarta na rozbudowe złamanie zasady - (modyfikacja funkcji)-coś co już działa-za pomocą dziedziczenia można to naprawić
LSP- zasada podstawienia liskov-- nadpisanie  metody nie powinno wiązać się ze zmianą parametrów można pozmień klasy aby inacze działała ale musi robić to samo musi być zachowana zgodnośc interfejsu--złamanie nie można podmienić kodu gdy jedna rzuca wyjątek a drugi nie -- klasa abstrakcyjna jedzenie ->
ISP-  zasada segregacji interfejsu--zasada segregacji interfejsów aby były małe i konkretne interface przeciwnie do klas możemy mieć wiele interface mozna miec dowolną ilośc i można je dodawać
DIP-zasada--używanie gdzie parametrem jest abstrakt a nie metoda abstrakty i interfejsy a nie metody aby nei być uzaleznionymm on konkretnej klasy


interface z jedną metodą?
znajdować taki punkt przez który będzie można miej zbiior interfejsów który będzie posiadał ich minimalną ilość

aby  danny fragment kodu pojawiał się tylkko raz Dry Dont repeat yourself   tworzyć kod tak aby nie powtarzał się
korzyści zminimalizowanie efentualnych poprawek

kazda zmiana w programie wymaga jednej poprawni w jednym miejscy zamiast w wielu gdy np chcemy coś zmienić
dry czyli kod bez powtózeń

kod powinien napisany być tak aby nie posiadał powtózeń + nie miał tych samych elementów np w obszarze jednej metody 
zasada KISS KEEP IT SIMPLE STUPID
bez udziwnień zbędnych idioto  ine pisać skomplikowanych struktur kod ma być prosty i realizować zadanie nie udziwniamy priorytet łatwy do zrozumienia latwy do wymiany nie udziwniamy nazw zmiennych i klas
musi być na tyle prosty aby ktoś kto przychodzii z ulicy powinen wiedziec coś o tym kodzie
tak aby komentarz  nie był potrzebny


Nie piszemy na zapas  YAGNI-YOU AIN"T GONA NEED IT gdy NIE potrzebujemy danego kodu nie nadpisujemy specjalnie czegos na zapas np napisanie interfejsu albo klasy gdy nie jest potrzebna
TDA TELL DON"T ASK mów zamiast czytać  gdy piszemy metody powinnysmy pytac obiekty o dane dzielić obowiązki   czyli segmentacja na inne miejsce aby zmianić coś i nie szukać tego w kodzie  np w warunku  aby coś wzróciło tak albo nie w właśnie w niej coś zmienić a nie w jakiś if   w warunkach 





