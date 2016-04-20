Q1 AVL
=====

This model is a work in progress

Initial dump of Quickie Q1 w/ GU foil model

Model is based on the Q1 build manual and paper templates, scaled up and roughly checked

Recently hacked BL/FS/WL into agreement with build manual, intiailly in improvised coordinates

Model contains canard and wing modeled as through-fuselage surfaces. Horizontal fuse approximately modeled, so all longitudinal elements have some fidelity

Formerly did not model inside-fuselage wing sections, and added vertical risers per VORLAX standard.  Predictions seemed poor, but joiners are left in, commented.  Will be removed in future iterations

Lateral elements mostly not modeled.  No wheel pants, no vertical fuse, only vertical stabilizer

Control surfaces believed generally accurate

Mass file is not particularly believed

Surface incidences from paper templates.  Some distributions seem strange

Both provided airfoils from UIUC, with paneling refinement and QDES work to smooth waves, especially in Eppler file.  Should not significantly influence AVL results

Todo includes massfile scrubbing, a run file, better lateral modeling
