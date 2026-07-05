# Us Among Roles

A simple mobile-friendly role assignment page for Among Us-style games.

## Use

Open `index.html` in a browser.

1. Add players.
2. Add impostor roles and choose how many impostors are assigned this game.
3. Add non-imposter roles and mark each one as `Crewmate` or `Neutral`.
4. Save the setup as a profile if you want to reuse it later.
5. Click `Assign roles`.
6. Pass the device around so each player can reveal only their own role.

Impostors can also see the other impostors.

## Saved Data

Setups are saved locally in the browser using cookies, with `localStorage` as a fallback for direct file usage. Profiles can be created, updated, selected, and deleted from the page.
