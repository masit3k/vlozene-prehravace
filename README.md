# Vložené přehrávače třetích stran – živá ukázka

Ukázka k individuální prezentaci v předmětu Internetové technologie – client side (ETE89E, ČZU PEF).

Tři přehrávače na jedné stránce:

- **A) klasický iframe** (YouTube): přehrávač se stáhne hned při načtení stránky,
- **B) fasáda (facade)** (YouTube): jen náhledový obrázek a tlačítko, přehrávač (`youtube-nocookie.com`) až po kliknutí,
- **C) Spotify s `loading="lazy"`**: 6 000 px níž, prohlížeč ho stáhne, až když se k němu přiblížíte.

Otevřete DevTools → Network a obnovte stránku. Filtr `nocookie` ukáže jen přehrávač B, filtr `spotify` jen přehrávač C.

Stránka běží na GitHub Pages. Otevřená přímo ze souboru (`file://`) hlásí YouTube chybu 153, protože prohlížeč neposílá hlavičku Referer.
