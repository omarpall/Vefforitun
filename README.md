# Fooþjónusta

Vefsíða fyrir revolutionary nýjung í þjónustubransanum: Fooþjónusta.

## Upplýsingar um hvernig keyra skuli verkefnið

Verkefnið er geymt á GitHub og notast skal við `git` til að sækja verkefnið og þegar gerðar eru breytingar.

Í verkefninu notum við node.js. Til að nota það þarf að setja það upp, og fara svo í `/gogn` möppuna (í command line, terminal eða öðru skipanalínuforriti) og nota `npm run dev` til að keyra síðuna. Ef til vill þarf fyrst að gera `npm install` til að sækja alls konar sem er notað, t.d. browser-sync.

Við notum lint í css. Keyra skal `npm run lint` til að skoða hvort einhverjar lint reglur séu brotnar.

## Lýsingu á uppsetningu verkefnis, hvernig því er skipt í möppur, hvernig CSS er skipulagt og fleira sem á við

Í rót verkefnisins (`/Vefforritun` möppu), er þessi README.md skrá, og tvær skrár með lýsingu á markmiði verkefnisins, annars vegar `stort-verkefni1.md` og hins vegar `stort-verkefni1.pdf`. Allur kóði síðunnar er svo í `/gogn` möppu.

Í `/gogn` möppu eru `package.json`, `stylelintrc`, og svo allur html kóði fyrir síður verkefnisins. Einnig eru þar allar myndir sem notaðar eru á vefsíðunum. Útlit síðunnar er í `styles.css` skjali.

Við notumst við SASS tæknina í þessu verkefni. Í `/scss` möppu er að finna allar `.scss` skrár sem við notum. Þegar `npm run dev` er  gangi er hægt að gera breytingar í `.scss` skrám og þær vistast sjálfkrafa í `styles.css` og birtast á síðunni. Því þarf aldrei að eiga beint við skjalið `styles.css`.


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
