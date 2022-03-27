# Mixed-Cell Cellular Automata (MCCA) software
   When used for landuse change modeling, Cellular Automata (CA) traditionally assume each cell to be of one landuse type at each time step, ignoring the mixed landuse structures that are often found in land units. Mixed cells, composed of cover proportions of multiple landuse types, can better express the continuous changes of land use, and provide a new perspective for modeling the spatio-temporal dynamics of mixed landuse structures. 
  Simulating landuse change with mixed cells is challenging because mixed-cell CAs are fundamentally different from conventional CAs. We present the first attempt of developing a mixed-cell CA (MCCA). The structure of CA is re-designed based on mixed cells, including the representations of cell state, lattice, and neighborhood. The transition rules are automatically constructed by random-forest regression over historical data and a competition mechanism selects among multiple landuse types at the sub-cell scale. In addition, evaluation methods for both simulation accuracy and similarity of landuse structure are proposed for MCCA. 
  
# Article
The article can be downloaded from the free share link:  
https://authors.elsevier.com/c/1bqTPcUG5IST0  

To cite this paper and software:    
  
Liang X., Guan Q.*, Clarke KC, Chen G., Guo S., & Yao Y., 2021. Mixed-cell Cellular Automata: A new approach for simulating the spatio-temporal dynamics of mixed land use structures. Landscape and Urban Planning, 205:103960. DOI: https://doi.org/10.1016/j.landurbplan.2020.103960.

# More Information
https://xun2018.github.io/
 
# Interfaces
![add image](https://github.com/HPSCIL/Mixed_Cell_Cellullar_Automata/raw/master/pic1.png)
![add image](https://github.com/HPSCIL/Mixed_Cell_Cellullar_Automata/raw/master/pic2.png)
# Running environment
Run MCCA software by double-clicking the exe file 'MCCA V1.0_boxed.exe'. MCCA software can run independently on Windows Vista/7/8/X 64-bit environment, without any dependencies and setup process.
# User manual
Please find the attached PDF file 'User_Manual_MCCA-20191206-Eng.pdf' in the Repository.
# Test data
Please find the compressed file 'Testdata.zip' in the Repository.
# Innovation and advantages 
  The MCCA represents a new breed of geospatial CA models for spatio-temporal dynamics of mixed landuse structures. Also, the MCCA provides a new approach to enable more dynamic mixed landuse modeling to move away from the analysis of static patterns. 
One of the biggest advantages of mixed-cell CA models is the capability of simulating the quantitative and continuous changes of multiple landuse components inside cells, while pure-cell CA models can only simulate the qualitative and discrete change of landuse at the cell level. Therefore, mixed-cell CA models are able to simulate subtle changes in landuse structures caused by minor variations of socio-economic, eco-environmental and political driving factors, providing a detailed perspective for understanding landuse change process.
# Scope of application
  Also, the quantitative and continuous simulations generated by mixed-cell CA models that contain the information for landuse structure in each cell have the potential to help researchers more precisely evaluate the impacts of landuse change on many environment variables, such as air quality, the urban heat island, landscape connectivity, net primary production (NPP) lost, ecological service value, energy consumption and more. Mixed-cell CA models may better support space-time continuous analysis and the quantitative calculation of environment variables. In addition, mixed-cell CA models provide an enabling approach to the simulation of structural changes of mixed land use, as most previous studies focused on the measurement and static analysis of mixed landuse structures and ignored their dynamic evolution. The mixed-cell CA model can simulate the gradual change in land use structures and help the researchers understand how the multiple driving factors interact to generate the future distribution of mixed land use.
# Related open source library
  MCCA was developed purely in the C++ language. The parallel technology of MCCA software is from High-performance Spatial Computational Intelligence Lab @ China University of Geosciences (Wuhan) (https://github.com/HPSCIL). The Random forest technique in our model is from a powerful open source library called Alglib 3.9.2 (http://www.alglib.net/). The linear regression algorithm is from (https://github.com/fengbingchun/NN_Test).The UI of the software is built using a famous open source library Qt 5 (https://www.qt.io/download/). This UI provides a real-time display of dynamic changes of land use in simulation process. Moreover, the using of open source library GDAL 2.0.2 (http://www.gdal.org/) allows our model to directly read and write raster data (.tif, .img, .txt files) that includes geographical coordinate information. 
# Consultation 
If you have technical questions regarding MCCA software, please contact Dr. Xun Liang (liangxun@cug.edu.cn)

# Contact info
High-performance Spatial Computational Intelligence Lab(HPSCIL) (https://github.com/HPSCIL)
School of Geography and Information Engineering, China University of Geosciences, Wuhan, Hubei 430078, China.
For any possible research collaboration, please contact Prof. Qingfeng Guan (guanqf@cug.edu.cn)

