# Fremde Modelle, Texturen und Himmel

Alles, was nicht in diesem Projekt selbst erzeugt wurde. Sketchfab-Modelle nur mit CC0 oder CC BY.
Epoche der Szene: Altes Reich, um 2500 v. Chr., Bauerndorf am Nil (Regeln in `CLAUDE.md`).

## Modelle

| Titel | Verwendung | Urheber | Link | Lizenz | Epochenprüfung |
|---|---|---|---|---|---|
| Realistic HD Date palm (13/78) | Dattelpalmen: Wedel, Dattelrispen, Stamm- und Kronentextur (als Blattkarten neu zusammengesetzt) | PlantCatalog | https://sketchfab.com/3d-models/f59f6acc24bd42e5a5d59fc0a5ec686b | CC BY 4.0 | Echte Dattelpalme (Phoenix dactylifera) mit hängenden Dattelrispen; im Alten Ägypten verbreitet und auf der Erlaubt-Liste. |
| Acacia tree | Akazien (nah vollständig, fern vereinfacht) | evolveduk | https://sketchfab.com/3d-models/acacia-tree-bb14c2bb679b4d0bb1c578a27e2ddabf | CC BY 4.0 | Schirmakazie (Gattung Acacia/Vachellia), im Niltal heimisch und auf der Erlaubt-Liste; reiner Baum ohne Gegenstände. |
| Wheat – FREE | Ähren für die Emmer-Bildtafeln (Felder) | Yaroslav Karas | https://sketchfab.com/3d-models/wheat-free-ddff74ac0661414a9478bd4d7581c854 | CC BY 4.0 | Begrannte Weizenähren; Emmer ist eine begrannte Weizenart und auf der Erlaubt-Liste. Verwendet nur als Ähren auf selbst gebauten Halmen. |
| Grass Medium 02 | Grasbüschel (als Bildtafeln gerendert) | Rico Cilliers | https://polyhaven.com/a/grass_medium_02 | CC0 | Gewöhnliches Wildgras ohne erkennbare Art, keine Blüten, keine Gegenstände; zeitlos. |

## Figuren (MakeHuman / MPFB)

Werkzeug: MPFB 2.0.17 (MakeHuman für Blender, GPL; das Werkzeug wird nicht weitergegeben, erzeugte Figuren sind frei).
Grundpaket „makehuman_system_assets“, https://static.makehumancommunity.org/assets/assetpacks/makehuman_system_assets.html.
Kleidung (Schurz, Gürtel, Kleid mit Trägern) und Gegenstände (Holzsichel mit Feuersteinzähnen, Läuferstein des
Reibsteins in Nebets Händen, zusammengerafftes Fischernetz aus Pflanzenfaser mit Senksteinen in Idus Hand) sind selbst
gebaut (`blender/scripts/figuren.py`). Epochenprüfung: Sichel aus Holz und Feuerstein, Reibstein mit Läufer (keine
Drehmühle), Netz aus Pflanzenfaser mit Steingewichten; alles im Alten Reich belegt, kein Metall.

| Titel | Verwendung | Urheber | Link | Lizenz | Epochenprüfung |
|---|---|---|---|---|---|
| MakeHuman-Grundkörper (Basemesh) mit Skelett „game_engine“ | Körper und Skelett aller Figuren (ausgedünnt) | MakeHuman-Team (Data Collection AB) | https://www.makehumancommunity.org | CC0 | Neutraler menschlicher Körper ohne Kleidung oder Schmuck; Körperbau, Alter und Hautfarbe eingestellt. |
| Haut „middleage_african_male“ | Haut von Kai (etwas aufgehellt und wärmer) | MakeHuman-Team | wie oben | CC0 | Braune Haut ohne Tätowierung oder Schmuck; passt zur Regel „Hautfarbe braun“. |
| Haut „middleage_african_female“ | Haut von Nebet (etwas aufgehellt und wärmer) | MakeHuman-Team | wie oben | CC0 | Braune Haut ohne Tätowierung oder Schmuck. |
| Haut „old_african_male“ | Haut von Idu (älterer Mann, Falten) | MakeHuman-Team | wie oben | CC0 | Braune, faltige Haut ohne Schmuck. |
| Haar „short02“ | kurzes Haar von Kai (dunkel) und Idu (dunkel mit grauen Strähnen) | MakeHuman-Team | wie oben | CC0 | Kurzes, ungeordnetes Haar ohne Frisurmode der Neuzeit; umgefärbt. |
| Haar „long01“ | Nebets Haar, auf Schulterlänge gerade abgeschnitten | MakeHuman-Team | wie oben | CC0 | Glattes Haar mit Mittelscheitel; gekürzt entspricht es Frauendarstellungen des Alten Reichs. |
| Brauen „eyebrow001“, „eyebrow006“, „eyebrow010“, Augen „low-poly“/„brown“ | Gesichter | MakeHuman-Team | wie oben | CC0 | Natürliche Brauen und braune Augen; zeitlos. |


