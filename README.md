# DLNN For Contrail Avoidance Assessment (DCAA)

<br>

DAEN690 - 009 <br> 
Team Data Freaks: Poojitha Nagulapati, Sarfraaz Shahul Hameed, Akhil Madasu, Sriven Sachit Kallepally, Venkat Sai Mudiraj Chintala.<br>

### Abstract

This research endeavor is motivated by the growing concern regarding global warming. Contrail formation, especially the formation of cirrus clouds known as Ice Super Saturated Regions (ISSR), has been pinpointed as a contributing factor. These clouds possess the ability to reflect energy radiated from the Earth's surface, resulting in an elevation of surface temperatures. The aim of our project, therefore, is to forecast and identify contrails in the sky, harnessing the capabilities of machine learning algorithms. The significance of employing machine learning techniques cannot be overstated, as they play a pivotal role in the groundbreaking predictive methodology introduced in this project. A pioneering predictive approach utilized in this project encompasses the use of machine learning algorithms, including deep neural networks. We utilized Roboflow for our Image Classification and training. In this process, we annotated the sky images and subsequently trained them using Roboflow's model. This model predicts the presence of contrails in the images based on the provided training and testing data. This ensures precise and efficient contrail detection, providing a deeper insight into their environmental implications. Ultimately, our project approach involves predicting contrail formation in the sky to detect ISSR and adjusting flight paths to avoid these regions.

### Project Background

The CATSR project is focused on examining the environmental effects of contrails caused by aircraft engine emissions in the lower stratosphere (Kaercher., 2018). The several types of contrails studied in this project include cirrus, long-lasting persistent, and short-lived contrails. These groups show variations in their outward appearance, time spent existing, and the atmospheric circumstances that allowed them to form.

 
The study also explores the part that contrails play in causing global warming (Sherry., 2020). It focuses on how contrails affect radiative forcing, whereby they exacerbate the greenhouse effect by trapping more heat than it reflects. The percentage of human-caused global warming attributable to contrails is another goal of this paper (Kaercher., 2018).
Furthermore, the study mentions the flight-shame movement, which aims to reduce air travel and the carbon emissions it produces. It also discusses the difficult task of locating environmentally suitable aircraft fuel sources, taking into account the significant environmental impact of conventional aviation fuels (Reed, B., 2020, January 17).
The report looks at ways to reduce contrail generation as potential treatments. One method that holds promise is the use of jet fuel made from biomass, which may help to cut soot emissions (Reed, B., 2020, January 17). The report also explores the idea of avoiding flight paths through areas with excessive ice to reduce contrail generation (Fred Pearce., 2019, July 18).
In conclusion, the CATSR project thoroughly investigates the many facets of contrails, their ecological ramifications, and workable solutions to lessen their environmental effects.

### Problem Statement

The distinction between the energy that the Earth absorbs and the energy that it emits is relevant to the concept of radiative forcing. Radiative forcing can appear in two different ways: positively and negatively. Surface temperatures are increased by positive radiative forcing, which contributes to global warming, whereas surface temperatures are decreased by negative radiative forcing (Kaercher., 2018).
The Ice-Supersaturated Region (ISSR) is the geographic area where contrails produce cirrus clouds. Contrails within ISSRs produce clouds that have a dual effect: they reflect solar energy while also entangling energy released by the Earth.

### Project Objective

.To build an ML algorithm which predicts the presence of contrails in the sky. <br>
.To build a dashboard with the charts generated comparing the data collected from IGRA Weather Balloons. <br>



### About the Files Attached to the GitHub

. IGRA Data Set which has the weather details downloaded from the IGRA website.<br>
. Sky Image data (3).xlsx - Has the data about the Sky Images on the number of contrails present, % cloud cover, date and time.<br>
. Sort.ipynb - Renaming and sorting of the images using Python Code.<br>
. Prediction.ipynb - Using the trained Roboflow ML code with python, built GUI tool for Image prediction.<br>
. Contrail Dashboard_Data Freaks.pbix - Power BI file that contains the dashboard for analysis and visualization.<br>
. Sky Image Dataset - https://photos.app.goo.gl/Kvn1T2FSNLor9R5p8.<br>

### Tool/algorithm that used for the project
Roboflow
Power BI

### Solution Approach

<img width="853" alt="image" src="https://github.com/PoojithaNagulapati/DAEN690-Team-DataFreaks/assets/144862312/d0dfc5d0-edac-447e-8f31-bdd658545904">


### Rectangular Annotation

Rectangular annotations were used in the first annotation strategy since the majority of computer vision models support this format. It's essential to remember that, despite their widespread acceptance, rectangular annotations could not offer the maximum degree of accuracy when contrasted with polygon annotations. Rectangular annotations allow the model to learn everything inside the rectangle, which usually leads to a reasonably good accuracy with some error margin. Rectangular annotation-trained models have a tendency to be more generalist in nature, exhibiting excellent accuracy in detecting items with minute differences.

### Polygon Annotation


 
The primary benefit of using custom annotations for contrail detection lies in the enhanced accuracy they offer to machine learning models. Custom annotations, such as polygons, prove particularly advantageous when dealing with objects that lack a clearly defined or rigid structure. This approach allows for a higher degree of model fine-tuning, facilitating the detection of concealed structures within cloud formations, thereby broadening the model's capabilities.

<img width="374" alt="image" src="https://github.com/PoojithaNagulapati/DAEN690-Team-DataFreaks/assets/144862312/67c08cc3-8019-4528-a59c-42a683d5dd15">

### GUI Tool for Sky Image Prediction <br>

<img width="470" alt="image" src="https://github.com/PoojithaNagulapati/DAEN690-Team-DataFreaks/assets/144862312/aa58c089-19f3-4ff4-a286-2967d1bd30c3">

The final product of our findings is the prediction GUI. The contrail prediction GUI offers an intuitive interface equipped with buttons, input fields, and information displays to streamline contrail detection tasks. Its user-friendly design allows for various functions like predicting contrails in newly added images or in the entire selected directory, along with the option to export prediction results. Users can customize contrail detection by setting a confidence threshold via an input box. The GUI generates a comprehensive summary, displaying images with highlighted contrails or overlays indicating detected areas. It also presents a summary table detailing filenames, contrail detection outcomes, confidence levels, and prediction times. This interface ensures a seamless user experience by providing status messages for successful actions or encountered errors. Developed using frameworks like Tkinter in Python, it interacts with the contrail prediction model, processes user inputs, and showcases relevant outputs, enhancing the usability and efficiency of contrail prediction tasks.<br>

<br>

### Dashboard

This is the visual representation of our dashboard, for more details please refer to Contrail Dashboard_Data Freaks.pbix file.

![WhatsApp Image 2023-11-28 at 6 29 22 PM](https://github.com/PoojithaNagulapati/DAEN690-Team-DataFreaks/assets/144862312/6c4a9501-7ba5-46d1-8986-9d7abcaf7e89)



If you have any questions, please contact us via email.

pnagulap@gmu.edu <br>
sshahulh@gmu.edu <br>
amadasu@gmu.edu <br>
vchintal@gmu.edu <br>


