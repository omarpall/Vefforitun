# Fooþjónusta

Vefsíða fyrir revolutionary nýjung í þjónustubransanum: Fooþjónusta. Vefsíðan samanstendur af þremur síðum: Forsíðu, síðu um þjónustuna, og svo Kaupa síðu þar sem hægt er að panta þjónustuna.

## Upplýsingar um hvernig keyra skuli verkefnið

Verkefnið er geymt á GitHub og notast skal við `git` til að sækja verkefnið og þegar gerðar eru breytingar.

Í verkefninu notum við node.js. Til að nota það þarf að setja það upp, og fara svo í `/gogn` möppuna (í command line, terminal eða öðru skipanalínuforriti) og nota `npm run dev` til að keyra síðuna. Ef til vill þarf fyrst að gera `npm install` til að sækja alls konar sem er notað, t.d. browser-sync.

## Lýsingu á uppsetningu verkefnis, hvernig því er skipt í möppur, hvernig CSS er skipulagt og fleira sem á við

Í rót verkefnisins (`/Vefforritun` möppu), er þessi README.md skrá, og tvær skrár með lýsingu á markmiði verkefnisins, annars vegar `stort-verkefni1.md` og hins vegar `stort-verkefni1.pdf`. Allur kóði síðunnar er svo í `/gogn` möppu.

Í `/gogn` möppu eru `package.json`, `stylelintrc`, og svo allur html kóði fyrir síður verkefnisins. Einnig eru þar allar myndir sem notaðar eru á vefsíðunum. Útlit síðunnar er í `styles.css` skjali. Ath. að ekki skal eiga við `styles.css` beint, heldur eru allar stílbreytingar gerðar í `.scss` skrám (sjá neðar).

Við notumst við SASS tæknina í þessu verkefni. Í `/scss` möppu er að finna allar `.scss` skrár sem við notum. Þegar `npm run dev` er keyrt í skipanalínu þá er hægt að gera breytingar í `.scss` skrám og þær breytingar færast sjálfkrafa í `styles.css` og birtast þar með á síðunni. Aldrei þarf að eiga beint við skjalið `styles.css`.

Við notum `lint` í css. Keyra skal `npm run lint` til að skoða hvort einhverjar `lint` reglur séu brotnar.

## Upplýsingar um alla sem unnu verkefnið
Þeir sem unnu verkefnið eru:

### Birkir Freyr Guðbjartsson

HÍ email: bfg6@hi.is

GitHub Username: birkirfreyrg

### Ómar Páll Axelsson

HÍ email: opa2@hi.is

GitHub Username: omarpall

### Stefán Páll Sturluson

HÍ email: sps8@hi.is

GitHub Username: TheGuitarMonkey
