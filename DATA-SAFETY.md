# Doomscroller – Google Play "Data safety" answers

Package name: `com.darkbliser.doomscroller` · Privacy policy URL: see README.md

> Draft based on what the game does (12 Nov 2026). Not legal advice – check the answers when the game changes
> (new online features, analytics, ads, accounts…).

## English (Play Console → App content → Data safety)

**Data collection and security**

| Question | Answer |
|---|---|
| Does your app collect or share any of the required user data types? | **Yes** (only during online play with a join code) |
| Is all of the user data collected by your app encrypted in transit? | **Yes** (Unity Gaming Services use encrypted connections) |
| Which account creation methods does your app support? | **My app does not allow users to create an account** |
| Do you provide a way for users to request that their data is deleted? | **Yes** – via the developer email on the Play Store page; the anonymous ID on the device is deleted by clearing the app data |

**Data types** (everything else: *not collected*)

| Data type | Collected | Shared | Processed ephemerally | Required / optional | Purpose |
|---|---|---|---|---|---|
| Personal info → **Name** (in-game player name, sent to the other players of an online game) | Yes | No | **Yes** | Optional (only online play) | App functionality |
| Device or other IDs → **Device or other IDs** (anonymous Unity player ID) | Yes | No | No | Optional (only online play) | App functionality |
| App info and performance → **Diagnostics** (technical diagnostic data of Unity's online services) | Yes | No | No | Optional (only online play) | App functionality |

Why "Shared: No": Unity processes the data for us as a service provider, and the player name only goes to the other
players in a game the player chose to join – Google does not count either of these as "sharing".

Also in "App content":
- **Ads:** No ads.
- **Target audience:** choose **13 and older** (or 16+). Choosing under 13 brings the stricter "Families" rules.
- **Content rating:** fill in the questionnaire – fantasy violence against monsters, no blood, no chat, players can
  interact online (they see each other's player names), no purchases.
- **Government apps / News / Health:** No.

## Deutsch (Play Console → App-Inhalte → Datensicherheit)

**Datenerhebung und Sicherheit**

| Frage | Antwort |
|---|---|
| Erhebt oder teilt deine App erforderliche Nutzerdatentypen? | **Ja** (nur beim Online-Spiel mit Beitrittscode) |
| Werden alle von deiner App erhobenen Nutzerdaten bei der Übertragung verschlüsselt? | **Ja** (Unity Gaming Services nutzen verschlüsselte Verbindungen) |
| Welche Methoden zur Kontoerstellung unterstützt deine App? | **Meine App erlaubt keine Kontoerstellung** |
| Können Nutzer die Löschung ihrer Daten anfordern? | **Ja** – über die Entwickler-E-Mail auf der Play-Store-Seite; die anonyme ID auf dem Gerät wird durch Löschen der App-Daten entfernt |

**Datentypen** (alles andere: *nicht erhoben*)

| Datentyp | Erhoben | Geteilt | Kurzzeitig verarbeitet | Erforderlich / optional | Zweck |
|---|---|---|---|---|---|
| Personenbezogene Daten → **Name** (Spielername, wird an die Mitspieler eines Online-Spiels gesendet) | Ja | Nein | **Ja** | Optional (nur Online-Spiel) | App-Funktionalität |
| Geräte- oder andere IDs → **Geräte- oder andere IDs** (anonyme Unity-Spieler-ID) | Ja | Nein | Nein | Optional (nur Online-Spiel) | App-Funktionalität |
| App-Informationen und -Leistung → **Diagnose** (technische Diagnosedaten der Unity-Online-Dienste) | Ja | Nein | Nein | Optional (nur Online-Spiel) | App-Funktionalität |

Warum „Geteilt: Nein": Unity verarbeitet die Daten für uns als Dienstleister, und der Spielername geht nur an die
Mitspieler einer Runde, der man selbst beitritt – beides zählt laut Google nicht als „Teilen".

Außerdem unter „App-Inhalte":
- **Werbung:** Keine Werbung.
- **Zielgruppe:** **ab 13 Jahren** (oder ab 16) wählen. Unter 13 bringt die strengeren „Familien"-Regeln mit sich.
- **Altersfreigabe:** Fragebogen ausfüllen – Fantasy-Gewalt gegen Monster, kein Blut, kein Chat, Spieler können online
  miteinander spielen (sehen die Spielernamen der anderen), keine Käufe.
- **Behörden-, Nachrichten-, Gesundheits-Apps:** Nein.
