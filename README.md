# Magazin cu articole de pescuit

**Proiect realizat de :** Enescu Horia Teodor Gabriel

**Introducere :** Pentru realizarea acestui proiect, am ales ca temă un magazin care să conțină diverse articole de pescuit. Încât pescuitul este unul din hobby-urile mele de peste 14 ani, pot spune că am o oarecare experiență în ce privește articolele pe care eu le voi introduce în magazinul online.

 <details>
 <summary>
   
## Etapa 0

</summary>

  Magazinul online propus de mine va avea atât momeli, cât și articole necesare pescuitului sportiv. Așadar, vor exista 2 categorii : momeli și produse. Din aceste categorii rezultă și subcategoriile care au legătură cu denumirea articolului și firma care l-a confecționat. De exemplu, pentru momeli (mămăligă,porumb,nadă,etc) iar pentru produse (undiță,mulinetă,momitor,plumb,cârlig,etc). Aceste articole vor apărea toate într-o pagină principală, unde va fi afișat și stocul curent al fiecărui articol în parte, precum și prețul și eficiența acestuia. Prin eficiență mă refer la recomandările producătorului în ce privește utilizarea articolului, întrucât fiecare produs în parte este fabricat cu un singur scop, există de exemplu mămăligi care pot fi utilizate la o singură specie de pește. Pagina principală va avea și o opțiune de filtrare a produselor, deoarece cumpărătorul își dorește să cumpere un anume articol și poate nu este interesat să vadă toate ofertele propuse de site-ul meu.

**Paginile vor fi următoarele :**

-> pagina principală, unde cumpărătorul poate vedea toate sugestiile și va putea filtra rezultatele. <br>
-> o pagină care să conțină articolele în urma filtrării.<br>
-> o pagină de creare a unui cont, cu nume și parolă.<br>
-> o pagină de logare într-un cont deja existent folosind nume și parolă.<br>
-> o pagină numită “Coș de cumpărături” unde cumpărătorul va putea plasa comanda. Tot acolo va exista și un istoric cu obiectele pe care acesta le-a cumpărat în trecut. Cumpărătorul nu va putea plasa o comandă dacă nu are un cont.

*Opțional, dacă îmi rămâne timp, doresc să fac și o pagină de feedback. Acolo cumpărătorul poate oferi feedback cu stele de la 1 la 5 pentru un anume articol.*

**Cuvinte cheie pentru pagina principală :**

undiță, lansetă, cârlig, nailon, momitor, plumb, opritor, mulinetă, scaun, umbrelă, suport, mămăligă, nadă, stoc, preț, eficiență, informații.

**Cuvinte cheie pentru pagina de creare cont :**

user, parolă, creare cont

**Cuvinte cheie pentru pagina de logare :**

user, parolă, login

**Cuvinte cheie pentru pagina care conține rezultatele filtrate :**

undiță, lansetă, cârlig, nailon, momitor, plumb, opritor, mulinetă, scaun, umbrelă, suport, mămăligă, nadă, stoc, preț, eficiență, informații

**Cuvinte cheie pentru pagina “Coș de cumpărături” :**

undiță, lansetă, cârlig, nailon, momitor, plumb, opritor, mulinetă, scaun, umbrelă, suport, mămăligă, nadă, istoric, livrare, dată livrare, preț, plasare comandă, preț, cumpărare, contul meu.

**Cuvinte cheie pentru pagina de feedback :**

undiță, lansetă, cârlig, nailon, momitor, plumb, opritor, mulinetă, scaun, umbrelă, suport, mămăligă, nadă, feedback, stele, mulțumit/nemulțumit.

**Site-uri similare :**

https://www.totalfishing.ro/

*Pro : Produsele sunt afișate într-un mod similar cu planul meu de implementare al proiectului. Fiecare produs are și stoc, preț și feedback. Are și opțiune de filtrare.*

*Contra : Pagina principală mi se pare că este mult prea încărcată, sunt adeptul unei implementări mai simple.*

https://marelepescar.ro/

*Pro : Îmi place sistemul de filtrare propus de acest site, se aseamănă cu cel la care mă gandesc și eu.*

*Contra : La fel ca la site-ul anterior, sunt prea multe informații, iar pentru a ajunge la recomandări trebuie dat scroll.*

https://www.fishingmall.ro/

*Pro : Este un site simplist, și după mine chiar eficient și atrăgător, personal așa văd și implementarea site-ului meu.*

*Contra : Site-ul este în doar 2 culori, alb și albastru, iar eu personal doresc un site în mai multe culori, să fie mai modern.*

https://fisela.ro/

*Pro : site realizat în 4 culori, ceea ce îl face din punctul meu de vedere modern și atrăgător. Mai mult decât atât, site-ul conține opțiune de autentificare/logare, precum și un Coș de cumpărături, dorite de mine în implementarea proiectului.*

*Contra : Nu îmi place bara neagră de informații, e mult prea mare. De asemenea, sugestiile le-aș insera în partea dreaptă a paginii, nu în mijlocul acesteia.*

</details>

<details>
 <summary>
  
## Etapa 1
</summary>

