# ⚽ GolBet

Simulador académico de apuestas de fútbol donde se arriesgan FutCoins, no dinero.

Curso de Desarrollo de Software · .NET 8 · Arquitectura N-Capas.

## Estructura de la solución

| Proyecto | Tipo | Referencia a |
|---|---|---|
| GolBet.Web | ASP.NET Core MVC | GolBet.Services |
| GolBet.Services | Class Library | GolBet.Repositories, GolBet.Entities |
| GolBet.Repositories | Class Library | GolBet.Entities |
| GolBet.Entities | Class Library | — |

Las referencias van en una sola dirección: Web → Services → Repositories → Entities.
