# Ściągawka z poleceń .NET CLI (PRG1)

### MOBBYN

W tej sekcji znajdziesz najważniejsze polecenia interfejsu wiersza poleceń .NET (CLI) przydatne podczas tworzenia aplikacji w języku C#.

| Polecenie               | Przykład użycia               | Co opisać                                            |
| ----------------------- | ----------------------------- | ---------------------------------------------------- |
| `dotnet --version`      | `dotnet --version`            | Sprawdzenie zainstalowanej wersji zestawu .NET SDK.  |
| `dotnet --list-sdks`    | `dotnet --list-sdks`          | Wyświetlenie wszystkich dostępnych wersji SDK.       |
| `dotnet new list`       | `dotnet new list`             | Wyświetlenie dostępnych szablonów projektów.         |
| `dotnet new console`    | `dotnet new console`          | Utworzenie aplikacji konsolowej w bieżącym katalogu. |
| `dotnet new console -n` | `dotnet new console -n MyApp` | Utworzenie aplikacji konsolowej w katalogu MyApp.    |
| `dotnet restore`        | `dotnet restore`              | Pobranie zależności wymaganych przez projekt.        |
| `dotnet build`          | `dotnet build`                | Kompilacja projektu i odczyt komunikatów o błędach.  |
| `dotnet run`            | `dotnet run --project MyApp`  | Zbudowanie i uruchomienie wskazanego projektu.       |
| `dotnet clean`          | `dotnet clean`                | Usunięcie plików wygenerowanych podczas kompilacji.  |

## Szczegółowy opis poleceń .NET CLI

### 1. `dotnet --version`

Wyświetla aktualnie zainstalowaną wersję zestawu .NET SDK w systemie.

```bash
dotnet --version
```
