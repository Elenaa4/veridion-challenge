# veridion-challenge

Acest repositoru conține soluția mea pentru provocarea din cadrul programului Veridion Internship Challenge — Autonomous Systems on Mars

Provocarea

Scenariul vizează o aeronavă autonomă care operează pe Marte și detectează o furtună de praf pe ruta sa actuală, la o distanță în aproximativ 12 minute, în condițiile în care comunicarea cu Pământul implică o întârziere.

Prin urmare, aeronava trebuie să evalueze situația și să ia o decizie în mod autonom.

Abordarea mea

Am abordat problema ca pe o provocare caracterizată prin incertitudine, informații incomplete, constrângeri de timp și resurse energetice limitate.

Sistemul propus structurează procesul decizional în trei etape:

Fiabilitatea dovezilor → Fezabilitatea din perspectiva siguranței → Cea mai bună acțiune fezabilă

Designul se concentrează pe:

*   evaluarea fiabilității semnalelor provenite de la senzori, care pot fi contradictorii;
*   separarea observațiilor, a inferențelor și a gradului de încredere;
*   luarea în calcul a incertitudinii privind locația estimată;
*   determinarea momentului în care așteptarea unui răspuns de la Pământ nu mai este utilă din punct de vedere operațional;
*   conservarea unei cantități suficiente de energie electrică pentru a permite revenirea la o stare sigură;
*   eliminarea acțiunilor nesigure înainte de optimizarea alegerii între alternativele fezabile;
*   actualizarea continuă a deciziei pe măsură ce devin disponibile noi informații.

Documentul de design

Documentul conține:

*   Partea 1 — Analiza problemei
*   Partea 2 — Soluția propusă

Acesta include ipotezele, aspectele neelucidate, detaliile tehnice, arhitectura, fluxul de date, logica decizională, pseudocodul, strategia de validare, limitările și abordarea propusă pentru implementare.

Utilizarea IA

Instrumentele bazate pe inteligență artificială au fost utilizate în etapa de explorare pentru a testa validitatea ipotezelor, a identifica situații limită și a structura analiza. Sugestiile primite au fost evaluate și adaptate, nefiind tratate ca cerințe obligatorii.

Autor

Georgiana-Elena Dumitru
