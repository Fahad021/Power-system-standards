# Power System Standards (Grouped by Power Engineering Role)

This repository is a curated starting point for power engineers to find commonly used standards, grouped by discipline, with relevant GitHub repositories for practical implementation and study.

> Notes:
> - Standards documents are typically copyrighted by their issuing organizations (IEEE, IEC, NFPA, etc.).
> - Where possible, links point to official catalog pages plus open-source repositories commonly used alongside those standards.
> - This is a living list and not an exhaustive legal compliance guide.

## 1) Protection & Control Engineers

| Standard | Scope | Relevant GitHub Repositories |
|---|---|---|
| IEC 61850 | Substation communication networks and systems | [openiec61850/openiec61850](https://github.com/openiec61850/openiec61850), [mz-automation/libiec61850](https://github.com/mz-automation/libiec61850) |
| IEEE C37.2 / C37 series | Device function numbers, switchgear, breaker and relay practices | [GitHub topic search: relay protection](https://github.com/search?q=IEEE+C37+relay+protection&type=repositories) |
| IEEE 242 (Buff Book) | Protection and coordination in industrial/commercial systems | [GitHub search: IEEE 242 protection coordination](https://github.com/search?q=IEEE+242+protection+coordination&type=repositories) |
| IEC 60255 | Measuring relays and protection equipment | [GitHub search: IEC 60255 relay testing](https://github.com/search?q=IEC+60255+relay+testing&type=repositories) |

## 2) Transmission Planning & Stability Engineers

| Standard | Scope | Relevant GitHub Repositories |
|---|---|---|
| NERC TPL-001 | Transmission system planning performance requirements | [pnnl/tesp](https://github.com/pnnl/tesp), [NREL-Sienna/PowerSystems.jl](https://github.com/NREL-Sienna/PowerSystems.jl) |
| IEEE 399 (Brown Book) | Power system analysis | [MATPOWER/matpower](https://github.com/MATPOWER/matpower), [e2nIEE/pandapower](https://github.com/e2nIEE/pandapower) |
| IEC 60909 | Short-circuit current calculations in 3-phase AC systems | [e2nIEE/pandapower](https://github.com/e2nIEE/pandapower) |
| IEC 60826 | Design criteria for overhead transmission lines | [GitHub search: IEC 60826 transmission line design](https://github.com/search?q=IEC+60826+transmission+line+design&type=repositories) |

## 3) Distribution Engineers

| Standard | Scope | Relevant GitHub Repositories |
|---|---|---|
| IEEE 1547 | Interconnection and interoperability of DER with electric power systems | [NREL/PyDSS](https://github.com/NREL/PyDSS), [gridlab-d/gridlab-d](https://github.com/gridlab-d/gridlab-d) |
| IEEE 519 | Harmonic control in electric power systems | [GitHub search: IEEE 519 harmonics](https://github.com/search?q=IEEE+519+harmonics&type=repositories) |
| IEC 61000 series | EMC and power quality standards | [GitHub search: IEC 61000 power quality](https://github.com/search?q=IEC+61000+power+quality&type=repositories) |
| EN 50160 | Voltage characteristics of electricity supplied by public distribution systems | [GitHub search: EN 50160 voltage quality monitoring](https://github.com/search?q=EN+50160+voltage+quality+monitoring&type=repositories) |

## 4) Substation Design Engineers

| Standard | Scope | Relevant GitHub Repositories |
|---|---|---|
| IEEE 80 | Grounding in AC substations | [InterPSS-Project/ipss-plugin](https://github.com/InterPSS-Project/ipss-plugin) |
| IEEE 81 | Measuring earth resistivity and ground impedance | [GitHub search: substation grounding IEEE 81](https://github.com/search?q=IEEE+81+grounding&type=repositories) |
| IEC 61936-1 | Power installations exceeding 1 kV AC | [tumcms/Open-Infra-Platform](https://github.com/tumcms/Open-Infra-Platform) |
| IEC 60076 | Power transformers | [PyPSA/pypsa](https://github.com/PyPSA/PyPSA) |

## 5) Operations, Reliability & Grid Compliance Engineers

| Standard | Scope | Relevant GitHub Repositories |
|---|---|---|
| NERC CIP (family) | Cybersecurity requirements for BES assets | [NERC-CIP-Compliance-Tools](https://github.com/search?q=NERC+CIP+compliance&type=repositories) |
| NERC PRC (family) | Protection and control reliability standards | [openXDA/openXDA](https://github.com/GridProtectionAlliance/openXDA) |
| IEEE 1366 | Distribution reliability indices (SAIDI, SAIFI, CAIDI) | [dss-extensions/dss_python](https://github.com/dss-extensions/dss_python) |
| IEC 60870-5-104 | Telecontrol protocols for SCADA | [mz-automation/lib60870](https://github.com/mz-automation/lib60870) |

## 6) Power Quality & Metering Engineers

| Standard | Scope | Relevant GitHub Repositories |
|---|---|---|
| IEC 61000-4-30 | Power quality measurement methods | [GitHub search: IEC 61000-4-30 power quality measurement](https://github.com/search?q=IEC+61000-4-30+power+quality+measurement&type=repositories) |
| IEC 61000-4-7 | Harmonics and interharmonics instrumentation | [GitHub search: IEC 61000-4-7 harmonics](https://github.com/search?q=IEC+61000-4-7+harmonics&type=repositories) |
| IEEE 1459 | Definitions for measurement of electric power quantities | [GitHub search: IEEE 1459 power measurement](https://github.com/search?q=IEEE+1459+power+measurement&type=repositories) |
| ANSI C12 family | Electricity metering standards | [openenergymonitor/EmonLib](https://github.com/openenergymonitor/EmonLib) |

## 7) Renewable Integration & DER Engineers

| Standard | Scope | Relevant GitHub Repositories |
|---|---|---|
| IEEE 1547.1 | Conformance testing procedures for DER interconnection | [NREL/ditto](https://github.com/NREL/ditto) |
| IEC 61400 series | Wind turbine design and grid compliance | [OpenFAST/openfast](https://github.com/OpenFAST/openfast) |
| IEC 61724 | PV system performance monitoring | [pvlib/pvlib-python](https://github.com/pvlib/pvlib-python) |
| UL 1741 / IEEE 2800 (utility practice context) | Inverter-based resource interconnection and grid support | [GitHub search: IEEE 2800 inverter models](https://github.com/search?q=IEEE+2800+inverter+grid+model&type=repositories) |

## 8) HVDC & FACTS Engineers

| Standard | Scope | Relevant GitHub Repositories |
|---|---|---|
| IEC 62747 | Terminology for voltage-sourced converter (VSC) HVDC systems | [OpenIPSL/OpenIPSL](https://github.com/OpenIPSL/OpenIPSL) |
| IEC 62501 | Voltage sourced converter valves for HVDC power transmission | [PyPSA/pypsa-eur](https://github.com/PyPSA/pypsa-eur) |
| CIGRE technical brochures (practice guides) | HVDC/FACTS engineering guidance | [CIGRE papers mirror/search](https://github.com/search?q=CIGRE+HVDC&type=repositories) |

## 9) Electrical Safety & Industrial Power Engineers

| Standard | Scope | Relevant GitHub Repositories |
|---|---|---|
| NFPA 70 (NEC) | Electrical installation requirements | [GitHub search: NEC code tools](https://github.com/search?q=NFPA+70+NEC+electrical+code&type=repositories) |
| NFPA 70E | Electrical safety in the workplace | [Arc-Flash-Calculator](https://github.com/search?q=arc+flash+calculator&type=repositories) |
| IEEE 1584 | Arc-flash hazard calculations | [arcflash-calculator](https://github.com/search?q=IEEE+1584+arc+flash&type=repositories) |
| IEC 60364 | Low-voltage electrical installations | [electrical-installation-calc](https://github.com/search?q=IEC+60364+electrical+installation&type=repositories) |

## 10) Widely Used Open-Source Power System Tooling (Cross-Discipline)

- [MATPOWER/matpower](https://github.com/MATPOWER/matpower) - Power flow and OPF
- [e2nIEE/pandapower](https://github.com/e2nIEE/pandapower) - Distribution/transmission analysis
- [PyPSA/PyPSA](https://github.com/PyPSA/PyPSA) - Sector-coupled energy and power system analysis
- [gridlab-d/gridlab-d](https://github.com/gridlab-d/gridlab-d) - Distribution simulation
- [dss-extensions/OpenDSSDirect.py](https://github.com/dss-extensions/OpenDSSDirect.py) - OpenDSS Python interface
- [NREL/PyDSS](https://github.com/NREL/PyDSS) - Time-series distribution simulation
- [OpenIPSL/OpenIPSL](https://github.com/OpenIPSL/OpenIPSL) - Dynamic models for power systems

## 11) Official Standards Bodies (Primary Sources)

- [IEEE Standards Association](https://standards.ieee.org/)
- [IEC](https://www.iec.ch/)
- [NERC Reliability Standards](https://www.nerc.com/pa/Stand/Pages/default.aspx)
- [CIGRE](https://www.cigre.org/)
- [NFPA Codes and Standards](https://www.nfpa.org/codes-and-standards)
- [ANSI](https://www.ansi.org/)
