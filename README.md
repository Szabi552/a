# Budgie Parrot Pack (MC 1.21.11)

Resource pack, ami a vanilla papagáj-textúrákat hullámos papagájra
(budgie / budgerigar) jellemző színekre és mintázatra cseréli — beleértve
a jellegzetes fekete "hullám" csíkozást a fejtetőn és a szárnyakon, amit a
vanilla textúra eredetileg nem tartalmazott (ezt hozzá rajzoltam). A modell
geometriája/UV-térképe változatlan, 100%-ban kompatibilis a vanilla
papagáj-modellel, nincs szükség semmilyen modra hozzá.

## Melyik variáns mit ábrázol

| Vanilla variáns neve | Budgie színmutáció |
|---|---|
| `parrot_green` | Világoszöld (wild-type) budgie, sárga arcmaszkkal |
| `parrot_blue` | Égkék budgie, fehér arcmaszkkal |
| `parrot_yellow_blue` | Lila (violet) budgie, fehér arcmaszkkal |
| `parrot_grey` | Szürke budgie, fehér-szürke arcmaszkkal |
| `parrot_red_blue` | Albínó budgie — sima fehér, csíkozás nélkül, apró piros szemfolttal |

## Telepítés

1. Nyisd meg a Minecraft/Modrinth App profilod `resourcepacks` mappáját
   (Modrinth App-ban: profil → ... menü → "Open resource packs folder",
   vagy sima launcherben: `.minecraft/resourcepacks`)
2. Másold ide az egész `Budgie-Parrot-Pack` mappát (vagy tömörítve .zip-ként)
3. Játékban: Beállítások → Resource Packs → aktiváld
4. Kész — minden papagáj az új, budgie-szerű mintázattal fog kirajzolódni

## Megjegyzés

A geometria nem változott, csak a textúra — ha más resource pack is felülírja
a `textures/entity/parrot/` mappát, ütközés lehet; ilyenkor tedd ezt a
listában feljebb (magasabb prioritásra).
