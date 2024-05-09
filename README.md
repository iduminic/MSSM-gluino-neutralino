# Gluino-pair production simulation

Simulations of the gluino-pair production, with each gluino decaying to a quark-antiquark pair and a neutralino.

## Software requirements

In order to run the input cards, one needs to pre-install:

- [ROOT](https://root.cern/install/)
- [Pythia8](https://pythia.org)
- [DELPHES](https://github.com/delphes/delphes)
- [MadGraph5](https://launchpad.net/mg5amcnlo)

## Run the command cards

In the MG5 directory, do:

```
$ nohup ./bin/mg5_aMC ../MSSM-gluino-neutralino/input-cards/MSSM_testing_gogo_TESTCKKW_{neutralino_mass}-{gluino_mass}.dat > output_{neutralino_mass}-{gluino_mass}.txt &