### Cerințe
Creați prima pagină a site-ului (doar prima pagină; fără stilizare încă, fiindcă veți primi taskuri legate de acest aspect). Puteți pune în această pagină text care va fi mutat în alte pagini, mai târziu, dar nu faceți încă mai multe pagini fiindcă le vom genera prin Node! La prezentare vă rog să aveți pentru fiecare task notată linia din program la care l-ați rezolvat ca să nu dureze prezentarea mai mult de 3-4 minute. 
Creați un folder al proiectului care va cuprinde toate fisierele necesare site-ului vostru. Creați în el un fisier  numit index.html. Deschideți acest fișier cu un editor de text care marchează sintaxa. Adăugați în fișier doctype și setați limba documentului în tagul html
Adaugati un title corespunzător conținutului textului. Folosiți 4 taguri meta relevante pentru a specifica: charset-ul, autorul, cuvintele cheie, descrierea.
Creați un folder (de exemplu numit "resurse") care va conține toate fișierele folosite de site, dar care nu sunt pagini html (de exemplu imagini, fisiere de stilizare etc). In el creati un folder numit ico. Adaugati un favicon relevant pentru temă. Folosiți https://realfavicongenerator.net pentru a genera toate dimensiunile necesare de favicon și codul compatibil pentru diversele browsere și sisteme de operare. Pentru favicon transparent, trebuie sa setati si o culoare a tile-ului (de background), care trebuie specificata și în tagul meta: <meta name="msapplication-TileColor" content="...culoarea aleasa de voi...">
Împărțiți body-ul în header, main, footer.
În header faceți un sistem de navigare ca în curs (nav cu listă neordonată de linkuri), cu opțiuni  principale (care vor reprezenta paginile site-ului) și secundare (pentru opțiunea "Acasă", adică pagina principală, subopțiunile vor cuprinde linkuri către secțiunile paginii, care vor avea id-uri relevante). Folosiți în header h1 pentru titlul site-ului. 
Folosiți minim un tag dintre: section, article, aside. Trebuie să existe măcar un caz de taguri de secționare imbricate (secțiune în secțiune). Puneți headingul cu nivelul corespunzător nivelului imbricării. Atenție, nu folosim headinguri decât ca titluri pentru tagurile de secționare. Observație: nivelul headingului trebuie să corespundă nivelului de imbricare a secțiunii (de exemplu un tag de secționare aflat direct în body  are titlul scris cu h2, dar un tag de sectionare aflat intr-un tag de secționare care la rândul lui se află în body, va avea titlul scris cu h3
În cadrul secțiunilor folosiți minim 2 taguri dintre următoare taguri de grupare: p, ol, ul, blockquote, dl
Adăugați în pagină o imagine cu descriere, folosind figure și figcaption. Pe ecran mic (mobil) trebuie să se încarce o variantă mai redusă în dimensiune (bytes) a imaginii, pe tabletă o variantă medie, iar pe ecran mare varianta cea mai mare a imaginii. Folosiți un editor grafic pentru cropping și redimensionare pentru a obține cele 3 variante de imagini.
Textul trebuie să conțină toate cuvintele cheie identificate pentru pagina curentă. Puteți găsi mai multe sintagme cheie pe care le puteți folosi, cu https://www.wordtracker.com/  sau https://app.neilpatel.com/en/ubersuggest/keyword_ideas
Acestea trebuie să apară de mai multe ori în pagină, în taguri relevante.
În cadrul textului îndepliniți 3 dintre cerințele de mai jos, la alegere:
marcați cuvintele și sintagmele cheie cu ajutorul tagului b
marcați textul idiomatic (termeni științifici, în altă limbă, termeni tehnici, de jargon, etc) cu tagul i
marcați textul de atenționare cu strong
marcați textul accentuat cu em
marcați textul șters (corectat sau care nu mai e relevant) cu tagul s și textul inserat în loc cu tagul ins
marcați o abreviere cu abbr și cu atributul title specificați sintagma abreviată
marcați un termen definit cu dfn
marcați un citat cu tagul q
Creați următoarele linkuri speciale: 
un link extern (va fi in continutul paginii, nu in meniu, va face referire la alt site si se va deschide in fereastră nouă)
un link în footer către începutul paginii,
minim două linkuri care se deschid într-un iframe (se poate face ca în exemplul de curs, linkuri care deschid videoclipuri relevante de pe youtube în iframe). Atentie nu e vorba de src-ul iframe-ului ce de taguri <a> care la click se deschid in iframe. Iframe-ul va contine in mod default una dintre resursele specificate in linkuri
Un link de tip download
Creați în pagină mai multe zone de details și summary. Pot fi întrebări frecvente, pot fi niște oferte pentru care afișăm titlul și utilizatorul le deschide pe cele care îl interesează, pot fi secțiuni explicative etc.
În footer se vor adăuga cu ajutorul tagului address informații de contact:
telefon fictiv, marcat cu tagul <a> si URI Scheme-ul corespunzător
adresă fictivă care la click deschide o locatie pe Google Maps (locatia in mod normal ar corespunde cu adresa dar voi veti pune drept locatie in maps, Facultatea de Matematica si Informatica)
e-mail fictiv, marcat cu tagul <a> si URI Scheme-ul corespunzător în href
Link care deschide o aplicatie de comunicare precum skype sau whatsapp pentru chat
În footer se va adăuga informație de copyright, folosind tagul small, simbolul specific de copyright cu codul html necesar (forma &cod;) și data creării paginii scrisă în limba română și pusă în tagul time cu atributul datetime corespunzător. 
Pagina trebuie sa fie valida din punct de vedere sintactic. Deci verificati cu validatorul html. Validatorul va fi pregătit într-un tab, la prezentare, și pagina se va valida pe loc.

### Rezolvări

</details>

## Etapa 2

## Etapa 3

## Etapa 4

## Etapa 5

## Etapa 6

## Etapa 7

## Etapa 8

## Etapa 9

## Etapa 10

## Etapa 11
