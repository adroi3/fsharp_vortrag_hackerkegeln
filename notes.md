[Originale Präsentation (Wolfgang Kinkeldei)](https://github.com/wki/fsharp_vortrag_hackerkegeln)

--------------------

- Intro
    - PWA (Website) -> Collection von Features/Technologien (Bsp.: Offline nutzbar)
    - Zu allen Features komme ich noch
    - Mit PWAs soll man in Zukunft native Applikationen ersetzen können
    - Kurz Beispiel Web App von Christian Liebel zeigen (https://pwapraxis.liebel.io/)

- Features (12)
    - Features von PWAs
        - Responsive
            - Auf verschiedenen Größen gut aussehen
        - Linkable
            - Einfach zu teilen (über eine URL)
            - Ohne Installation nutzbar
        - Discoverable
            - Sind als Applikation markiert
            - Dadurch können Sie auch einfach von Suchmaschinen gefunden werden
        - Installable
            - Können über einen Browser installiert/deinstalliert werden
        - App-like
            - Hat ein zu einer App ähliches Bedienkonzept
        - Connectivity Independent
            - Offline nutzbar
        - Fresh
            - Hält sich automatisch aktuell
        - Safe
            - Muss mit TLS ausgeliefert werden (HTTPS)
        - Re-engageable
            - Es können Betriebssytem Features verwendet werden (Bsp.: Notifications)
        - Progressive
            - Läuft auf vielen verschiedenen Browsern (Auch alten Versionen)
            - Teilweise nicht mit allen Features

- Erklärungen + Beispiel
    - Unterscheidung Web Apps und Websites (15, 16)
        - Live zeigen
    - Display Modes (browser, fullscreen usw.) (17)
    - Offline First (24)
        - Locking (26)
        - Locking Technologies (27)
        - Service Worker (29, 30)
            - Basic Implementation (33)
                - Live zeigen
                - Install zeigen
        - Cache API (36)

- Weitere nützliche APIs
    - Workbox (46)
        - Nur kurz erwähnen
    - Indexed DB
        - Overview (52)
            - Web Storage
                - Schlüssel-Wert-Paare, intuitiver als Cookies
        - Dexie.js
            - Overview (56)
            - Beispiel/API (57)
    - Background Sync API (61)
    - Push API
        - Overview (65)
        - Details (69)
    - Payment Request API (https://www.nearform.com/blog/payment-request-api-for-online-purchases-in-pwas/)

- New Things
    - Play Store und Microsoft Store unterstützen PWAs (72)
        - Microsoft Store --> Lädt auch Daten aus Bing
    - Badging API (74)
    - Background Fetch API (76)

- Summary (77)