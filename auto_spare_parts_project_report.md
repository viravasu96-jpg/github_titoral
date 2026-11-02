# Auto Spare Shop Parts & Materials Project Documentation

> **Project Designation**: Enterprise Automotive Spare Parts, Metallurgy & Quality Management System  
> **Generated Date**: 2026-11-02 13:00:26  
> **Engineering Focus**: Multi-Brand Vehicle Compatibility (Maruti Suzuki, Mahindra, Tata, Hyundai)  
> **Inventory Scope**: 40 Core SKUs Across 8 Automotive Subsystems  

---

## 1. Executive Project Summary & KPI Dashboard

This project provides an end-to-end operational, metallurgical, and inventory control framework for an automotive spare parts and workshop facility. It integrates OEM part cross-referencing, mechanical material properties, bill of materials (BOM), tier-1 supplier evaluation, and warranty failure analysis.

| Macro Metric | Verified Project Metric Value | Operational Significance |
| :--- | :--- | :--- |
| **Total Cataloged SKUs** | **40 Active SKUs** | Complete coverage across powertrain, chassis & electrical |
| **Total Physical Stock** | **5,180 Units** | Active workshop buffer stock |
| **Total Inventory Valuation** | **₹6,689,750.00** | Capital allocation in verified high-turnover spares |
| **Average Gross Margin** | **38.6%** | Robust dealership parts markup |
| **Critical Reorder Items** | **0 SKUs Alerted** | Threshold triggered for automated purchase requisition |

### Automotive Subsystems & Valuation Distribution

| Automotive Subsystem | Active SKUs | Total Stock (Units) | Inventory Valuation (₹) | Avg Gross Margin (%) | Status |
| :--- | :---: | :---: | :---: | :---: | :---: |
| Engine & Powertrain | 6 | 710 | ₹1,192,650.00 | 36.5% | `ACTIVE` |
| Braking & Friction | 5 | 850 | ₹1,010,750.00 | 38.3% | `ACTIVE` |
| Transmission & Clutch | 5 | 430 | ₹922,200.00 | 36.7% | `ACTIVE` |
| Suspension & Steering | 5 | 520 | ₹712,650.00 | 39.1% | `ACTIVE` |
| Electrical & Electronics | 5 | 640 | ₹1,040,500.00 | 37.3% | `ACTIVE` |
| Cooling & Climate | 5 | 580 | ₹707,000.00 | 39.4% | `ACTIVE` |
| Exhaust & Emissions | 4 | 290 | ₹893,000.00 | 35.9% | `ACTIVE` |
| Fasteners & Hardware | 5 | 1,160 | ₹211,000.00 | 45.6% | `ACTIVE` |

---

## 2. Master Parts & Materials Inventory Catalog

The following catalog specifies all component parts, mechanical material classes, vehicle application cross-references, OEM part codes, and stock valuation:

