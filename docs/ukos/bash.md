# Ściągawka z poleceń Bash (UKOS)

W tej sekcji znajdziesz najważniejsze polecenia powłoki Bash przydatne w codziennej pracy programisty.

| Polecenie | Przykład użycia                | Co opisać                                                        |
| --------- | ------------------------------ | ---------------------------------------------------------------- |
| `pwd`     | `pwd`                          | Wyświetlanie ścieżki bieżącego katalogu.                         |
| `ls`      | `ls -la`                       | Listowanie plików, także ukrytych, w formacie szczegółowym.      |
| `cd`      | `cd docs/ukos` oraz `cd ..`    | Przechodzenie do katalogu i katalogu nadrzędnego.                |
| `mkdir`   | `mkdir -p docs/ukos`           | Tworzenie katalogu wraz z brakującymi katalogami nadrzędnymi.    |
| `touch`   | `touch bash.md`                | Tworzenie pustego pliku lub aktualizacja czasu jego modyfikacji. |
| `cp`      | `cp bash.md bash-backup.md`    | Kopiowanie pliku; wspomnij o opcji `-r` dla katalogów.           |
| `mv`      | `mv bash-backup.md archive.md` | Przenoszenie i zmiana nazwy pliku.                               |
| `rm`      | `rm archive.md`                | Usuwanie pliku i ostrzeżenie, że operacja omija kosz.            |
| `cat`     | `cat bash.md`                  | Wyświetlanie zawartości pliku w terminalu.                       |
| `clear`   | `clear`                        | Czyszczenie widoku terminala bez usuwania historii poleceń.      |

## Szczegółowy opis poleceń

### 1. `pwd` (Print Working Directory)

Wypisuje bezwzględną ścieżkę aktualnego katalogu, w którym się znajdujesz.

```bash
pwd
```
