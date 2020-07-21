Ships are collections of Sections, with built in Components and added on Equipment. Each Section is roughly 10'x10'x6' in size. Multiple sections of the same size can be grouped together to form a single large section at a additional cost of 10%(additive) per additional section. This makes an area capable of housing larger components, grants it a greater HP pool and allows crew to transverse it quicker, but also it will make them more likely to be struck in combat.



| Name | Role | Price| Description |
| -- | -- | -- | -- | -- |
| Decking | General section| 40 gp | A general use, unenclosed empty space |
| Row bench | Decking or Gallery | 10gp | Oars and fittings for adding rowing speed to a ship. Allows 2 rowers. |
| Railing | Decking | 10 gp | 3' high railing. Provideds 1/2 cover for Medium or 3/4ths cover for Small characters. Helps prevent accidents.| 
| Mast | Decking | 1000 gp | Riggings, sails and mast for capturing wind. Once set contributes to speed until wind changes. |
| Weapons Bay | Dedicated area for siege weapons and ammunition | gp | Weapons in a Weapons Bay reduce Load DC by 5 |
| Ballista | Weapon or Decking | 500gp | 3d10 + firing member's modifier, Load count 1. Cost includes maintence gear, ammunition, basic tools, etc. |
| Brig | Dedicated area for holding captives | gp | For rowdy crewmates or prisoner transport |
| Cargo | Dedicated area for transporting goods | gp | The cargo will likely stay dry |
| Bow | Front of the ship | gp | A pointed, wave breaking ship front |
| Stern | Rear of the ship | gp | A flat, reinforced ship back |
| Gallery | Dedicated area for oars-men | gp | Enclosed area set aside for row benches, drums and sometimes shackels. |
| Workshop | Dedicated area for tools and crafts | gp | If you can't carry it then maybe you can carry the means to make it. |
| Quarters | Dedicated area for housing | 75 gp | Enclosed area set aside for housing |
| Modest Accomodations | Quarters | 200 gp | A single bed (1-2 people), locker with DC 20 lock, and some surface that can be used to write and eat on. Space inefficient but comfortable. |

```yaml
reference:
  Rowboat (10x5, 50gp):
    Deck 40gp:
      Rowbench 10gp

  Keelboat (60x20, 3000gp):
    Deck x 10 400*(1+.1*10) 800gp:
      Ballista 500gp
      Mast & rigging 1000gp
      Rowbench x 6 60gp
      Railing x 10 100gp
    Quarters x 2 165gp:
      Modest accomodations x 2 400gp
```