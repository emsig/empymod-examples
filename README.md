# Examples for [empymod](https://github.com/empymod/empymod)

0. [Published results](#user-content-0-published-results-in-other-repositories)
1. [Frequency-domain examples](#user-content-1-frequency-domain-examples)
2. [Time-domain examples](#user-content-2-time-domain-examples)
3. [Comparison to analytical solution](#user-content-3-comparison-to-analytical-solution)
4. [Add-ons](#user-content-4-add-ons)
5. [Reproducing published results](#user-content-5-reproducing-published-results)
6. [Tools](#user-content-6-tools)
7. [Explanations and educational material](#user-content-7-explanations-and-educational-material)

## 0. Published results in other repositories

* See [article-tle2017](https://github.com/empymod/article-tle2017) for:

  > Werthmüller, D., 2017, Getting started with controlled-source
  > electromagnetic 1D modeling: The Leading Edge, 36, 352-355;
  > doi: [10.1190/tle36040352.1](http://dx.doi.org/10.1190/tle36040352.1).

  Contains 2 notebooks with eight frequency- and time-domain examples.


* See [article-geo2017](https://github.com/empymod/article-geo2017) (in
  the `notebooks`-directory) for:

  > Werthmüller, D., 2017, An open-source full 3D electromagnetic modeler for
  > 1D VTI media in Python: empymod: Geophysics, 82(6), WB9-WB19; DOI:
  > [10.1190/geo2016-0626.1](http://doi.org/10.1190/geo2016-0626.1).

  Contains:
    * Comparison to analytical solution
    * FHT filter comparison
    * GPR example
    * Time-domain example


* See [article-fdesign](https://github.com/empymod/article-fdesign) (in the
  `notebooks`-directory) for:

  > Werthmüller, D., K. Key, and E. Slob, 2018, A tool for designing digital
  > filters for the Hankel and Fourier transforms in potential, diffusive, and
  > wavefield modeling: Submitted to Geophysics.

  Contains:
    * Examples regarding the design of digital filters for the Hankel and
      Fourier transforms
    * GPR example with a digital filter


* See
  [csem-ziolkowski-and-slob](https://github.com/empymod/csem-ziolkowski-and-slob)
  for:

  > Ziolkowski, A., and E. Slob, 2018, Introduction to Controlled-Source
  > Electromagnetic Methods: Cambridge University Press.

  Contains all numerical examples of the book, 61 in total, frequency- and
  time-domain.

## 1. Frequency-domain examples

* [1a_Frequency_Single-and-Crossplot](./1a_Frequency_Single-and-Crossplot.ipynb)  
  Frequency example, for a single frequency and crossplot frequency vs offset.

* [1b_Frequency_Dipole-vs-Bipole](./1b_Frequency_Dipole-vs-Bipole.ipynb)  
  Comparison of a 800 m long bipole with a dipole at its centre.

* [1c_Comparison_of_Source-Receiver_Combinations](./1c_Comparison_of_Source-Receiver_Combinations.ipynb)  
  Comparison of all source-receiver combinations; electric and magnetic.

## 2. Time-domain examples

* [2a_Time_Step-and-Impulse](./2a_Time_Step-and-Impulse.ipynb):  
  Comparison of QWE, FHT, FFTLog, and FFT for frequency-to-time transformation.

* [2b_DC_rho-a_Dipole-Dipole](./2b_DC_rho-a_Dipole-Dipole.ipynb):  
  Example of DC apparent resistivity calculation for the dipole-dipole
  arrangement.


## 3. Comparison to analytical solution

* [3a_Full-Diffusive_comparison](./3a_Full-Diffusive_comparison.ipynb)  
  Comparison of the diffusive with the full wavefield analytical
  full-space solutions.

* [3b_Halfspace-Dipole_comparison](./3b_Halfspace-Dipole_comparison.ipynb)  
  Comparison of `analytical` with `dipole` for half- and fullspaces.

## 4. Add-ons

* [4a_TMTE-split](./4a_TMTE-split.ipynb)  
  Contributions of up- and downgoing TM- and TE-modes.

* [4b_Digital-Linear-Filter_design](./4b_Digital-Linear-Filter_design.ipynb)  
  Design a Digital Linear Filter (DLF) for the Hankel transform.


## 5. Reproducing published results

* [5a_CSEM](./5a_CSEM.ipynb):  
  So far: Constable and Weiss (2006); Ziolkowski et al. (2007).


## 6. Tools
* [6a_Benchmark](./6a_Benchmark.ipynb)  
  Example benchmark to check which method is best for a given problem.

* [6b_Profiling](./6b_Profiling.ipynb)  
  Example for profiling the code.


## 7. Explanations and educational material
* [7a_DLF-Standard-Lagged-Splined](./7a_DLF-Standard-Lagged-Splined.ipynb)  
  Graphical explanation of the different optimisation methods for the DLF.
