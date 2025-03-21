# Dedicated PS table of the L1Menu_Collisions2022_v1_5_0 for testing
This PS table represents the new baseline PS table for trigger developments in view of the start of the 2023 Run 3 data-taking : [L1 Weekly Meeting 17th January 2023](https://indico.cern.ch/event/1242617/contributions/5224028/attachments/2577253/4444430/Menu%20studies%20at%20PU%2065-70_L1TWeeklyMeeting17012023.pdf)

Update : 18-01-2023

 - Prescaled the following seeds to 100 :

   - L1_DoubleMu0er2p0_SQ_OS_dEta_Max1p6 (bit 55)
   - L1_DoubleMu0er2p0_SQ_OS_dEta_Max1p5 (bit 56)

 - Disabled the following seeds :

   - (bit 83) L1_TripleMu_3SQ_2p5SQ_0OQ_Mass_Max12
   - (bit 94) L1_TripleMu_3SQ_2p5SQ_0DQ_Mass_Max12
   - (bit 95) L1_TripleMu_4SQ_2p5SQ_0OQ_Mass_Max12

 - Disabled   L1_DoubleEG11_er1p2_dR_Max0p6 (bit 214) in the baseline configuration (currently 2.2E34 column).
 - Column 2.1E34 is a testing configuration: copy of 2.2E34 column + bit 94 (TauTo3Mu seed) enabled
 - Column 2.0E34 is a testing configuration: copy of 2.2E34 column + bit 214 (DoubleEG B Parking) enabled
 - L1_DoubleMu0er1p4_OQ_OS_dEta_Max1p6 (bit 62) prescaled to 1000.
