Użytkownik jest pytany o podanie nazwy miasta i imienia, nazwiska i numeru PESEL a następnie wprowadza te dane za pomocą konsoli.
Następnie kod sprawdza, czy numer PESEL jest poprawny za pomocą metody statycznej IsValid z klasy PeselCheck. Jeśli numer jest poprawny, tworzy się plik tekstowy o nazwie równej numerowi PESEL i zapisuje do niego dane wprowadzone przez użytkownika. Plik jest zapisywany w folderze "dane" na pulpicie użytkownika. Jeśli plik o tej samej nazwie już istnieje, zostaje nadpisany nowymi danymi.
