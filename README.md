# JAL

This is a project based on Water Quality Analysis and Prediction using Machine Learning. We have a website [JAL](https://main-production-5602.up.railway.app/) which describes about our project.

## About Project

Our project 'JAL' is made to find out the different parameters which have a significant impact on the surface water quality. These parameters could be either the one using which the Water Quality Index (WQI) is calculated or those which negatively impacts on water quality. We performed Data Analysis on all the Indian States and Delhi(UT). There are different graphs present in our website which are directly or indirectly related to the water quality. The website also has a model deployed in it using which any user can calculate the WQI. Its evaluating paramenters are Dissolved Oxygen Saturation (%), pH, Biological Oxygen Demand, Temperature, Phosphate, Nitrate, Turbidity, and Total Solids. The value ranges from 0 to 100, where 100 is the best or ideal water quality.

The WQI values also specify their usage as well, below is the range of values and their uses

* WQI Values (0 to 25): Poor    
* WQI Values (26 to 50): Fair    
* WQI Values (51 to 70): Average    
* WQI Values (71 to 90): Good    
* WQI Values (91 to 100): Excellent

Uses: [Criteria and Uses](https://cpcb.nic.in/water-quality-criteria/)

### Tool and Technologies

* **Python:** It was used for data analysis and creating the machine learning model.
* **Tableau:** We used Tableau public for data visualization and to use some of its exceptional features.
* **Nodejs:** For backend development of the website.
* **Express:** This Nodejs web application framework is used for building web applications. 
* **Flask:** It helps in ML model implementation in a web application.
* **MS Excel:** For Data Cleaning and EDA.

## Running the project

For running it on local machine users can download the zip file and see the required dependencies to be installed in order to run the project. Before running it on local machine it's recommended to first run the ML model file "wqmodel.py" and then run the "app.py" file. Whereas, if a user just want to see the running website they can go to this link [JAL](https://main-production-5602.up.railway.app/) which describes about our project.

## Using the project

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change. Below are some of the screenshots of our website.

![JAL Homepage](https://github.com/Healthy-Sip/JAL/blob/main/Images/Homepage.jpeg)

![Model Webpage](https://github.com/Healthy-Sip/JAL/blob/main/Images/Model.jpeg)

## Credits 

This project is made by our group "JAL" and the team members are 

* **Arsh Chandrakar** - Worked on Data Analysis and creating the ML model.
* **Aryan Dubey** - Worked on the backend and deployment of the website.
* **Rishi Nayak** - Worked on the frontend and designing of the website.

Here are some reference materials which we used:
1. [Research Paper](https://www.researchgate.net/publication/274460102_Water_Quality_Status_of_Ciambulawung_River_Banten_Province_Based_on_Pollution_Index_and_NSF-WQI)
2. [Datasets](https://data.gov.in/catalog/surface-water-quality)
3. [Water Quality Criteria](https://cpcb.nic.in/water-quality-criteria/)
4. [What is CEPI?](https://cpcb.nic.in/comprehensive-environmental-pollution-index-cepi/)

## License

[MIT](https://choosealicense.com/licenses/mit/)
