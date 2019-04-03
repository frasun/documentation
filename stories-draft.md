### PREPHASE:

SETUP
- Setup test repository
- Create Phantom Workers (open PR, merged PR)

JORDAN
- Setup dev environment
- Setup Heroku

---

### I want to see DMR of my team
SETUP
- Use hardcoded values (DMRi, timezone, working days, team size)

ANTON
- Install Heroku
- Calculate basic DMR (merged PR / (team size * eDMR))
- Add API endpoint (DMR)

JORDAN
- Display DMR

### I want to see more details about how DMR was calculated
ANTON
- Add API endpoint (merged PR count, eDMR, team size)

JORDAN
- Display details about DMR (merged PR count, eDMR, team size)

### I want to know when DMR is below treshold
JORDAN
- Highlight DMR status (good/bad)
