[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14976788.svg)](https://doi.org/10.5281/zenodo.14976788)

# Tirzepatide model
This repository provides the tirzepatide physiologically based pharmacokinetics (PBPK) model.

The model is distributed as [SBML](http://sbml.org) available from [`tirzepatide_body_flat.xml`](./models/tirzepatide_body_flat.xml) with the COMBINE archive available from [`tirzepatide_model.omex`](./tirzepatide_model.omex).

The model is distributed as [SBML](http://sbml.org) available from [`tirzepatide_body_flat.xml`](./models/tirzepatide_body_flat.xml) with 
corresponding SBML4humans model report at [https://sbml4humans.de/model_url?url=https://raw.githubusercontent.com/matthiaskoenig/tirzepatide-model/main/models/tirzepatide_body_flat.xml](https://sbml4humans.de/model_url?url=https://raw.githubusercontent.com/matthiaskoenig/tirzepatide-model/main/models/tirzepatide_body_flat.xml) and equations from [`tirzepatide_body_flat.md`](./models/tirzepatide_body_flat.md).

The COMBINE archive is available from [`tirzepatide_model.omex`](./tirzepatide_model.omex).

![model overview](./figures/tirzepatide_model.png)

### Comp submodels
The liver submodel is available from [`tirzepatide_liver.xml`](./models/tirzepatide_liver.xml) with corresponding SBML4humans report at
[https://sbml4humans.de/model_url?url=https://raw.githubusercontent.com/matthiaskoenig/tirzepatide-model/main/models/tirzepatide_liver.xml](https://sbml4humans.de/model_url?url=https://raw.githubusercontent.com/matthiaskoenig/tirzepatide-model/main/models/tirzepatide_liver.xml) and equations from [`tirzepatide_liver.md`](./models/tirzepatide_liver.md).

The kidney submodel is available from [`tirzepatide_kidney.xml`](./models/tirzepatide_kidney.xml) with corresponding SBML4humans report at
[https://sbml4humans.de/model_url?url=https://raw.githubusercontent.com/matthiaskoenig/tirzepatide-model/main/models/tirzepatide_kidney.xml](https://sbml4humans.de/model_url?url=https://raw.githubusercontent.com/matthiaskoenig/tirzepatide-model/main/models/tirzepatide_kidney.xml) and equations from [`tirzepatide_kidney.md`](./models/tirzepatide_kidney.md).

The whole-body submodel is available from [`tirzepatide_body.xml`](./models/tirzepatide_body.xml) with corresponding SBML4humans report at
[https://sbml4humans.de/model_url?url=https://raw.githubusercontent.com/matthiaskoenig/tirzepatide-model/main/models/tirzepatide_body.xml](https://sbml4humans.de/model_url?url=https://raw.githubusercontent.com/matthiaskoenig/tirzepatide-model/main/models/tirzepatide_body.xml) and equations from [`tirzepatide_body.md`](./models/tirzepatide_body.md).

## How to cite
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14976788.svg)](https://doi.org/10.5281/zenodo.14976788)

> Mishra, A., & König, M. (2025).
> *Physiologically based pharmacokinetic (PBPK) model of tirzepatide.*   
> Zenodo. [https://doi.org/10.5281/zenodo.14976788](https://doi.org/10.5281/zenodo.14976788)

## License

* Source Code: [MIT](https://opensource.org/license/MIT)
* Documentation: [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)
* Models: [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)

This program is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE.

## Funding
Matthias König was supported by the Federal Ministry of Education and Research (BMBF, Germany) within LiSyM by grant number 031L0054 and ATLAS by grant number 031L0304B and by the German Research Foundation (DFG) within the Research Unit Program FOR 5151 QuaLiPerF (Quantifying Liver Perfusion-Function Relationship in Complex Resection - A Systems Medicine Approach) by grant number 436883643 and by grant number 465194077 (Priority Programme SPP 2311, Subproject SimLivA). This work was supported by the BMBF-funded de.NBI Cloud within the German Network for Bioinformatics Infrastructure (de.NBI) (031A537B, 031A533A, 031A538A, 031A533B, 031A535A, 031A537C, 031A534A, 031A532B). 

© 2025 Abhinav Mishra and Matthias König, [Systems Medicine of the Liver](https://livermetabolism.com)