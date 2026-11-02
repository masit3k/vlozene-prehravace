# Vložené přehrávače třetích stran – živá ukázka

Ukázka k individuální prezentaci v předmětu Internetové technologie – client side (ETE89E, ČZU PEF).

Stejné video YouTube dvakrát:

- **A) klasický iframe**: přehrávač se stáhne hned při načtení stránky,
- **B) fasáda (facade)**: jen náhledový obrázek a tlačítko, přehrávač (`youtube-nocookie.com`) až po kliknutí.

Otevřete DevTools → Network, do filtru zadejte `youtube` a obnovte stránku.

Stránka běží na GitHub Pages. Otevřená přímo ze souboru (`file://`) hlásí YouTube chybu 153, protože prohlížeč neposílá hlavičku Referer.
