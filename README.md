#  Numerical Experiments Data from the paper entitled "Distributionally Robust Optimal Power Flow with Contextual Information"

## Goals

The purpose of this repository is to provide the details of the numerical experiments coded in the Python programming language used in the paper [[1]](https://arxiv.org/abs/2009.10592). This paper has been developed by some members of the [OASYS group](https://sites.google.com/view/groupoasys/home) through funding from the project [Flexanalytics](https://groupoasysflexanalytics.readthedocs.io/en/latest/). We encourage you visit the related links to know more about our research.

## Contents

This repository includes the data about the two test problems used in the paper:

- A 118-bus case study:

  * [118bus_generation_data]: This folder contains the data used in the numerical experiment corresponding to the  118-bus case study with contextual information considered in [[1]](). The file "indices+str(N)".csv contains the 400 samples' index of size N; that is, each row (total=400) of the .csv file represents a sample of size N. The data points of the bivariate distribution are in the file entitled "muestra_dist_real.csv". The rest of the parameters of the numerical experiments are described in [[1]]().

- Illustrative example (3-bus system) at the Appendix.

  * [3bus_generation_data]: This folder contains the data used in the numerical experiment corresponding to the portfolio allocation problem with side information used in [[1]]().    The file "indices+str(N)".csv contains the 200 samples' index of size N; that is, each row (total=200) of the .csv file represents a sample of size N. The data points of the joint distribution are in the file entitled "muestra_real_conjunta.csv".  The rest of the parameters of the numerical experiment are described in [[1]](). The main test case deals with the case in which alpha=0 and the data points of the true conditional distribution of this case are in the file entitled "muestra_dist_real.csv". Some crucial remarks to reproduce the numerical experiments in the paper in the case alpha=0:

   


The folder Codes contains the codes used in the numerical experiments.
 
## References 📚
[1] Esteban-Pérez, A., & Morales, J. M. (2021).   



## Do you want to contribute? 👨🏾‍🔬
 
 Any feedback is welcome :sparkles: so please feel free to ask about or comment on anything you want via a Pull Request in this repo.
 If you need more help, you can ask Adrián Esteban-Pérez (adrianesteban@uma.es) :e-mail:.

 ## Contributors
 
 * [OASYS group](http://oasys.uma.es) -  groupoasys@gmail.com
 
 ## Developed by 👨🏾‍💻
 * [Adrián Esteban-Pérez](https://scholar.google.es/citations?user=iDEU4ZAAAAAJ&hl=es https://www.researchgate.net/profile/Adrian_Esteban-Perez) - adrianesteban@uma.es 

 ## License 📝
 
    Copyright 2021 Optimization and Analytics for Sustainable energY Systems (OASYS)

    Licensed under the GNU General Public License, Version 3 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.gnu.org/licenses/gpl-3.0.en.html

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
