# ToDo & Roadmap

Offene Punkte, Ideen und technische Schulden, die wir abarbeiten wollen.

## Infrastructure & Resilience
- [ ] **Model Fallback Chain:**
  - Chain wurde konfiguriert (Gemini -> Claude -> Flash), muss aber im Ernstfall (Simulation) validiert werden.
  - Ziel: Sicherstellen, dass der Switch automatisch und zuverlässig passiert, wenn der Primary Provider (Google) ausfällt.

## Integrations
- [ ] **Google Workspace (GOG):**
  - Skill `gog` ist systemseitig vorhanden (`openclaw/skills/gog`).
  - Muss evaluiert, konfiguriert und getestet werden (Gmail, Calendar, Drive).
  - Ziel: Echte Kalender-Checks und Email-Summaries direkt im Chat.
