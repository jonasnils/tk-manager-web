# TK Manager – Web

Web-Version des TK Managers (Tiefkühltruhen-Inventar). Nutzt dieselbe Supabase-Datenbank wie die iOS-App.

- Anmeldung mit E-Mail + Passwort (Supabase Auth). Zugriff nur für Adressen in `public.app_users`.
- Auf dem iPhone in Safari öffnen → Teilen → „Zum Home-Bildschirm“.
- Direkt zu einer Truhe: `…/#tk1` oder `…/#tk2`.

Der Publishable Key in `index.html` ist öffentlich gedacht; der Schutz passiert über Row Level Security in Supabase.
