## Projekt - konfiguracja

1. Uruchom Docker.
2. Wykonaj polecenia:
   - `docker compose build`
   - `docker compose up -d`
   - `docker compose exec app make init_project`

Serwer będzie dostępny pod adresem http://localhost:8080/.

## Wersje

- PHP: 8.2
- Symfony: 6.2.5

## Opis

Projekt jest skonfigurowanym szkieletem Symfony do tworzenia aplikacji. Wykorzystuje podstawowe zależności i narzędzia dla Symfony 6.2.5. Projekt jest uruchamiany w środowisku Docker.

### Struktura katalogów

- `src/` - Pliki źródłowe aplikacji.
- `tests/` - Testy jednostkowe i integracyjne.
- `.docker/` - Konfiguracja Docker Compose i Dockerfile.

## Zależności

Projekt korzysta z różnych zależności i bibliotek, takich jak Doctrine, Symfony Bundles, Twig, itp.
