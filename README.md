# AUTO-ASD-NETWORK
Auto-ASD-Network
Please follow the instructions below in order to run the Auto-ASD-Network method.

Enviroment Setup:
The Specification of system and libraries which used for testing the code are as below:
  Linux operating system
  atm (Auto Tune Models) Version: 0.2.2.dev0 (Home-page: https://github.com/HDI-project/ATM)
  numpy
  scipy
  PyPrind
  Pytorch
  CUDA version 8 or above
  scikitlearn


Data:
  To download the fMRI data run the following command:
  python download.py

To run the code:
  bash script.sh 'site_name'
  In which site_name variable can be one of the followings:
  [USM,NYU,UCLA,OHSU]
  e.g. 
  bash script.sh 'UCLA'

The result of each algorithm will be stored in a text file inside a folder named results. 

In case of any questions please contact: taban.eslami@wmich.edu