| Part ID | Component Description | Subsystem | Material Grade / Spec | Vehicle Compatibility | OEM Part No. | Cost (₹) | Retail (₹) | Margin (%) | Stock | Status |
| :---: | :--- | :--- | :--- | :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| `ENG-101` | Cylinder Liner / Sleeve | Engine & Powertrain | Centrifugally Cast Gray Iron G250 | Maruti Swift / Dzire 1.2L K12N | `MS-11211M79M00` | ₹1,450 | ₹2,200 | 34.1% | 120 | `HEALTHY` |
| `ENG-102` | Piston Assembly w/ Rings | Engine & Powertrain | High-Silicon Forged Aluminum 4032-T6 | Mahindra Scorpio-N / Thar 2.2L mHawk | `MM-0303BC0021N` | ₹3,200 | ₹4,800 | 33.3% | 85 | `HEALTHY` |
| `ENG-103` | Crankshaft Journal Bearing Set | Engine & Powertrain | Tri-Metal (Steel Back + Cu-Pb-Sn Alloy) | Tata Nexon / Altroz 1.2L Revotron | `TAT-287103100109` | ₹1,850 | ₹2,950 | 37.3% | 90 | `HEALTHY` |
| `ENG-104` | Exhaust Valve (Stellite Faced) | Engine & Powertrain | Austenitic Stainless Steel 21-4N (EV8) | Hyundai Creta / Seltos 1.5L CRDi | `HYU-22212-2A100` | ₹480 | ₹780 | 38.5% | 180 | `HEALTHY` |
| `ENG-105` | Cylinder Head Gasket (MLS) | Engine & Powertrain | Multi-Layer Full-Hard Stainless 301 w/ FKM | Maruti Brezza / Grand Vitara 1.5L | `MS-11141M68K00` | ₹1,250 | ₹2,100 | 40.5% | 110 | `HEALTHY` |
| `ENG-106` | Timing Chain & Tensioner Kit | Engine & Powertrain | Alloy Steel Link Plates w/ Nitrided Pins | Mahindra XUV700 2.0L mStallion | `MM-0305DA0110N` | ₹2,850 | ₹4,400 | 35.2% | 125 | `HEALTHY` |
| `BRK-201` | Front Ventilated Brake Rotor | Braking & Friction | High-Carbon Gray Cast Iron SAE J431 G3000 | Maruti Swift / Baleno / Fronx | `MS-55311M68K00` | ₹1,650 | ₹2,600 | 36.5% | 140 | `HEALTHY` |
| `BRK-202` | Ceramic Brake Pad Set (Front) | Braking & Friction | Copper-Free Ceramic-Aramid Composite | Hyundai Creta / Kia Seltos 1.5L | `HYU-58101-1RA00` | ₹1,150 | ₹1,950 | 41.0% | 220 | `HEALTHY` |
| `BRK-203` | Rear Brake Drum | Braking & Friction | Gray Cast Iron ASTM A48 Class 30 | Tata Punch / Tiago 1.2L | `TAT-287042300104` | ₹1,350 | ₹2,150 | 37.2% | 110 | `HEALTHY` |
| `BRK-204` | Brake Master Cylinder Assembly | Braking & Friction | Anodized Cast Aluminum Alloy ADC12 | Mahindra Scorpio-Classic / Bolero | `MM-0603CA0141N` | ₹2,400 | ₹3,750 | 36.0% | 75 | `HEALTHY` |
| `BRK-205` | Hydraulic Brake Caliper Piston | Braking & Friction | Phenolic Resin Composite / Chrome Steel | Maruti Ertiga / XL6 1.5L | `MS-55101M79M00` | ₹650 | ₹1,100 | 40.9% | 305 | `HEALTHY` |
| `TRN-301` | Clutch Friction Plate (Disc) | Transmission & Clutch | Organic Friction Lining on C45 Spring Steel | Maruti Swift / Dzire Diesel & Petrol | `MS-22400M79M00` | ₹1,750 | ₹2,750 | 36.4% | 130 | `HEALTHY` |
| `TRN-302` | Clutch Pressure Plate Cover | Transmission & Clutch | Ductile Nodular Iron GGG-50 w/ Diaphragm | Mahindra Scorpio-N / Thar CRDe | `MM-0306AA0220N` | ₹2,600 | ₹4,100 | 36.6% | 90 | `HEALTHY` |
| `TRN-303` | Synchronizer Ring (3rd/4th) | Transmission & Clutch | High-Tensile Die-Cast Forged Brass CuZn40Al2 | Tata Nexon 6-Speed Manual | `TAT-287226200108` | ₹820 | ₹1,350 | 39.3% | 110 | `HEALTHY` |
| `TRN-304` | Transmission Input Shaft Gear | Transmission & Clutch | Case-Hardening Steel 16MnCr5 (Carburized) | Hyundai i20 / Venue 1.2L Kappa | `HYU-43221-02500` | ₹3,100 | ₹4,850 | 36.1% | 45 | `HEALTHY` |
| `TRN-305` | Dual-Mass Flywheel Ring Gear | Transmission & Clutch | Induction-Hardened Forged Carbon Steel 1045 | Mahindra XUV700 Diesel AT/MT | `MM-0306AA0510N` | ₹4,200 | ₹6,500 | 35.4% | 55 | `HEALTHY` |
| `SUS-401` | Front MacPherson Strut Damper | Suspension & Steering | Cold-Drawn Seamless Tube St52 w/ Chrome | Maruti Swift / Baleno (All Gens) | `MS-41601M68K00` | ₹2,150 | ₹3,400 | 36.8% | 115 | `HEALTHY` |
| `SUS-402` | Helical Coil Suspension Spring | Suspension & Steering | High-Stress Silicon-Chromium Steel 55Cr3 | Tata Harrier / Safari Kryotec | `TAT-287332100101` | ₹1,450 | ₹2,350 | 38.3% | 100 | `HEALTHY` |
| `SUS-403` | Lower Control Arm w/ Bushings | Suspension & Steering | Stamped High-Strength Low-Alloy Steel (HSLA) | Hyundai Creta / Kia Seltos 2020+ | `HYU-54500-1R000` | ₹2,650 | ₹4,200 | 36.9% | 80 | `HEALTHY` |
| `SUS-404` | Steering Tie Rod End (Ball Joint) | Suspension & Steering | Forged Carbon Steel 40Cr w/ POM Ball Seat | Maruti Ertiga / Dzire / Brezza | `MS-48810M68K00` | ₹580 | ₹950 | 38.9% | 140 | `HEALTHY` |
| `SUS-405` | Anti-Roll Sway Bar Bushing Kit | Suspension & Steering | High-Durometer Natural Rubber w/ EPDM | Mahindra Scorpio / Bolero Neo | `MM-0401AA0100N` | ₹320 | ₹580 | 44.8% | 85 | `HEALTHY` |
| `ELE-501` | Starter Motor Armature Assembly | Electrical & Electronics | Electrolytic Tough Pitch (ETP) Copper C11000 | Maruti K-Series & DDiS Engines | `MS-31100M68K00` | ₹1,950 | ₹3,100 | 37.1% | 120 | `HEALTHY` |
| `ELE-502` | Alternator Rotor w/ Slip Rings | Electrical & Electronics | Low-Carbon Steel St37 w/ Solid Copper Wire | Mahindra mHawk 2.2L All Variants | `MM-0308AA0190N` | ₹2,400 | ₹3,800 | 36.8% | 80 | `HEALTHY` |
| `ELE-503` | Electronic Throttle Body Actuator | Electrical & Electronics | Die-Cast Aluminum ADC12 w/ NdFeB Magnet | Tata Nexon / Altroz Revotron | `TAT-287415100102` | ₹3,400 | ₹5,200 | 34.6% | 60 | `HEALTHY` |
| `ELE-504` | Iridium Spark Plug (Set of 4) | Electrical & Electronics | Laser-Welded Iridium Tip w/ High Alumina | Maruti K12 / K15 DualJet Engines | `MS-09482M00605` | ₹1,200 | ₹1,950 | 38.5% | 250 | `HEALTHY` |
| `ELE-505` | Camshaft Position Hall Sensor | Electrical & Electronics | Overmolded Glass-Filled PBT w/ SmCo Core | Hyundai 1.5L U2 CRDi & MPI | `HYU-39350-2A400` | ₹850 | ₹1,400 | 39.3% | 130 | `HEALTHY` |
| `THM-601` | Engine Radiator Core Assembly | Cooling & Climate | Furnace-Brazed Aluminum Alloy 3003-H14 | Maruti Swift / Baleno / WagonR | `MS-17700M68K00` | ₹2,450 | ₹3,900 | 37.2% | 95 | `HEALTHY` |
| `THM-602` | Centrifugal Water Pump Assembly | Cooling & Climate | Die-Cast Aluminum ADC12 w/ SiC Mechanical Seal | Mahindra Scorpio-N / Thar 2.2L | `MM-0304AA0210N` | ₹1,650 | ₹2,650 | 37.7% | 110 | `HEALTHY` |
| `THM-603` | Thermostat Valve w/ Housing | Cooling & Climate | Cartridge Brass CuZn30 w/ Wax Pellet | Tata Nexon / Safari 2.0L Diesel | `TAT-287120100103` | ₹620 | ₹1,050 | 41.0% | 140 | `HEALTHY` |
| `THM-604` | Engine Cooling Fan Motor (BLDC) | Cooling & Climate | PA66 30% Glass-Filled Blades w/ Copper Rotor | Hyundai Creta / Venue / i20 | `HYU-25380-1R050` | ₹1,850 | ₹2,950 | 37.3% | 75 | `HEALTHY` |
| `THM-605` | Radiator Inlet/Outlet Hose Set | Cooling & Climate | Peroxide-Cured EPDM Rubber w/ Aramid Braid | Maruti Ertiga / Ciaz 1.5L | `MS-17851M79M00` | ₹420 | ₹750 | 44.0% | 160 | `HEALTHY` |
| `EXH-701` | Exhaust Header Manifold | Exhaust & Emissions | Ferritic Heat-Resistant Stainless Steel SUS409 | Maruti K15C Smart Hybrid | `MS-14110M79M00` | ₹3,800 | ₹5,800 | 34.5% | 45 | `HEALTHY` |
| `EXH-702` | Catalytic Converter Monolith | Exhaust & Emissions | Extruded Cordierite Honeycomb w/ Pt-Pd-Rh | Mahindra Thar / Scorpio Diesel BS6 | `MM-0307AA0120N` | ₹8,500 | ₹12,800 | 33.6% | 35 | `HEALTHY` |
| `EXH-703` | Front Exhaust Flexible Bellows | Exhaust & Emissions | Double-Braid Austenitic Stainless Steel 304 | Tata Nexon / Tiago Revotron | `TAT-287549100101` | ₹1,250 | ₹2,050 | 39.0% | 90 | `HEALTHY` |
| `EXH-704` | Rear Muffler Exhaust Silencer | Exhaust & Emissions | Aluminized Carbon Steel Sheet DX53D+AS120 | Hyundai Creta 1.5L Petrol | `HYU-28700-1R000` | ₹2,600 | ₹4,100 | 36.6% | 120 | `HEALTHY` |
| `FST-801` | Cylinder Head Bolt Set (M10) | Fasteners & Hardware | Quenched & Tempered Cr-Mo Steel Grade 10.9 | Maruti K-Series Engines | `MS-09103M10214` | ₹450 | ₹780 | 42.3% | 210 | `HEALTHY` |
| `FST-802` | Wheel Lug Stud & Nut (M12x1.25) | Fasteners & Hardware | High-Tensile Cold-Forged Steel Grade 10.9 | Mahindra Scorpio / Thar / XUV700 | `MM-0403AA0020N` | ₹120 | ₹220 | 45.5% | 350 | `HEALTHY` |
| `FST-803` | Connecting Rod Bolt (Fatigue Res) | Fasteners & Hardware | Vacuum-Degassed Alloy Steel 42CrMo4 | Tata 2.0L Kryotec Diesel | `TAT-287103200105` | ₹280 | ₹490 | 42.9% | 140 | `HEALTHY` |
| `FST-804` | Oil Sump Drain Plug w/ Cu Washer | Fasteners & Hardware | Zinc-Nickel Plated Carbon Steel Class 8.8 | Universal Fit (M14x1.5) | `UN-09247M14019` | ₹65 | ₹130 | 50.0% | 280 | `HEALTHY` |
| `FST-805` | Brake Caliper Mounting Bolt M12 | Fasteners & Hardware | Grade 12.9 High-Strength Alloy Steel w/ Geomet | Hyundai / Kia All Models | `HYU-11244-12356B` | ₹95 | ₹180 | 47.2% | 180 | `HEALTHY` |

