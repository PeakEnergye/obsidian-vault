# CLAUDE.md – Obsidian-Vault von Tobias

## Über mich
- BWL-Student im 1. Semester an der TH Deggendorf
- Rennradfahrer in der Bundesliga
- Sprache im Vault: **Deutsch**

## Ordnerstruktur
| Ordner | Inhalt |
|---|---|
| `00 Inbox/` | Eingang für alle neuen Notizen und die Tagesnotizen (`JJJJ-MM-TT.md`). Wird regelmäßig einsortiert. |
| `01 Uni/` | Vorlesungsmitschriften, Skript-Zusammenfassungen, Prüfungsvorbereitung, Hausarbeiten |
| `02 Training/` | Trainingseinheiten, Rennberichte, Trainingspläne, Saisonplanung |
| `03 Wirtschaft/` | Wirtschaftsthemen außerhalb des Studiums: Nachrichten, Unternehmen, Märkte, Bücher |
| `04 Projekte/` | Eigene Projekte mit klarem Ziel (eine Notiz oder ein Unterordner pro Projekt) |
| `05 Vorlagen/` | Obsidian-Vorlagen – **nur Vorlagen**, keine normalen Notizen |
| `Claude/` | Arbeitsdateien, Entwürfe und Auswertungen, die Claude erstellt |

Unterordner in `01 Uni/` und `02 Training/` (z. B. pro Modul oder Saison) sind erlaubt, wenn sie gebraucht werden.

## Vorlagen
| Vorlage | Wofür | Ablage | Dateiname |
|---|---|---|---|
| `Vorlesung` | Mitschrift einer Vorlesung | `01 Uni/` | `JJJJ-MM-TT Modul – Thema` |
| `Training` | Eine Trainingseinheit | `02 Training/` | `JJJJ-MM-TT Training – Einheit` |
| `Rennen` | Rennbericht | `02 Training/` | `JJJJ-MM-TT Rennen – Name` |
| `Tagesnotiz` | Tagesnotiz (Plugin „Tägliche Notizen“) | `00 Inbox/` | `JJJJ-MM-TT` |

Jede Notiz hat im Kopf die Property `typ` (vorlesung, training, rennen, tagesnotiz, …) und `datum` im Format `JJJJ-MM-TT`. Wenn du neue Notizen eines dieser Typen anlegst, übernimm Aufbau und Properties der passenden Vorlage.

## Regeln für die Arbeit im Vault
1. **Neue Notizen** landen in `00 Inbox/`, außer der Zielordner ist eindeutig klar.
2. **Verlinken** mit `[[Wikilinks]]`, nicht mit Markdown-Links. Verwandte Notizen (z. B. Vorlesung ↔ Modul) aktiv verlinken.
3. **Tags** klein und ohne Leerzeichen (`#uni`, `#training`, `#rennen`), verschachtelt mit `/` (z. B. `#uni/mikroökonomie`).
4. **Nicht löschen, umbenennen oder verschieben** ohne Rückfrage – Ausnahme: Einsortieren aus der Inbox, wenn ich darum bitte.
5. **Nicht anfassen:** `.obsidian/plugins/` (besonders `obsidian-git`). Änderungen an anderen `.obsidian/`-Einstellungen nur auf ausdrücklichen Wunsch.
6. **Git:** Das Plugin obsidian-git sichert den Vault automatisch. Selbst nur committen, wenn ich es ausdrücklich verlange.
7. **Zitierweise** bei Uni-Arbeiten: nach den Vorgaben der TH Deggendorf (BWL).
8. Zahlen und Fakten (Trainingswerte, Ergebnisse, Wirtschaftsdaten) nie erfinden – fehlende Werte leer lassen oder nachfragen.
