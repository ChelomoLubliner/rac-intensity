# rac-intensity based on naomikap research
Improving spatial modeling of randomly acquired characteristics on outsoles 

#### Research of Naomi Kaplan: https://arxiv.org/abs/1912.08272
This research is based on Naomi Kaplan research, on the high resolution with random effects model.
In this research we add the distance parameter to the existing model.


#### Description:
The location of randomly acquired characteristics (RACs) is modeled here as a point process over the shoe sole. A database of RACs collected by the Israeli Police Division of Identification and Forensic Science, which includes 13,000 RACs from 386 lab shoeprints (Wiesner et al., 2019) is used to estimate its intensity function. The analysis is somewhat complicated as the shoes are differentiated by shape, level of wear and tear and contact surface. We present methods that take into account these challenges, either by using natural cubic splines on high resolution data, or by using a piecewise-constant model on larger regions defined by experts' knowledge.

### Data sets:

A. locations_data.CSV: A data set of RAC locations. The first three columns are used. The first column indicates the shoe number. The second indicates the x axis of the RAC location . The third indicates the Y axis of the RAC location.

B. contacts_data.txt: A data set of the contact surface This is a pixel data where 1 indicates there is a contact surface and 0 otherwise. There are 307 columns in each shoe and 395 is the number of rows. The number of shoes is 387 but 386 is the number of shoes with RACs - shoe 127 has no RACS.
The dataset is here : https://github.com/naomikap/rac-intensity/tree/master/Data

If using the data, please cite the  paper https://arxiv.org/abs/1912.08272 and Wiesner, S., Shor, Y., Tsach, T., Kaplan-Damary, N., & Yekutieli, Y. (2020). Dataset of Digitized RACs and Their Rarity Score Analysis for Strengthening Shoeprint Evidence. Journal of Forensic Sciences, 65(3), 762-774. Last updated: 8/31/2020