---

## 3. Engineering Materials & Metallurgical Specifications

Automotive component longevity depends strictly on metallurgical characteristics. The table below outlines international standard grades, mechanical properties, thermal limits, and workshop preservation practices:

| Material ID | Material Family Name | International Standard | Tensile (MPa) | Yield (MPa) | Hardness Rating | Max Temp (°C) | Workshop Storage & Handling Rules |
| :---: | :--- | :--- | :---: | :---: | :--- | :---: | :--- |
| `MAT-01` | **Gray Cast Iron (G250/G3000)** | `SAE J431 / ASTM A48 Class 35` | 250 | 165 | 187 - 241 HBW | 450°C | VCI paper wrapping; keep humidity < 50% RH |
| `MAT-02` | **Forged High-Silicon Aluminum 4032** | `ASTM B247 / EN AW-4032` | 380 | 315 | 120 - 140 HBW | 300°C | Store on wooden racks; avoid chemical fumes |
| `MAT-03` | **Die-Cast Aluminum Alloy ADC12** | `JIS H5302 / ASTM A383.0` | 310 | 160 | 80 - 95 HBW | 200°C | Dry covered storage; prevent moisture condensation |
| `MAT-04` | **Case-Hardening Alloy Steel 16MnCr5** | `DIN EN 10084 / ISO 683-3` | 1,000 | 750 | 58 - 62 HRC (Case) | 250°C | Dip in light rust-preventive oil; seal in PE film |
| `MAT-05` | **Chrome-Molybdenum Steel 42CrMo4** | `DIN EN 10083-3 / AISI 4140` | 1,100 | 900 | 28 - 34 HRC | 400°C | Corrosion inhibitor coating; avoid direct ground |
| `MAT-06` | **Spring Steel 55Cr3 (SUP9)** | `DIN EN 10089 / JIS G4801` | 1,450 | 1,250 | 42 - 48 HRC | 220°C | Inspect shot-peened surface; keep dry and boxed |
| `MAT-07` | **Austenitic Stainless Steel 21-4N** | `SAE J775 / ASTM A565 EV8` | 1,050 | 680 | 32 - 38 HRC | 850°C | Store in clean containers away from carbon steel |
| `MAT-08` | **Ferritic Stainless Steel SUS409** | `ASTM A240 / EN 1.4512` | 450 | 250 | 75 - 85 HRB | 650°C | Dry indoor racking; protect flanges from denting |
| `MAT-09` | **Electrolytic Tough Pitch Copper ETP** | `ASTM B152 / UNS C11000` | 240 | 70 | 45 - 55 HRB | 150°C | Air-tight desiccant pouches; prevent tarnishing |
| `MAT-10` | **Ceramic Friction Composite** | `Proprietary NAO Formulation` | 45 | 30 | 65 - 80 HRE | 650°C | Keep away from grease/fluids; handle with gloves |
| `MAT-11` | **Ethylene Propylene Diene (EPDM)** | `ASTM D2000 M3BA714` | 14 | 10 | 65 - 75 Shore A | 140°C | Store away from electric motors (ozone); <25°C |
| `MAT-12` | **Grade 10.9 Fastener Alloy Steel** | `ISO 898-1 Class 10.9` | 1,040 | 940 | 32 - 39 HRC | 300°C | Pre-lubricated w/ phosphate/oil; keep unopened |

