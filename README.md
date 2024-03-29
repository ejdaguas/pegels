This readme.txt file was last updated on 2023-03-20 by Erika Aguas.

# General information
Title of Dataset: Polyelectrolyte Gel Adaptation Dataset </br>
Principal Investgator: Jay. C. Sy, PhD. jay.c.sy@rutgers.edu </br>
First Author: Erika D. Aguas, PhD. ejdaguas@gmail.com </br>
Institutiton: Dept of Biomedical Engineering, Rutgers University–New Brunswick </br>
Address: 599 Taylor Road, Piscataway, NJ 08854 </br>

Date of data collection: 2021-2023

Funding sources supporting data collection: </br>
GAANN Fellowship in Precision and Personalized Medicine </br>
Rutgers Biotechnology Training Program Fellowship </br>
NJ Commission on Brain Injury Research Fellowship </br>
Busch Biomedical Grant Program

This data is intended to accompany the RCS submission "Adaptation of a polyelectrolyte hydrogel for use as a micromotion-attenuating coating" (2023).

No restrictions are placed on this dataset.

# File-specific information
cyclicdeformation/cycdef_70x: Rheology results for cyclic deformation tests on low-PI gels (70/3-70/24) (three replicates). Time (sec), strain (%), G*, G', G" (Pa), and loss tangent (G"/G') are included for each experiment. Non-physical outliers, defined as rows with strain < 0.25%, were removed from the data. Following this, rows with fewer than two replicates represented were also excluded. This data is plotted in Figures 7 and 8 in the paper.

rheology_lowvshi/lowvhi_70x: Rheology results for sandwich-swelled low-PI and high-PI 70/3-70/24 gels (three replicates). G*, G' and G" values (Pa) and loss tangent presented for corresponding strain values (%). This data is plotted in Figure 5 in the paper.

rheology_swelling/swelling_70x: Rheology results for initial-swelled, sandwich-swelled, and fully-swelled low-PI 70/3-70/24 gels (three replicates). G*, G' and G" values (Pa) and loss tangent presented for corresponding strain values (%). This data is plotted in Figure 6 in the paper.

data_figure2: MTT assay results (signal minus background, 540nm reading - 630 nm reading) for four plates: three replicates of the PE gel results and one of the Am-only gel results. Results were normalized for visualization using the control wells on the respective plates.

data_figure3: Acrylamide concentrations (g/mL) from 70/3-70/24 gel washes over 4 days. "L" indicates low-PI gels and "H" indicates high-PI gels. Each column represents one gel. Three samples of each gel were included in this experiment. Concentrations were calculated from the acrylamide calibration curve shown in Supplementary Figure 1 using linear extrapolation.

data_figure4: MTT assay results (signal minus background, 540nm reading - 630 nm reading) for two plates: one for gels 70/3-70/12, one for gels 70/18 and 70/24. Each gel had three separate samples per plate. Results were normalized for visualization using the control wells on the respective plates. 

micromotiondata: Micromotion data is presented as [mean, SD, N] versus distance from probe center for all gels 70/3-70/24 and the control PEGDA gel. This data is plotted in Figure 9 in the paper.


