# Plan antrenament — sep–dec 2026

Site personal cu planul meu de antrenament pentru septembrie–decembrie 2026. Îl folosesc ca să-mi urmăresc progresul și să am planul la îndemână pe telefon, la sală.

Nu e un program general și nu e un sfat pentru altcineva. Greutățile, exercițiile și regulile sunt calibrate pe istoricul meu din Strong și pe situația mea (istoric de menisc, 3 zile de sală pe săptămână, deficit caloric). Dacă îl citești, ia-l ca pe un exemplu de structură, nu ca pe un plan de urmat.

## Ce conține

- **Unde sunt** — comparație greutăți august vs. septembrie, din exportul Strong
- **Bloc 1** (7 sep – 11 oct) — Upper / Lower / Full Body
- **Bloc 2** (12 oct – 15 nov) — Push / Pull / Legs cu exerciții noi
- **Bloc 3** (16 nov – 20 dec) — superseturi antagoniste
- **Reguli** — genunchi, non-negociabile, deload, ce trimit coach-ului

Pagina detectează ziua curentă și arată antrenamentul zilei. Bifa „făcut azi" se salvează local în browser, nu pleacă nicăieri.

## Hosting

Un singur fișier, `index.html`, fără build și fără dependențe în afară de fonturi (Google Fonts).

Pe GitHub Pages: Settings → Pages → Source: *Deploy from a branch* → `main` / `/ (root)` → Save. Site-ul apare la `https://<user>.github.io/<repo>/`.

## Actualizare

La finalul fiecărui bloc (11 oct, 15 nov, 20 dec) export CSV din Strong, compar etaloanele și ajustez blocul următor direct în `index.html`.