---

## 4. Multi-Level Sub-Assembly Bill of Materials (BOM)

Hierarchical breakdown of complex assemblies into individual mechanical sub-components with manufacturing processes, unit masses, and quality inspection standards:

| Assembly ID | Assembly Description | Sub-Component Item | Material Specification | Manufacturing Process | Qty | Unit Mass (kg) | Total Mass (kg) | Criticality |
| :---: | :--- | :--- | :--- | :--- | :---: | :---: | :---: | :---: |
| `ASM-01` | Front Ventilated Disc Brake Assembly | Ventilated Brake Disc Rotor | Gray Cast Iron SAE J431 G3000 | Sand Casting + CNC Turning | 2 | 6.850 | 13.700 | `HIGH` |
| `ASM-01` | Front Ventilated Disc Brake Assembly | Single-Piston Floating Caliper Body | Ductile Iron GGG-40 | Gravity Die Casting + Machining | 2 | 3.420 | 6.840 | `HIGH` |
| `ASM-01` | Front Ventilated Disc Brake Assembly | Ceramic Friction Brake Pads | Copper-Free NAO Composite | Hot Press Sintering | 4 | 0.420 | 1.680 | `HIGH` |
| `ASM-02` | Cylinder Head & Valvetrain Assembly | Aluminum Cylinder Head Casting | Al-Si-Cu Alloy A356-T6 | Low-Pressure Die Casting (LPDC) | 1 | 14.500 | 14.500 | `HIGH` |
| `ASM-02` | Cylinder Head & Valvetrain Assembly | Dual Overhead Camshafts (DOHC) | Chilled Cast Iron Grade G350 | Chilled Sand Casting + Cam Grind | 2 | 2.950 | 5.900 | `HIGH` |
| `ASM-03` | Manual Clutch & Driveline Module | Diaphragm Spring Clutch Cover | Carbon Steel C67S w/ Nodular Ring | Progressive Stamping + Heat Treat | 1 | 4.850 | 4.850 | `HIGH` |
| `ASM-03` | Manual Clutch & Driveline Module | Clutch Driven Friction Plate | Aramid-Copper Yarn on C45 Plate | Resin Impregnation + Riveting | 1 | 1.450 | 1.450 | `HIGH` |
| `ASM-04` | Front MacPherson Strut Module | Twin-Tube Damper Cylinder Body | Cold-Drawn Welded Steel St52-3 | Cold Draw + Roll Burnishing | 2 | 4.100 | 8.200 | `HIGH` |
| `ASM-04` | Front MacPherson Strut Module | Variable Pitch Helical Spring | Silicon-Chromium Steel 55Cr3 | Hot Coiling + Shot Peening | 2 | 2.750 | 5.500 | `HIGH` |
| `ASM-05` | Engine Cooling Radiator Module | Brazed Aluminum Tube & Fin Core | Clad Aluminum Alloy 3003/4343 | Controlled Atmosphere Brazing (CAB) | 1 | 3.200 | 3.200 | `HIGH` |
| `ASM-05` | Engine Cooling Radiator Module | Radiator Inlet/Outlet Tank Set | Polyamide PA66 with 30% Glass Bead | Precision Injection Molding | 2 | 0.720 | 1.440 | `HIGH` |

