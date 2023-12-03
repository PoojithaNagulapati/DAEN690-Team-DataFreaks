# DAEN690-Team-DataFreaks

## DLNN For Contrail Avoidance Assessment (DCAA)

### Abstract

This research endeavor is motivated by the growing concern regarding global warming. Contrail formation, especially the formation of cirrus clouds known as Ice Super Saturated Regions (ISSR), has been pinpointed as a contributing factor. These clouds possess the ability to reflect energy radiated from the Earth's surface, resulting in an elevation of surface temperatures. The aim of our project, therefore, is to forecast and identify contrails in the sky, harnessing the capabilities of machine learning algorithms. The significance of employing machine learning techniques cannot be overstated, as they play a pivotal role in the groundbreaking predictive methodology introduced in this project. A pioneering predictive approach utilized in this project encompasses the use of machine learning algorithms, including deep neural networks. We utilized Roboflow for our Image Classification and training. In this process, we annotated the sky images and subsequently trained them using Roboflow's model. This model predicts the presence of contrails in the images based on the provided training and testing data. This ensures precise and efficient contrail detection, providing a deeper insight into their environmental implications. Ultimately, our project approach involves predicting contrail formation in the sky to detect ISSR and adjusting flight paths to avoid these regions.

### Dataset

Our dataset for this project is the images taken from the sky over a specific area during a specific time for several periods of time. The process of picturing the sky is happening often, but we only choose several time periods. The dataset was made by the images which we need to transform into data using the image processing algorithms. The dataset was the image of the sky which was taken for every hour. This is taken to discuss and analyze the traffic controls and to detect the contrail formation. The dataset we planned to create will have the time, date, presence/absence of contrails, altitude of contrails, temperature of the area at the time of contrails, and altitude. These are the data that we have to render from the images.
The future work with the datasets will be on further procedures.

Field Description

Sky Images:
•	Pictures:
Type: Image, The dataset consists of 4234 images currently, it can be altered accordingly. A picture of the sky is taken every hour to verify the presence of contrails. The pictures of the sky are taken and stored in Google Drive by which we can access the images.

Sky Images spreadsheet:
•	Day:
Type: String, The day the picture was taken.
•	Month:
Type: Int, The month the picture was taken.
•	Year:
Type: Int, The year the picture was taken.
•	Hour:
Type: Int, The hour of the image was taken.
•	Presence of Contrails:
Type: String, To indicate whether the contrail is present or not.
•	Short-lived contrails:
Type: Binary, To count the short-lived contrails.
•	Long-lived contrails:
Type: Binary, To count the long-lived contrails
•	Count of Cirrus clouds:
Type: Int, The numbers count the number of cirrus contrails that transform into clouds.

Integrated Global Radiosonde Archive (IGRA) Data (Bruce., 2016):
•	Temperature:
Type: Int, The temperature in Fahrenheit at the time the image was taken.
•	Humidity:
Type: Float, The relative humidity percentage at the duration of the image taken. 
•	Wind Direction:
Type: Int, The direction of the wind.
•	Wind Speed:
Type: Float, The speed of the wind in miles per hour.
•	Latitude:
Type: Float, The latitude location of where and which direction the image was taken.
•	Longitude:
Type: Float, The longitude location of where and which direction the image was taken.
•	Altitude:
Type: Float, The height of the contrails is in meters.
•	Pressure:
Type: Float, The pressure at the time of image taken.
