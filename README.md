# fwi_gpgpu_github



Essential Files for execution of modleing:


sources.py: Needed for soure generation: Sources already created using this py file. No editing required
win_overt.bin: Nodel File: No changes required


ompfunc.c: Definition of threads
modeling.c:  Main Function; Requires cleaning and editing
fdutilc:   All funtions: Requires cleaning


dobs.bin: observed data at specified receviers from t = (25 Geophones at ?)
fswfld.bin: u(x,y) at all time frames


Commands to execute the code:

gcc -fopenmp modeling.c
./modleing