---

## 5. Tier-1 Automotive Sourcing & Supplier Directory

Strategic sourcing matrix evaluating certified Tier-1 manufacturing suppliers on lead times, minimum order quantities (MOQ), and defect parts-per-million (PPM) rates:

| Supplier ID | Supplier Name | Manufacturing Hub | Component Focus | Quality Certifications | Lead Time | MOQ | Defect PPM | Audit Score | Status |
| :---: | :--- | :--- | :--- | :--- | :---: | :---: | :---: | :---: | :---: |
| `SUP-01` | **Bharat Forge Limited** | Pune, Maharashtra | Engine Blocks, Crankshafts, Forged Pistons | `IATF 16949, ISO 9001, ISO 14001` | 14 days | 50 | 42 PPM | 94.5/100 | `APPROVED` |
| `SUP-02` | **Sundram Fasteners Limited** | Chennai, Tamil Nadu | High-Tensile Fasteners, Valve Pins, Rods | `IATF 16949, ISO 45001, VDA 6.3` | 7 days | 100 | 28 PPM | 96.0/100 | `APPROVED` |
| `SUP-03` | **Brakes India Private Limited** | Sholinghur / Chennai, TN | Brake Rotors, Drums, Master Cylinders | `IATF 16949, ISO 14001, OHSAS 18001` | 10 days | 40 | 35 PPM | 93.0/100 | `APPROVED` |
| `SUP-04` | **Endurance Technologies Limited** | Aurangabad, Maharashtra | Clutch Assemblies, Friction Discs, Gaskets | `IATF 16949, ISO 9001, ISO 50001` | 12 days | 35 | 48 PPM | 91.5/100 | `APPROVED` |
| `SUP-05` | **Subros Limited** | Noida, Uttar Pradesh | Radiators, Condensers, Heat Exchangers, EPDM | `IATF 16949, ISO 14001` | 15 days | 30 | 52 PPM | 90.0/100 | `APPROVED` |
| `SUP-06` | **Gabriel India Limited** | Chakan / Pune, Maharashtra | Shock Absorbers, MacPherson Struts, Springs | `IATF 16949, ISO 9001, ISO 14001` | 12 days | 40 | 38 PPM | 92.5/100 | `APPROVED` |
| `SUP-07` | **Lucas-TVS Limited** | Padi, Chennai, Tamil Nadu | Starters, Alternators, ETP Copper Windings | `IATF 16949, Deming Prize, ISO 14001` | 9 days | 25 | 22 PPM | 97.0/100 | `APPROVED` |
| `SUP-08` | **Uno Minda Limited** | Gurugram / Manesar, Haryana | Sensors, Actuators, Electronic Throttle Bodies | `IATF 16949, ISO 9001, ISO 27001` | 10 days | 30 | 40 PPM | 93.5/100 | `APPROVED` |

