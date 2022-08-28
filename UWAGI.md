Program.cs:
1. W lini 15 znajduje się błędna nazwa pliku "data.csv". Poprawiono z "dataa.csv" na "data.csv".

DataReader.cs:
1. W liniach 32-38 zwraca wyjątek przy próbie przypisania pustych danych. Dodano try-catch (linie 32-45).
2. W lini 27 znajduje się błędny warunek kontynuacji pętli. Zmieniono z <= na <.
3. W liniach 52, 87 i 98 brakuje warunku zabezpieczającego przed pustymi danymi. Dodano warunek if.
