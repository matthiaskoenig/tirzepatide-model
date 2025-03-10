# model: tirzepatide_liver
Autogenerated ODE System from SBML with [sbmlutils](https://github.com/matthiaskoenig/sbmlutils).
```
time: [min]
substance: [mmol]
extent: [mmol]
volume: [l]
area: [m^2]
length: [m]
```

## Parameters `p`
```
TMEX_k = 0.00394930762501805  # [1/min] rate for tirzepatide import, export, transport in bile  
Vapical = nan  # [m^2] apical membrane  
Vbi = 1.0  # [l] bile  
Vext = 1.5  # [l] plasma  
Vli = 1.5  # [l] liver  
Vlumen = 1.15425  # [l] intestinal lumen (inner part of intestine)  
Vmem = nan  # [m^2] plasma membrane  
```

## Initial conditions `x0`
```
tm = 0.0  # [mmol/l] tirzepatide metabolites (liver) in Vli  
tm_bi = 0.0  # [mmol] tirzepatide metabolites (bile) in Vbi  
tm_ext = 0.0  # [mmol/l] tirzepatide metabolites (plasma) in Vext  
tm_lumen = 0.0  # [mmol/l] tirzepatide metabolites (lumen) in Vlumen  
```

## ODE system
```
# y
TMIM = TMEX_k * Vli * tm_ext  # [mmol/min] tirzepatide import (TMIM)  
TMEHC = TMIM  # [mmol/min] tirzepatide enterohepatic circulation  
TMEX = TMIM  # [mmol/min] tirzepatide bile export  

# odes
d tm/dt = TMIM / Vli - TMEX / Vli  # [mmol/l/min] tirzepatide metabolites (liver)  
d tm_bi/dt = TMEX - TMEHC  # [mmol/min] tirzepatide metabolites (bile)  
d tm_ext/dt = -TMIM / Vext  # [mmol/l/min] tirzepatide metabolites (plasma)  
d tm_lumen/dt = TMEHC / Vlumen  # [mmol/l/min] tirzepatide metabolites (lumen)  
```