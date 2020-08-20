# KSP Tweaks
A bunch of small/medium ModuleManager patches to various mods I use in KSP, to make them fit more or be slightly more useful with other mods.

# Recommend Dependency Mods (at least one or you won't see any differences!)
- B9PartSwitch
- WildBlueTools

# Cargo Switchers for B9
Parenthesis indicates the mod required for the cargo type to be available
CRP is Community Resource Pack
EPL is Extra-planetary Launchpads
MKS is Modular Kolony Systems
WBT is WildBlueTools

- Structural
- Ore
- (TAC-LS) Life Support - Oxygen, Water, Food
- (Snacks) Snacks
- (Snacks) Soil
- (USI-LS) Supplies
- (CRP) Metallic Ore
- (CRP) Uranite
- (CRP) Substrate
- (CRP) Minerals
- (MKS) Commodities
- (CRP) Exotic Minerals [Unavailable if MKS also installed]
- (CRP) Rare Metals [Unavailable if MKS also installed]
- (CRP) Material Kits
- (MKS) Metals
- (MKS) Polymers
- (MKS or GroundConstruction) Machinery
- (MKS) Recyclable
- (MKS or GroundConstruction) Specialised Parts
- (CRP) Fetilizer
- (MKS or TAC-LS) Hydrates
- (MKS) Gypsum
- (MKS) Dirt
- (MKS) Silicates
- (MKS) Silicon
- (MKS) Refined Exotics
- (MKS) Colony Supplies
- (MKS) Organics
- (CRP) Rock
- (EPL) Metal [Unavailable if MKS also installed]
- (EPL) Metal Ore [Unavailable if MKS also installed]
- (EPL) Rocket Parts [Unavailable if MKS also installed]
- (EPL) Scrap Metal [Unavailable if MKS or Simple Construction also installed]
- (TAC-LS) Food
- (TAC-LS) Water
- (TAC-LS) Oxygen
- (CRP) Lead
- (WBT) Research Kits
- (WBT) Equipment

# Delivery - Beale (https://spacedock.info/mod/2430/Special%20Delivery%20-%20Stockalike%20Cygnus)
A stock-alike Cygnus mod

## Changes
- Increase the BT-4 engines thrust to 20kN to make it comparable to the ATV in Knes
- Add two variants of the Fuselage
  - Variant using WildBlueTools' OmniStorage
  - Variant using B9PartSwitch Cargo switches loosely based around the SSPXR (Space Station Parts Expansion Redux) configs
  - Slightly different colour variants on the fuselage
  
# Tantares - Beale (https://spacedock.info/mod/174/Tantares%20-%20Stockalike%20Soyuz%20and%20MIR)
A stock-alike Russian parts mod covering capsules and stations

## Changes
- (WIP) Add USI-LS to capsules, so far just the Soyuz capsule parts are covered with a maximum of 90 days of supplies
- Add 1 day of electricity to the Crew Section for each kerbal*
- (WIP) Add variants of the Soyuz Orbital Module that can carry more cargo than the default KIS inventory (B9 and WBT variants)
- (WIP) Add variants of the Hamal Forward Section that can carry both B9PartSwitch and WBT cargo loadouts
- Add extra monopropellant to the Service Modules (*2) and add a MP Fuel Cell for power when using the 7K-T which historically ran on battery power alone. The 120 extra gives you about 3.5 hours of total run time
- 

* this also fixes a general issue with the Soyuz in that it only has about 50EC in total across the vehicle..

# TantaresLV - Beale (https://spacedock.info/mod/176/TantaresLV%20-%20Stockalike%20Launch%20Vehicles)
A stock-alike Russian parts mod covering launch vehicles

## Changes
- Give at least the Soyuz launcher engines Alternators so your rocket doesn't run out of EC on the way up

# KNES - Well (https://spacedock.info/mod/1470/Knes)
A stock-alike French/European parts mod

## Changes
- Lets the following parts use WBT's OmniStorage
  - ATV 'Almadi' Pressurised Module
  - Small 'MiraGino' Pressurised Module
  - Multi-Role Cargo Kapsule DM
  - Multi-Role Kapsule DM
- Lets the 'Steam "Blamont" Fuel Module' carry more types of fuels than just MP.
- Create a variant of the MiraGino PCM carry cargo via B9PartSwitch
- Create a variant of the MiraGino PCM able to carry switchable fuels like the Blamont
