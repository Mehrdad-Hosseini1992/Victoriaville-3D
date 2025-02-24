# Victoriaville-3D
Open source Lidar point cloud dataset

With the advancement of 3D point cloud segmentation and classification methods through machine learning, there is an increasing need for high-quality and extensive datasets. The effectiveness of training models relies heavily on having large, well-labeled datasets that encompass a broad range of point types, classes, and segmentation qualities. While there are numerous datasets available for image classification and segmentation, stereo vision, visual odometry, vehicle and pedestrian detection in videos, and other optical methods, there remains a significant gap in the availability of urban 3D point cloud datasets that are both segmented and classified.

Many of the available point cloud datasets have been published through initiatives by universities or companies aimed at testing and comparing alternative methodologies. However, these datasets often fall short when it comes to specific applications such as assessing pedestrian accessibility within urban environments.

This motivated us to develop Victoriaville3D datasets. This Datasets aim to fill the existing gap, facilitating research and development efforts to improve urban accessibility and ensure that all environments are navigable for everyone.

This research project focuses on leveraging mobile LiDAR data to extract environmental factors essential for evaluating pedestrian network accessibility. Currently, there are no databases specifically designed for training algorithms to assess accessibility for persons with reduced mobility (PRM). Objects of interest in urban environments—such as Curb-cuts, Ramps, doors, and stairs—exhibit significant morphological variability and are often underrepresented in existing datasets.

To address this gap, we undertook to manually annotate a mobile Lidar dataset collected by the Quebec company Groupe Trifide . This dataset, acquired in Victoriaville (QC) using a Trimble MX50 sensor, covers several streets in the city, including Boulevard des Bois-Francs, Rue Notre-Dame, Boulevard Jutras Est and Rue Saint-Jean-Baptiste. The entire survey is divided into 9 point clouds, totaling nearly 137 GB of data and approximately 1.3 billion points. For the purposes of our study, we focused our annotation efforts on Rue Notre-Dame, which presents a variety of accessibility elements and challenges for semantic segmentation. Manual annotation was carried out using Cloudcompare software, which allows a semantic label to be assigned to each point in the cloud. This laborious process, which required more than a month of work, allowed to create a unique and valuable dataset for the analysis of urban accessibility. The table below presents the characteristics of the annotated dataset, indicating the number of points for each semantic class:



To having our dataset you can directly email to use : mehrdad.hosseini.1@ulaval.ca
