# Abbreviation Table

| Abbreviation | Meaning                |
| ------------ | ---------------------- |
| EBF          | Electric Blast Furnace |
| H            | Hydrogen               |
| Cl           | Chlorine               |
| HCl          | Hydrochloric Acid      |
| Al           | Aluminum               |
| Cu           | Copper                 |
| Fe           | Iron                   |
| Ni           | Nickel                 |
| Mn           | Manganese              |
| Sn           | Tin                    |
| Pb           | Lead                   |
| Ti           | Titanium               |
| W            | Tungsten               |

# Rubber Sheet

1. Coal Bee -> Coal
2. Coal -> Coal Dust
3. Coal Dust in _Coke Oven_ -> Coke Dust + (500mB) Creosote (50% chance)
   - Replace Coke Oven with Pyrolyse Oven
4. Coke Dust + (100mB) Water in _Mixer_ -> (200mB) Raw Synthetic Oil
5. (100mB) Raw Synthetic Oil in _Steam Blast Furnace_ -> (100mB) Synthetic Oil
   - Replace Steam Blast Furnace with EBF
6. (100mB) Synthetic Oil + Paper in _Mixer_ -> (2) Rubber Sheet

# Hydrochloric Acid (HCl)

1. Salty Bee -> Salt
2. (2) Salt in _Electrolyzer_ -> Sodium Dust + (125mB) Chlorine
3. (3000mB) Water in _Electrolyzer_ -> (2000mB) Hydrogen and (1000mB) Oxygen
4. (1000mB) Hydrogen + (1000mB) Chlorine in _Chemical Reactor_ -> (2000mB) Hydrochloric Acid

# Soldering Alloy

1. Sn Dust + Pb Dust in _Mixer_ -> (2) Soldering Alloy Dust
2. Soldering Alloy Dust in _EBF_ -> (90mB) Soldering Alloy

# Chromium

Hard Way

1. RuBee -> Ruby
2. Ruby -> Ruby dust
3. (6) Ruby Dust in _Centrifuge_ -> Chromium Crushed Dust + (2) Al Dust
4. Chromium Crushed Dust + 9000mB HCl in _Chemical Reactor_ -> (9000mB) Chromium Hydrochloric Solution
5. (1000mB) Chromium Hydrochloric Solution in _Electrolyzer_ -> (3) Chromium Tiny Dust + (450mB) H + (450mB) Cl
6. (9) Chromium Tiny Dust in _Crafting Table (or Packer)_ -> Chromium Dust
7. Chromium Dust in _EBF (Cupronickel Tier)_ -> Chromium Hot Ingot
8. Chromium Hot Ingot in _Vacuum Freezer_ -> Chromium Ingot
   - Heat Exchanger can also be used if you have access to Cryofluid somehow

Easy Way (need to do hard way first for the feeding block -- Chromium Block)

1. (6) RuBee Spawn Egg in _Centrifuge_ -> Chromium Bee Spawn Egg

After getting Chromium automated via Bees, stop processing Ruby Dust (into Chromium Crushed Dust). HCl is used later on, no need to waste it here.

# Manganese

Hard Way

1. (6) Raw Fe in _Centrifuge_ -> (8) Fe Dust + Mn Crushed Dust
2. (200mB) Oxygen + (200mB) Water + Sulfur in _Chemical Reactor_ -> (500mB) Sulfuric Acid
3. (9000mB) Sulfuric Acid + Mn Crushed Dust in _Chemical Reactor_ -> (9000mB) Mn Sulfuric Solution
4. (1000mB) Mn Sulfuric Solution in _Electrolyzer_ -> (900mB) Sulfuric Acid + (3) Mn Tiny Dust

Easy Way (need to do hard way first for the feeding block -- Mn Dust)

1. (6) Fe Spawn Egg in _Centrifuge_ -> Manganese Bee Spawn Egg

After getting the bee, stop producing Mn.

# Stainless Steel

1. (6) Fe Dust + Chromium Dust + Ni Dust + Mn Dust in _Mixer_ -> (9) Stainless Steel Dust

# Kanthal

1. Stainless Steel Dust + Al Dust + Chromium Dust in _Mixer_ -> (3) Kanthal Dust

# Annealed Copper

1. Cu Dust + (250mB) Oxygen in _EBF (Kanthal Tier)_ -> Annealed Cu Hot Ingot
2. Annealed Cu Hot Ingot in _Vacuum Freezer_ -> Annealed Cu Ingot

# Titanium

Titanium is able to be mined using the _Electric Quarry + Stainless Steel Drill_ but this is quite slow. Since we are playing ATM10, we can use an alternate method via Mekanism to acquire Ti.

1. Flint or (200mB) Oxygen + Raw Al in _Purification Chamber (Mekanism)_ -> (2) Al Clump
2. Al Clump in _Crusher (Mekanism)_ -> (2) Dirty Al Clump
3. (10) Al Clump in _Electrolyzer_ -> (4) Al Dust + (3) Tiny Ti Dust + (2000mB) Oxygen
4. (9) Tiny Ti Dust -> Ti Dust
5. Ti Dust in _EBF (Kanthal Tier)_ -> Ti Hot Ingot
6. Ti Hot Ingot in _Vacuum Freezer_ -> Ti Ingot

There is a Titanium Bee that is made from breeding a Diamond Bee with an Iron Bee. You can now use that bee for titanium. It is not _as_ important to use the bee instead of the production line here, unlike Chromium and Manganese.

# Tungsten

1. Raw W in _Macerator_ -> W Dust (50% chance for double)
2. W Dust in _Unpacker_ -> (9) W Tiny Dust
3. W Tiny Dust in _Electric Compressor_ -> W Nugget
4. (9) W Nugget -> W Ingot

_Immersive Engineering's Arc Furnace_ can smelt W Dust to W Ingots directly (requires progressing pretty much all the way through I.E.).