Die Zeitdrohne („Heute wissen wir“) ist selbst gezeichnet (SVG in `src/drohne.ts`). Epochenprüfung: bewusst ein Gerät
der Gegenwart, das nur am Bildrand erscheint und nie im Dorf; es steht für die Ebene „Heute wissen wir“.

Nicht verwendet: das Zusatzpaket „faceunits01“ (Gesichtsformen), weil auf seiner Seite keine Lizenz angegeben ist.
Das Blinzeln ist selbst gebaut.

## Texturen und Himmel

| Titel | Verwendung | Urheber | Link | Lizenz | Epochenprüfung |
|---|---|---|---|---|---|
| Quarry 01 (Pure Sky) | Himmel (HDRI) | Jarod Guest, Sergej Majboroda | https://polyhaven.com/a/quarry_01_puresky | CC0 | Reiner Himmel ohne Landschaft, Bauwerke oder Gegenstände; zeitlos. |
| Marble Cliff 03 | Fels der fernen Wüstenhänge | Amal Kumar | https://polyhaven.com/a/marble_cliff_03 | CC0 | Natürlicher geschichteter Fels, nur als Oberfläche; zeitlos. |
| Sand 01 | Boden: Wüstensand (einziger rot-gelber Boden) | Rob Tuytel | https://polyhaven.com/a/sand_01 | CC0 | Natürlicher, festgetretener Sand; keine Spuren von Rädern oder Gegenständen. |
| Mud Cracked Dry Riverbed 002 | Boden: rissiger Schlamm in Senken, am Kanal und am Ufer, graubraun umgefärbt | Poly Haven | https://polyhaven.com/a/mud_cracked_dry_riverbed_002 | CC0 | Rissiger, getrockneter Flussschlamm ohne Spuren oder Gegenstände; zeitlos. |
| Dry Mud Field 001 | Boden: festgetretene, staubige Erde (Hof, Wege, Dämme), graubraun umgefärbt | Rico Cilliers, Rob Tuytel | https://polyhaven.com/a/dry_mud_field_001 | CC0 | Trockene, festgetretene Erde. Die Beschreibung nennt „subtle track marks“; in der verwendeten Kachelgröße sind keine Rad- oder Reifenspuren erkennbar. |
| Farm Soil | Boden: Ackerboden im Feld; auch Grundlage der selbst gemalten Stoppeltextur | Amal Kumar | https://polyhaven.com/a/farm_soil | CC0 | Krümelige, dunkle Erde wie Nilschlamm auf dem Feld; zeitlos. |

## Selbst erzeugt

Die Nil-Tamariske ist aus selbst gezeichneten Zweigkarten gebaut (`tools/kulisse_texturen.py`, ersetzt das frühere
Modell „French tamarisk“ von PlantCatalog), ebenso die fernen Getreidefelder (Feldseite, Feldoberseite).
Papyrus (dreikantiger, blattloser Stängel mit Dolde) und Schilfrohr (Halme, Blätter, Rispe) sind in Blender
nachgebildet und auf Blattkarten gerendert, weil auf Sketchfab und Poly Haven kein passendes Modell zu finden war
(`blender/scripts/pflanzen_karten.py`). Alle übrigen Modelle und Texturen entstehen per Skript in diesem Projekt
(`blender/scripts/build_scene.py`, `blender/scripts/pflanzen.py`, `tools/make_textures.py`,
`tools/requisiten_texturen.py`: Ton, Garbenhalme, Ähren, Papyrusbündel des Boots, Seil, Fischernetz).
