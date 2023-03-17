# Square-wave-generator


-Cerinte de proiectare schema bloc-
- N=13 

✓ Frecvența de oscilație, fo, reglabilă în intervalul: o 2·N ÷ 4·N [kHz]; 
✓ Factor de umplere: o 0.5; 
✓ Sarcina la ieșire, RL: o N [kΩ];
✓ Valoarea (vârf la vârf) a oscilației la ieșire, Vo, reglabilă în intervalul: o 0 ÷ N/4 [V];
✓ Semnalul la ieșire nu are componentă continuă; 
✓ Domeniul temperaturilor de funcționare: o 00 - 700 grade Celsius (verificabil prin testare în temperatură);

N este numărul de ordine din lista grupei;
✓ Dimensiunile PCB: 40mm x 40mm; 
✓ Material FR4, dublu strat; 
✓ Originea (punctul de coordonate (0,0)) va fi plasată în colţul din stânga-jos al plăcii de cablaj imprimat, astfel toate elementele proiectului vor avea coordonate pozitive;



-Cerinte de proiectare PCB-

Realizarea în tehnologie SMT & PCB

Pentru tehnologia SMT & PCB, circuitul va fi realizat sub forma unui modul electronic a cărui structură de interconectare (PCB) va respecta următoarele cerinţe de proiectare:
•	Dimensiunile PCB: 40mm x 40mm;
•	Material FR4, dublu strat/ grosimea foliei de cupru 18 μm, grosimea plăcii 1,5 mm;
•	Toate componentele se vor plasa pe faţa superioară a plăcii, TOP;
•	Componente pasive SMD chip 0805;
•	Se pot folosi numai tranzistoare bipolare şi TEC-MOS în capsule SMD (SOT 23, D-PAK). Tranzistoarele TEC-J pot fi utilizate numai dacă se justifică necesitatea acestora.
•	Puncte de test: circulare, maxim 5 – justificate de planul de testare;
•	Originea (punctul de coordonate (0,0)) va fi plasat în colţul din stânga-jos al plăcii de cablaj imprimat, astfel toate elementele proiectului vor avea coordonate pozitive;
•	Faţă de marginea plăcii, se va păstra o gardare („clearance”) de 1 mm; aici nu vor fi plasate componente, trasee, texte, etc.;
•	Placa va fi prevăzută cu 2 markeri fiduciali globali pe layerul TOP, la distanța de 200 mil față de marginea plăcii, plasați convenabil; acești markeri vor exista și pe layerul Solder Paste Top (suprapuși peste cei de pe TOP); vor fi utilizați în momentul alinierii șablonului cu placa. Marcajul fiducial va fi un cerc de diametru minim 1mm pe layerul respectiv, aflat într-un spațiu circular de diametru minim dublu față de cercul interior, în care nu se va afla nimic pe nici un layer;
•	Se va acorda o atenţie sporită layer-ului Mască de inscripţionare (Silk Screen); acesta nu trebuie să se regăsească pe pad-urile componentelor;
•	Se va genera un nou layer neelectric, MECANIC. Acesta va conţine: conturul plăcii, desenul de găurire („drill drawing”) şi tabelul de găurire („drill chart/table”, „drill legend”), o secţiune transversală prin circuitul imprimat proiectat („layer stack-up”) şi informaţiile mecanice necesare pentru fabricaţia PCB;
•	Cotele de gabarit/dimensiunile plăcii nu trebuie să se regăsească pe layer-ul electric TOP; acestea, dacă există, se vor plasa pe un layer neelectric mecanic;
•	Placa va fi prevăzută cu elementele de identificare ale proiectantului (nume, prenume, grupă, PDCE I 2022-2023).
•	Pentru traseele de interconectare se dau următoarele lăţimi:
•	Curent de 1A - 28 mil;
•	Curent de sute de mA - 22 mil;
•	Semnal - 18 mil.
Spaţierea, în toate cazurile, va fi de 12 mil. Găurile de trecere pentru semnale (vias-uri) vor avea diametrul de 0,4 mm. 2 | 5 Fișierele Gerber - standard 274X şi fişierul Excellon trebuie să conțină următoarele informații:
•	Conturul plăcii (board outline);
•	Layer electric TOP;
•	Layer electric BOTTOM;
•	Layer neelectric Mască de inscripţionare (Silk Screen Top);
•	Layer neelectric Mască de protecţie (Solder Mask Top și Bottom);
•	Layer neelectric Şablon (Solder Paste Top);
•	Lista de aperturi şi fişierul de găurire.

!NOTĂ! Cerinţe de proiectare obligatorii:

•	Dimensiunile PCB: 40mm x 40mm;
•	Material FR4, dublu strat;
•	Originea (punctul de coordonate (0,0)) va fi plasat în colţul din stânga-jos al plăcii de cablaj imprimat, astfel toate elementele proiectului vor avea coordonate pozitive;
•	Dimensiunea traseelor şi spaţierea lor în concordanţă cu specificaţiile menţionate.
Cerințele de proiectare urmăresc cunoașterea, respectarea și aplicarea standardelor IPC din industria electronică în cadrul realizării modulului electronic pentru Proiectul 1, după cum urmează: IPC-2221A, ”Generic Standard on Printed Board Design”, privind rutarea traseelor conductoare, spațierea între conductoare, dimensiunile pad-urilor pentru componentele SMD, prezența marcării și orientarea simbolurilor, prevederea punctelor de test și prevederea punților termice (unde este cazul); IPC-7527, ”Requirements for Solder Paste Printing”, pentru operația de depunere a pastei de contactare; IPC-A-610, ”Acceptability of Electronic Assemblies”, pentru validarea operațiilor de plasare a componentelor și contactare propriu-zisă în vederea acceptabilității modulului electronic asamblat. Aplicarea corectă a standardelor pe parcursul realizării modului în tehnologie SMT poate duce la obținerea unei certificări de inițiere în standardele IPC recunoscută de industria electronică (eliberare de certificat). Pentru simulare și proiectare layout se va utiliza programul OrCAD – versiunea Lite (free) - atenţie la limitările impuse! Software-ul poate fi descărcat de la adresa: LINK RESURSE CAD: shorturl.at/frBVY

