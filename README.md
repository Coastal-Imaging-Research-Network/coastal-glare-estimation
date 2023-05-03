# A Globally Verified Coastal Glare Estimation Tool

Run the algorithm with:
- glare_estimator.ipynb

Supporting files and folders that need to be in the working directory of glare_estimator.ipynb:
- phone_images (note that the metadata has been removed from these images for privacy. If you want to check the original metadata used for making table B1 in the paper, please email michael.thompson2@uq.net.au)
- th_dist_cm.csv

Paper available at https://doi.org/10.1016/j.coastaleng.2022.104190

Supplementary data folders and files:
- phone_results_comparison_table_1.xlsx
- glare_graph_images_section_3p2
- glare_start_finish_times.xlsx
- phone_image_results_section_3p1
- glare_graph_results_section_3p2

Example glare graph from glare_estimator.ipynb:
![glare_graph_example](https://github.com/mikeyt120/coastal-glare-estimation/blob/main/glare_graph_example.png)

Light reflection geometry model:
![glare_model_eq](https://github.com/mikeyt120/coastal-glare-estimation/blob/main/glare_model_eq.jpg)
In the above image, the light blue rotations are theta_wx and red rotations are theta_wy. In this lego model, theta_wx is in the opposite direction to figure 8a in the paper. My collegue's Chewbacca was particularly interested in geometry so flew over to check it out.

The software was originally written with the following versions of code and libraries:
- anaconda v4.11.0
- python v3.8.5
- numpy v1.19.2
- matplotlib v3.3.2
- astropy v4.0.2 (doesn't come with anaconda installation)
- cv2 v4.4.0.46 (doesn't come with anaconda installation)

"From the rising of the sun to the place where it sets, the name of the Lord is to be praised." Psalm 113:3

