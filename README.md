
## ⚙️ Gebruik

- Elk project (web of mobiel) haalt automatisch deze bestanden op.
- Vertalingen worden ingeladen via een i18n-backend (zoals i18next of een eigen fetch-oplossing).
- Aanpassingen in deze bestanden worden automatisch gehost en zijn **direct zichtbaar** in de projecten na deployment/build.

## 🧑‍💻 Aanpassingen

Als lid van het `PRAxIS TRANSLATORS` team kun je:
- Vertalingen aanpassen of toevoegen
- **Let op:** wijzig geen bestaande keys (engels) zonder overleg, om breuken in andere projecten te vermijden.

### ✅ Tips voor bewerken

- Zorg dat de JSON geldig blijft (gebruik bij voorkeur een JSON-linter of VSCode-plugin)
- Houd de structuur consistent tussen `nl.json` en `fr.json`

## 🚀 Automatische integratie

Deze repo is gekoppeld aan meerdere projecten, waaronder:

- `mypraxis_app`
- `mypraxis_web`
- Andere MyPraxis microservices

Elke wijziging in dit project wordt automatisch opgepikt in de build/deploy pipelines.

Heb je vragen of moet je iets wijzigen dat impact heeft op meerdere projecten?  
👉 Neem contact op met het dev-team of open een issue.

---
