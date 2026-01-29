# Scale-Prediction_VORTEX-2026

# IoT–Machine Learning Integration for Mineral Scaling Prediction and Handling in Geothermal Operations: A Data-Driven Approach toward Sustainable Geothermal Development in X Field
![Scale Image](https://www.merusoilandgas.com/wp-content/uploads/2019/04/Scaling.jpg)
ref: https://www.merusoilandgas.com/wp-content/uploads/2019/04/Scaling.jpg

## Description
In the energy transition toward Indonesia’s Net Zero Emission target by 2060, geothermal energy plays a strategic role as a reliable baseload energy source supporting national energy security (PT PLN, 2021). Indonesia possesses substantial geothermal potential for both electricity generation and non-electric applications, such as direct heat utilization for industrial processes. However, its development still faces interrelated economic, regulatory, and technical challenges (Prauzek et al., 2023). High exploration and drilling costs reduce investment attractiveness, while regulatory complexity, permitting processes, and land-use issues further affect project feasibility (World Bank, 2019). Technically, upstream geothermal operations consist of exploration, drilling, reservoir development, production injection, and long-term field operation stages. During the exploration phase, the primary challenge arises from geological uncertainty due to geothermal reservoir heterogeneity, which increases exploration risk and cost. Unlike conventional oil and gas systems that are typically located in sedimentary basins with well-defined stratigraphic controls, Indonesia’s geothermal systems are predominantly associated with volcanic arc environments controlled by complex fault structures and extreme temperature gradients (Hochstein & Sudarman, 2008). In the drilling phase, major technical challenges include low rate of penetration (ROP) caused by hard formations, loss of circulation in fractured zones, and lithological uncertainty, making geothermal drilling more focused on geothermal risk management rather than hydrocarbon optimization. During the production and injection phase, mineral scaling and corrosion become dominant issues, leading to production decline and reduced injectivity, which directly impact geothermal recovery factors (Ahmadi & Chen, 2020; Sofyan et al., 2021). Effective mitigation through specialized mechanical methods or chemical inhibition is essential to maintain optimal flow in these harsh environment wells (Sofyan et al., 2025). These challenges are more pronounced than in oil and gas operations because geothermal fluids are multiphase, rich in dissolved minerals, and highly sensitive to thermodynamic changes (Xu et al., 2021).

Nevertheless, geothermal energy retains significant potential as a low-emission, domestically sourced baseload energy. Sustainable utilization strongly depends on improving operational efficiency and reducing technical risks through data-driven and digitalized approaches. The Internet of Things (IoT) enables continuous operational data acquisition through digital sensors installed on production and injection pipelines, particularly to monitor geochemical parameters such as pH and key ion concentrations that influence scale formation (Chen et al., 2020; Huaman Rojas et al., 2025). Real-time visualization and sensor monitoring systems provide critical insights into the early stages of scale deposition and its impact on system integrity (Kim et al., 2019). These data are transmitted in real time to Machine Learning (ML)-based analytical systems to predict mineral saturation indices and scaling tendencies before operational disruptions occur (Al Harrasi et al., 2025; Al-Hajri et al., 2020; Supekar et al., 2018). ML techniques canreveal complex nonlinear relationships between fluid chemistry and pH, thereby supporting proactive mitigation strategies (Yousefzadeh et al., 2023). This study utilizes a dataset This dataset comprised eight real PW samples collected from the Williston Basin Bakken formation in northwestern North Dakota and northeastern Montana, which were analyzed using PHREEQC and the OLI software. Consisting of 2,313 data points,including ionic composition, pH, and mineral saturation indices, to train Gradient Boosting Machine (GBM), Random Forest (RF), Extreme Boosting (XGBoost), and Power Ensemble Learning Model (PLEM). And used a hyperparameter tuning.

## Machine Learning Model Used
1. Gradient Boosting (GBM)
2. Random Forest (RF)
3. Extreme Boosting (XGBoost)

## Required Packages
- numpy
- pandas
- scikit-learn
- xgboost
- shap
- matplotlib

## Reference
Ahmadi, M., & Chen, Z. (2020). Machine learning–based models for predicting permeability impairment due to scale deposition. Journal of Petroleum Exploration and Production Technology, 10(8), 2873–2884. https://doi.org/10.1007/s13202-020-00941-1

Al-Hajri, N. M., Al-Ghamdi, A., Tariq, Z., & Mahmoud, M. (2020). Scale prediction and inhibition design using machine-learning techniques and a probabilistic approach. SPE Production & Operations. https://doi.org/10.2118/198646-PA

Al Harrasi, M. T. S., Kazemi, A., & Yousefzadeh, R. (2025). Ensemble learning for prediction of inorganic scale formation: A case study in Oman. Scientific Reports, 15, Article 21277. https://doi.org/10.1038/s41598-025-05003-2

Chen, F.-L., Yang, B.-C., Peng, S.-Y., & Lin, T.-C. (2020). Applying a deployment strategy and data analysis model for water quality continuous monitoring and management. International Journal of Distributed Sensor Networks, 16(6). https://doi.org/10.1177/1550147720929825

Huaman Rojas, J. J., Asto Bonifacio, R. F., Barreto Peña, J. M., Quincho Leon, D. R., Ramos Peña, C. D., & Povis Torres, K. G. (2025). Sensors and IoT for water quality monitoring: A systematic review of technologies and field validation. Journal of Robotics and Control, 6(6), 2844–2863. https://doi.org/10.18196/jrc.v6i6.28457

Kim, H.-W., Yun, T., Kang, P. K., Hong, S., Jeong, S., & Lee, S. (2019). Evaluation of a real-time visualization system for scaling detection during DCMD and its correlation with wetting. Desalination, 454, 59–70. https://doi.org/10.1016/j.desal.2018.12.014

Prauzek, M., Kucova, T., Konecny, J., Adamikova, M., Gaiova, K., Mikus, M., Pospisil, P., Andriukaitis, D., Zilys, M., Martinkauppi, B., & Koziorek, J. (2023). IoT sensor challenges for geothermal energy installations monitoring: A survey. Sensors, 23(12), 5577. https://doi.org/10.3390/s23125577

PT PLN (Persero). (2021). Rencana usaha penyediaan tenaga listrik (RUPTL) PT PLN (Persero) 2021–2030. https://web.pln.co.id/statics/uploads/2021/10/ruptl-2021-2030.pdf

Sofyan, A., Aka, H. S., Suranta, B. Y., & Ratasya, S. M. A. (2021). Analysis of silica saturation index (SSI), scale formation rate, and scale formation time based on geothermal production wellhead pressure at Well “X”. Indonesian Journal of Petroleum and Mineral, 1(1), 25–32. https://doi.org/10.53026/IJOEM/2021/1.1/15

Sofyan, A., Jaya, R., Susanto, H., Njeru, R. M., Bozsó, G., & Szanyi, J. (2025). Scale treatment planning using the broaching method in a vapor-dominated geothermal Well X at the Kamojang geothermal field. Eng, 6(4), Article 67. https://doi.org/10.3390/eng6040067

Sudarman, S. (2008). History of geothermal exploration in Indonesia from 1970 to 2000. Geothermics, 37(3), 220–266. https://doi.org/10.1016/j.geothermics.2008.01.001

Supekar, O. D., Brown, J. J., Greenberg, A. R., Gopinath, J. T., & Bright, V. M. (2018). Real-time detection of reverse-osmosis membrane scaling via Raman spectroscopy. Industrial & Engineering Chemistry Research, 57(29), 9632–9639. https://doi.org/10.1021/acs.iecr.8b01272

Tayyebi, A., Alshami, A., Tayyebi, E., Owoade, A., Talukder, M. J., Ismail, N., Rabiei, Z., Yu, X., & Tiker, G. (2025). Machine learning–based prediction of scale formation in produced water as a tool for environmental monitoring. Results in Engineering, 26, Article 105223. https://doi.org/10.1016/j.rineng.2025.105223

World Bank. (2019). Indonesia geothermal resource risk mitigation project (GREM). https://documents1.worldbank.org/curated/en/972941569608786496/pdf/Indonesia-Geothermal-Resource-Risk-Mitigation-Project.pdf

Xu, H., Jiao, Z., Zhang, Z., Huffman, M., & Wang, Q. (2021). Prediction of methane hydrate formation conditions in salt water using machine learning algorithms. Computers & Chemical Engineering, 151, Article 107358. https://doi.org/10.1016/j.compchemeng.2021.107358

Yousefzadeh, R., Bemani, A., Kazemi, A., & Ahmadi, M. (2023). An insight into the prediction of scale precipitation in harsh conditions using different machine learning algorithms. SPE Journal. https://doi.org/10.2118/212846-PA
