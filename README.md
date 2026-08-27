# Wątek: Analiza zagrożenia wojennego w Polsce

## Cel
1. **Codzienna ocena sygnałów eskalacji** na podstawie prasy i wybranych źródeł.
2. Utrzymanie dwóch gotowych planów:
   - **Schronienie w Piastowie** — przetrwanie na miejscu (`plan_dom_piastow.md`)
   - **Ewakuacja do Modrzewia k. Szczecina** — plan zapasowy / główny wyjazd (`plan_ewakuacja_modrzewie.md`)

## Jak działa wątek (cykl dzienny)
1. **Skan** — przegląd źródeł z `zrodla.md`, wyłapanie zdarzeń z ostatnich 24–72 h.
2. **Klasyfikacja** — każde zdarzenie → kategoria wskaźnika (`wskazniki_eskalacji.md`) + ocena wiarygodności: `potwierdzone` / `prawdopodobne` / `niepotwierdzone`.
3. **Wpis do dziennika** — `dziennik/RRRR-MM-DD.md`: co się stało, kategoria, trend 7-dniowy, bieżący **POZIOM (0–4)**.
4. **Rekomendacje** — aktualizacja `rekomendacje_biezace.md`: konkretne działania na dziś/tydzień wg POZIOMU.
5. **Zmiana POZIOMU** — tylko przy potwierdzeniu w ≥2 niezależnych typach źródeł i utrzymaniu trendu, nie na pojedynczym nagłówku.

## Zasady analityczne (anty-panika, anty-bagatelizowanie)
- Sygnał vs szum: pojedynczy incydent ≠ trend.
- Źródła oficjalne + OSINT zweryfikowany > media społecznościowe.
- Zawsze podawany poziom pewności.
- Trend liczony w oknie 7 dni, nie z jednego dnia.
- Rekomendacje proporcjonalne do POZIOMU — bez wyprzedzania faktów, ale i bez zwłoki gdy trend rośnie.

## Pliki
| Plik | Zawartość |
|---|---|
| `wskazniki_eskalacji.md` | Katalog wskaźników + drabina POZIOMÓW 0–4 z wyzwalaczami i działaniami |
| `zrodla.md` | Lista źródeł (oficjalne, analityczne, media, OSINT, lokalne) |
| `rekomendacje_biezace.md` | Co robić teraz — rolowane, aktualizowane co skan |
| `plan_dom_piastow.md` | Schronienie na miejscu |
| `plan_ewakuacja_modrzewie.md` | Trasa, wyzwalacze wyjazdu, załadunek, miejsce docelowe |
| `lista_wyposazenia.md` | Zakupy/sprzęt z priorytetami P0/P1/P2 + budżet |
| `lista_przygotowan.md` | Wszystkie zadania (zakupy + dokumenty + dom + auta + rozmowy) z terminami |
| `plan_cwiczen.md` | Ćwiczenia rodzinne + kalendarz roczny |
| `profil_rodzina_zasoby.md` | Dane rodziny, dom, Modrzewie, auta |
| `analiza_2022_wzorzec.md` | Retrospektywa 2022 — framework ostrzegania |
| `dziennik/` | Wpisy dzienne |

## Status
- Utworzono: **2026-08-27**
- POZIOM bazowy: **0 (TŁO)** — do potwierdzenia pierwszym pełnym skanem
- Sekcje `⟨DO UZUPEŁNIENIA⟩` czekają na dane od użytkownika (patrz kwestionariusz w rozmowie)
