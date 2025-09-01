# Horloge

# Param�tres

- Diam�tre du disque/support : � ~650 mm
- Longueur bras : ~400 mm (centre ? extr�mit�)
- Masse bras : � 2 kg, centre de gravit� � ~200 mm de l�axe
- Vitesse : 1 tr/min (sens horaire)

- Couple statique � l�horizontale � m�g�r = 2�9,81�0,2 � 3,9 N�m.
![Description du couple](torque.webp)

Avec pertes (vis sans fin, frottements) et marge x2�3 => viser 8�12 N�m au niveau de l�axe.


# Liste de composants 
version robuste et simple � sourcer

## M�canique

- Axe acier rectifi� �12 mm (longueur selon �paisseur de panneau + entretoises, pr�voir ~160�200 mm).
- 2 roulements � billes type UCFL204 (paliers fonte avec roulement � al�sage 20) ou version compacte : 2� 6001-2RS (� int. 12, � ext. 28) + logements.
- Moyeu de bras (aluminium/acier) al�sage �12 avec vis de pression pour fixer le bras.
- Roue dent�e pour vis sans fin (bronze/acier), 60 dents module 1 (exemple � ~60�65 mm, al�sage adapt� � l�axe �12).
- Vis sans fin module 1 (1 d�part) sur arbre moteur, entraxe correspondant � la roue.
- Ch�ssis / panneau support (contreplaqu� 15�18 mm ou t�le) + entretoises et �querres.
- Fixations (visserie M4/M5, rondelles, frein filet), goupille ou vis pointeau pour solidariser roue/axe.
- But�e axiale (bagues + rondelles de calage) pour �liminer jeu axial de l�axe.

## Motorisation & transmission
- Moteur DC 12 V ~50�100 tr/min en charge, couple =0,3 N�m sur l�arbre moteur.

Avec r�duction 60:1 par vis sans fin ? sortie axe � 1 tr/min et couple �60 ? ~18 N�m potentiel (avant pertes), suffisant.

Accouplement moteur -> vis sans fin (rigide ou flexible 6�8/8�10/� mm selon arbres).

Support moteur r�glable (pour ajuster l�entraxe et le jeu d�engr�nement).

![Moteur](doc.webp)

### Caract�ristiques
![Caract�ristiques du moteur](caracteristiques.webp)


## �lec/Contr�le
- Alimentation 12 V 5 A (marge confortable).
- Contr�leur PWM 12 V (2�10 A) pour r�gler finement la vitesse � 1 tr/min.
- Interrupteur marche/arr�t + porte-fusible (fusible 3�5 A).
- C�bles 1�1,5 mm�, cosses, serre-c�bles.

## S�curit� / Divers
- Carters imprim�s/pli�s pour couvrir roue + vis sans fin.
- Contrepoids discret optionnel (� l�arri�re du moyeu) si besoin d��quilibrer le bras.
- Frein anti-retour inutile avec une vis sans fin (auto-bloquante), mais possible via petit ressort/aimant si n�cessaire.

# Sch�ma

## Moteur

![Moteur et support](moteur.webp)

![Dimensions du moteur](moteur2.webp)

![Dimensions du support](bracket.webp)

## Entrainement

![Vis sans fin et engrenage 60 dents](engrenage.webp)

### Param�tres de transmission

![Param�tres de transmission](table de transmission.webp)

## Roulements

![Roulements](roulements.webp)

# Notes d�assemblage

- Aligner parfaitement roue et vis sans fin (jeu lat�ral minime, l�ger jeu fonctionnel au contact).
- Caler l�axe dans les roulements avec des entretoises pour que la roue tombe bien en face de la vis sans fin.
- Fixer solidement le moyeu sur l�axe (pointeau sur m�plat) et visser le bras au moyeu.
- D�marrer � vitesse plus �lev�e avec le PWM puis r�gler � 1 rpm (une marque sur le bras aide au r�glage).
- V�rifier l��chauffement du moteur apr�s 15�30 min : il doit rester ti�de.
