batman: Bad-Ass Transit Model cAlculatioN
=========================================

The ``batman`` package for Python makes super fast calculation of transit light curves easy.  Check out the docs at https://www.cfa.harvard.edu/~lkreidberg/batman/.    

This is a fork of the batman-package.    
Aims: it removes the detect function (to check openMP) in the TransitModel to speed-up the computation avoiding the creation of `hasfunction-XXXXX` folders in `/tmp` and allowing to init the object TransitModel in loop with different params objects.

