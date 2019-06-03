This folder contains the code to generate risk diagram under three different parameter distributions
****************************************************************************************

Run 'RiskMap_distributions.m' to calculate risk diagram under different parameter distributions

===> it loads 'GP.mat' (trained GP models), and pre-generated Monte Carlo samples for risk factor calculation
                                                
                  ===> ('MC_uni.mat' for case A)
                                               
                  ===> ('MC_uncor.mat' for case B)
                                                
                  ===> ('MC_cor.mat' for case C)

===> it produces risk factor grid data for case A ('ITA_RF.mat' & 'CAV_RF.mat'), 
                                                                                      case B ('Un_ITA_RF.mat' & 'Un_CAV_RF.mat')
                                                                           case C ('Cor_ITA_RF.mat' & 'Cor_CAV_RF.mat')

===> The covariance matrix for flame parameters required by case C is in 'CovKomarek.mat'
*****************************************************************************************

Run 'PostProcessing.m' to plot the joint results

===> it loads 'ITA_RF.mat' & 'CAV_RF.mat' for case A
              
                        'Un_ITA_RF.mat' & 'Un_CAV_RF.mat' for case B
              
                        'Cor_ITA_RF.mat' & 'Cor_CAV_RF.mat' for case C

