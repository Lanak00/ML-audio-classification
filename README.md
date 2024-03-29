# ML-audio-classification
Given a database with audio parameters extracted from audio recordings of babies, we applied ML algorithms (Neural networks, Logistic Regression, kNN) in order to train our model to recognize whether baby is crying, laughing or producing neutral sounds

-----------------------------------------------------------------------------------------------------------------------------
PROJEKAT IZ PREPOZNAVANJA OBLIKA

Svaki fajl odnosi se na snimke jedne klase (plac, smeh i neutralno). Svaki fajl sadrzi obelezja cija su imena 
data kao imena kolona (osnovna frekvencija, frekvencija prvog i drugog formanta, kao i 12 mfcc, ukljucujuci i nulti;
za svako od pomenutih obelezja izracunati su: srednja vrednost, standardna devijacija, minimum, medijan i maksimum;
statisticke vrednosti racunate su nad celom recenicom, dok su obelezja izvucena na prozorima od 25ms sa preklapanjem
od 10ms, pocetne i krajnje tisine su odstranjene, a osnovna frekvencija interpolirana na mestima gde nije definisana;
obelezja su izvucena pomocu Praat programskog alata za analizu audio snimaka).
Svaki fajl takodje sadrzi jednu kolonu koja predstavlja klasu, te svaki od snimaka (uzoraka) moze pripadati
jednoj od 3 klase: cry (plac), laugh (smeh) ili neutral (neutralno).
