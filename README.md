# tcap2021DMTutorial
### TCAP 2021, Summer School.
Hands on session for DM analysis

## Prerequisites

1. Install ctools and gammalib. You should probably have a conda environment from the hand-on session dedicated to ctools.
2. Download the [prod3b-v2 IRFs](https://www.cta-observatory.org/wp-content/uploads/2019/04/CTA-Performance-prod3b-v2-FITS.tar.gz). After unzip the `.tar.gz` file, you must export the environment variable `CALDB` pointing to the directory caldb. If you have wget installed:
```
$ wget https://www.cta-observatory.org/wp-content/uploads/2019/04/CTA-Performance-prod3b-v2-FITS.tar.gz
$ export CALDB=/path/where/you/installed/IRF/caldb
```
3. Review the following tutorials:
  - [Model handling](http://cta.irap.omp.eu/ctools/users/tutorials/howto/howto_model_handling_python.html)
  - [Advanced model manipulation and fitting](http://cta.irap.omp.eu/ctools/users/tutorials/howto/howto_advanced_python_fitting.html)
  - From the ctools hands-on session: **revisit the Crab tutorial by playing with different analysis configurations and parameters**

## Setup

For the notebooks we have the following configuration:

1. `python............: >3.6`
2. `Gammalib..........: 1.7.4`
3. `ctools............: 1.7.4`
4. `jupyter core......: 4.7.1`
6. `jupyter-notebook..: 6.4.0`
7. `qtconsole.........: 5.1.1`
8. `ipython...........: 7.16.1`
9. `ipykernel.........: 5.5.5`
10. `jupyter client...: 6.1.12`
11. `jupyter lab......: not installed`
12. `nbconvert........: 6.0.7`
13. `ipywidgets.......: 7.6.3`
14. `nbformat.........: 5.1.3`
15. `traitlets........: 4.3.3`
16. `matplotlib.......: 3.3.4`

Then, a conda environment with more recent versions of the packages listed above should works.
