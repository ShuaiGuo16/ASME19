This folder contains the code to address the third design task: Realistic control design
******************************************************************

Run 'GP_RControl.m' to perform rubost optimization

===> It loads 'GP.mat' (trained GP models)
              
                        'X.mat' (pre-generated Monte Carlo samples for risk calculation)
******************************************************************

Run 'PDF_Compare_Cav.m' and 'PDF_Compare_ITA.m' to compare GP results with reference results at the optimum mean tau_c

===> It loads 'GP.mat' (trained GP models)
             
           'MC.mat' (validation set), which is generated in /Monte_Carlo_Results/ folder
******************************************************************

/Monte_Carlo_Results/ folder contains the reference Monte Carlo results at the optimum mean tau_c

******************************************************************

Run 'MC_databank.m' to perform Monte Carlo simulation
===> It generates 'MC.mat'