---

## 6. Dealership Warranty Claims & Material Failure Log

Standardized warranty inspection tracking modeled on dealership failure verification, color-coded tagging (Yellow = OEM return, Red = Scrap), and claims reimbursement:

| Claim ID | Part ID | Component Description | Vehicle Model (Odo) | Failure Mechanism | Metallurgical Root Cause | Inspection Tag | Claim (₹) | Recovery (₹) | Status |
| :---: | :---: | :--- | :--- | :--- | :--- | :--- | :---: | :---: | :---: |
| `CLM-2026-001` | `BRK-201` | Front Ventilated Brake Rotor | Maruti Swift (18,450 km) | Lateral Runout & Brake Judder | Thermal warping due to excessive pad drag | Yellow Tag - Return to OEM | ₹2,600 | ₹2,600 | `APPROVED` |
| `CLM-2026-002` | `ENG-102` | Piston Assembly w/ Rings | Mahindra Scorpio-N (24,120 km) | Skirt Scuffing & Oil Consumption | Localized micro-welding; cooling jet clogging | Yellow Tag - Return to OEM | ₹4,800 | ₹4,800 | `APPROVED` |
| `CLM-2026-003` | `TRN-301` | Clutch Friction Plate | Tata Nexon (12,800 km) | Friction Material Delamination | Improper resin curing at supplier batch | Yellow Tag - Return to OEM | ₹2,750 | ₹2,750 | `APPROVED` |
| `CLM-2026-004` | `SUS-401` | MacPherson Strut Damper | Maruti Baleno (31,500 km) | Hydraulic Fluid Leakage at Rod Seal | Chrome micro-cracking causing seal abrasion | Yellow Tag - Return to OEM | ₹3,400 | ₹3,400 | `APPROVED` |
| `CLM-2026-005` | `ELE-502` | Alternator Rotor Assembly | Mahindra Thar (15,200 km) | Open Circuit / Zero Charging Output | Fatigue fracture of copper lead at slip ring | Yellow Tag - Return to OEM | ₹3,800 | ₹3,800 | `APPROVED` |
| `CLM-2026-010` | `TRN-303` | Synchronizer Ring 3rd Gear | Maruti Brezza (38,200 km) | Severe Gear Grinding / Lockup | Abrasive tooth wear due to contaminated gear oil | Red Tag - Customer Abuse / Denied | ₹1,350 | ₹0 | `REJECTED` |

---

## 7. Storage, Preservation & Environmental SOPs

- **Ferrous Components (Cast Iron & High-Alloy Steels)**: Must be preserved in volatile corrosion inhibitor (VCI) poly-bags with relative humidity strictly maintained below 50% RH.
- **Elastomeric Seals & EPDM Hoses**: Store away from electric motors and high-voltage ozone generators; store in ambient temperatures below 25°C to avoid polymer embrittlement.
- **Precision Sintered & Ceramic Friction Linings**: Keep hermetically sealed from moisture, oil mists, and hydrocarbon solvents to preserve the dynamic coefficient of friction (0.38 - 0.44).
- **Fasteners & Critical Clamping Bolts**: Store in original sealed manufacturer packaging with protective phosphate/oil coatings intact to prevent pre-installation hydrogen embrittlement.
