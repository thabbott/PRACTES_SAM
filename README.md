# PRaCTES session 6: the System for Atmospheric Model (part of Numerical Models used in EAPS)

## What is SAM?

SAM is a convection-permitting (or cloud-permitting, or convection-resolving, or cloud-resolving) atmospheric model. It simulates atmospheric motions on scales from tens to hundreds of meters up to hundreds or thousands of kilometers and is used primarily as a process model to study phenomena that are marginally-resolved or unresolved in global general circulation models.

## What are examples of things you can do with SAM?

- [Simulate tornadoes](https://www.wired.com/video/watch/inside-a-tornado-modeled-by-a-supercomputer)
- [Study cumulus convection in different environments](https://www.youtube.com/watch?v=ojX6AU22cJU#action=share)
- [Study hurricane genesis](http://rossby.msrc.sunysb.edu/~marat/Loops/TC_1024x1024x64_2km_301K_Visible_short.mov)
- [Try to understand why tropical islands are so rainy](http://web.mit.edu/~twcronin/www/images/rce_i14_3d_cloudmovie_003min-res1-15fps.mp4)
- [Model pollutant dispersal (experimental)](http://rossby.msrc.sunysb.edu/~marat/NYC/nyc_take1.mov)
- [Run near-global cloud resolving simulations (experimental)](http://rossby.msrc.sunysb.edu/~marat/DYAMOND/DYAMOND_SAM_4km_rect.mp4)
- [Run case studies of specific hurricanes (experimental)](http://rossby.msrc.sunysb.edu/~marat/IRMA/IRMA_4km.mp4)

## Are there things you can't do with SAM?

Yes! SAM cannot

1. Simulate coupled atmosphere-ocean dynamics
2. Run on non-Cartesian domains (so no global simulations)
3. Run with orography (so no mountain meteorology)
4. Easily initialize itself from global forecast models (so limited usefulness for case studies or forecasting)
5. Run in 2D axisymmetric mode (so no cheap hurricane simulations)

(Although the experimental version of the model can do 2-4). If you're interested in any of 2-5, CM1 (https://www2.mmm.ucar.edu/people/bryan/cm1/) or WRF (https://www.mmm.ucar.edu/weather-research-and-forecasting-model) are good alternatives.

## Who in EAPS uses SAM?

Me, Raphael Rousseau-Rizzi, Rohini Shivamoggi, Ziwei Li, Martin Velez-Pardo (students); Daniel Koll, Janni Yuval (postdocs); Tim Cronin, Kerry Emanuel, Paul O'Gorman 

## Acquiring SAM

SAM is source-controlled but available to anybody. To get SAM, email the maintainer (Marat Khairoutdinov, http://rossby.msrc.sunysb.edu/~marat/) and ask to be added to the SAM users list. He usually responds quickly.
