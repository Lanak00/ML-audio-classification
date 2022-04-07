# ML-audio-classification

PROJEKAT IZ PREPOZNAVANJA OBLIKA

U zavisnosti od odabrane baze, potrebno je rešavati problem klasifikacije, regresije ili klasterizacije. Pre 
svega, uraditi analizu baze što podrazumeva i rešavanje nedostajućih vrednosti i po potrebi prevođenje 
kategorija kategoričkih varijabli u numeričke vrednosti. Potom odabrati bar 3 algoritma i unakrsnom 
validacijom uporediti njihove performanse na odabranoj bazi. Pokušati i redukciju dimenzionalnosti
nekom od metoda, pa ponoviti odabrane algoritme i uporediti performanse. Konačno, u izveštaju (do 4 
str.) predstaviti najvažnije detalje iz analize podataka, kao i uporedne analize performansi modela, uz 
kratke teorijske opise korišćenih algoritama. Podrazumeva se da izveštaj treba da ima i uvod u problem, 
cilj istraživanja, kao i zaključke na samom kraju i preporučljivo je navesti korišćenu literaturu. U okviru
pojedinih foldera za projektne fajlove možete naći dodatne dokumente koji mogu da posluže za inspiraciju
ili koji detaljnije opisuju bazu.

Svaki fajl odnosi se na snimke jedne klase (plac, smeh i neutralno). Svaki fajl sadrzi obelezja cija su imena 
data kao imena kolona (osnovna frekvencija, frekvencija prvog i drugog formanta, kao i 12 mfcc, ukljucujuci i nulti;
za svako od pomenutih obelezja izracunati su: srednja vrednost, standardna devijacija, minimum, medijan i maksimum;
statisticke vrednosti racunate su nad celom recenicom, dok su obelezja izvucena na prozorima od 25ms sa preklapanjem
od 10ms, pocetne i krajnje tisine su odstranjene, a osnovna frekvencija interpolirana na mestima gde nije definisana;
obelezja su izvucena pomocu Praat programskog alata za analizu audio snimaka).
Svaki fajl takodje sadrzi jednu kolonu koja predstavlja klasu, te svaki od snimaka (uzoraka) moze pripadati
jednoj od 3 klase: cry (plac), laugh (smeh) ili neutral (neutralno).
