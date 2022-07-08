# Fracture energy
Data collection including published research data on the topic of fracture energy. In Cocco et al., in prep, we tried to include the broadest number of fracture energy estimates as possible, from many communities, ranging from laboratory, field geology, modelling and seismology.  

Contributors of this work are (in alphabetical order):
- Aretusini, S.
- Cornelio, C.
- Cocco, M.
- Spagnuolo, E.
- Tinti, E.
- Di Toro, G.
- Nielsen, S.

We hosted our data collection here in Github to benefit from the collaborative nature of this community.

The first release of this repository will be published directly to Zotero.

Further releases will be improved also according to the feedback from the community via the Issues to this repository. 
All contributors acknowledge that at its current state this data collection is not complete and hope to complete it further thanks to the scientific community.

We acknowledge for providing their data:
Harbord, C.
Paglialunga, F.
Scuderi, M.
Selvadurai, P.

And thank in particular Selvadurai, P. for the support.

# Description of data

The files included in this repository present the estimates of fracture energy divided by scientific community:
1. Geology: merged_data-geology.csv
2. Laboratory: merged_data-laboratory.csv
3. Numerical models: merged_data-models.csv
4. Seismology: merged_data-seismology.csv

All files above point to another file containing the references: merged_data-references.csv

## Geology
Estimates of fracture energy with rock deformation laboratory experiments.
Column | Description
 --- | ---
earthquake | Name of the earthquake if directly connected to the analysis
fault | Name of the fault where the analysis was performed
place in fault | Place in the fault where the analysis was performed, possibly with the original name used in the publication
on vs off fault | Place in the fault considering as "on fault" all the rocks in the fault core and as "off fault" all the rocks around the fault core
method | Method used to measure the surface area (PD = particle density, FD = fracture density, BET = Brunauer, Emmett and Teller)
type of energy | Name of the type of estimated energy density, possibly with the original name used in the publication (e.g. global surface energy, or surface energy per event)
value (J/m^2) | Value of estimated energy density
min (J/m^2) | Minimum value of estimated energy density
max (J/m^2) | Maximum value of estimated energy density
type of slip | Name of the type of estimated slip, possibly with the original name used in the publication (e.g., global slip, or slip per event)
value (m) | Value of fault slip
min (m) | Minimum value of fault slip
max (m) | Maximum value of fault slip
Reference | Reference to the paper where data was first published
Collection | Reference to a paper with a data collection including the data
Notes | Notes on the origin of data

## Laboratory
Estimates of fracture energy with rock deformation laboratory experiments.

Column | Description
 --- | --- 
name | Unique identifier of the experiment or event during an experiment
machine | Machine or apparatus used to perform the experiment (e.g., triaxial, large-sample biaxial, direct shear, biaxial, rotary, uniaxial, or double direct shear in triaxial)
experiment | Brief description of the experiment (e.g., shear fracture, stick slip, yoffe, trapezoidal, flywheel, creep test, or stick slip (destiffened machine))
material | Name of the material used in the experiment
sample | Type of sample (e.g., saw-cut, intact, or gouge)
fluid | Name of the fluid used in the experiment
method | Names of special methods used (e.g. AE for acoustic emission)
type of energy | Name of the type of energy density estimated in the experiment, possibly with the original name used in the publication (e.g. Wb, Gamma, Gamma_off, Ge,min, heat, WT, GII, surface energy, Gamma_bulk, Wb+Wr (bin), Wbd,tip, Wbd, G, G*, G_IIC, G_C^S, Wb(Dc), or Wb(Dth))
value (J/m^2) | Value of estimated energy density
min (J/m^2) | Minimum value of estimated energy density
max (J/m^2) | Maximum value of estimated energy density
type of slip | Name of the type of slip estimated in the experiment, possibly with the original name used in the publication (e.g., slip, Dc, average slip, total slip, slip (bin), Dfin, delta_nom, deltau_avg, delta, deltau, Dth, slip of event)
value (m) | Value of fault slip
min (m) | Minimum value of fault slip
max (m) | Maximum value of fault slip
normal stress (MPa) | Controlled normal stress on the sample
conf stress (MPa) | Controlled confining stress
pore press (MPa) | Controlled pore fluid pressure
stress drop (MPa) | Spontaneous stress drop during the experiment
T (°C) | Controlled temperature
peak slip velocity (m/s) | Spontaneous or controlled maximum fault slip velocity during the experiment
Reference | Reference to the paper where data was first published
Collection | Reference to a paper with a data collection including the data
Notes | Notes on the origin of data
Group | Group numbering following Cocco et al., in prep.

## Models
Estimates of fracture energy with numerical models.
Column | Description
 --- | ---
earthquake | Name of the earthquake if directly connected to the analysis, or unique identifier of the analysis
type of energy | Name of the type of estimated energy density, possibly with the original name used in the publication (e.g. Wb, avg Wb (>20%), or average Wb)
value (J/m^2) | Value of estimated energy density
min (J/m^2) | Minimum value of estimated energy density
max (J/m^2) | Maximum value of estimated energy density
type of slip | Name of the type of estimated slip, possibly with the original name used in the publication (e.g., slip, or average slip)
value (m) | Value of fault slip
min (m) | Minimum value of fault slip
max (m) | Maximum value of fault slip
type of stress drop | Name of the type of estimated stress drop, possibly with the original name used in the publication (e.g., energy-based stress drop)
value (Pa) | Value of stress drop
Reference | Reference to the paper where data was first published
Collection | Reference to a paper with a data collection including the data
Notes | Notes on the origin of data
Type of model | Category of model (e.g. pseudo-dynamic, or spontaneous-dynamic)

## Seismology
Estimates of fracture energy with from seismologic data (natural, induced, and laboratory seismic events).
Column | Description
 --- | ---
id | unique identifier of the analysis
earthquake | Name of the seismic event on which the analysis was done
M0 (seismic moment, Nm) | Seismic moment of the event
a (radius, m) | Rupture radius of the seismic event (assumes a circular seismic source)
deltasigma (stress drop, Pa) | Stress drop during the seismic event
Er (radiated energy, J) | Radiated energy by the seismic event
tau_i (Pa) | Initial stress on the fault
type of energy | Name of the type of estimated energy density, possibly with the original name used in the publication (e.g. G', or Gmax)
value (J/m^2) | Value of estimated energy density
min (J/m^2) | Minimum value of estimated energy density
max (J/m^2) | Maximum value of estimated energy density
type of slip | Name of the type of estimated slip, possibly with the original name used in the publication (e.g., slip)
value (m) | Value of fault slip
min (m) | Minimum value of fault slip
max (m) | Maximum value of fault slip
Reference M0, a | Reference to the paper where seismic moment and rupture radius data was first published
Reference Er | Reference to the paper where radiated energy data was first published
Reference slip, G' | Reference to the paper where slip and energy density data was first published. Most of data here was recalculated directly from radiated energy, seismic moment and rupture radius.
Collection | Reference to a paper with a data collection including the data
Notes | Notes on the origin of data
Type of seismic event | Category of seismic event (e.g. natural, induced, or laboratory)

## References
Column | Description
 --- | ---
Name | Name of the reference
Title | Title of the referenced publication
Community | Data file in which the reference is used (e.g., geology, laboratory, models, or seismology) 
Type | Category of the reference (e.g., Reference, or Collection)
