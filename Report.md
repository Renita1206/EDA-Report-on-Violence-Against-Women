# MahilAI-Datathon-2021
Data Analysis to combat violence against women

## General Observations
![image](https://user-images.githubusercontent.com/66276711/139733541-f2efcd3d-90a5-44e7-81ca-bec056bfadf5.png)  
- It can be seen that the most common form of crime is domestic violence followed by outrage to modesty, kidnapping and rape
- Importation of girls is the least common form of crime    

![image](https://user-images.githubusercontent.com/66276711/139735431-34b1b78b-6c08-48f5-bd9f-63dcbc6dc0e7.png)  
- It is seen that the number of crimes is increasing in India from the year 2011 to 2014  
  
  
## Task 1
![image](https://user-images.githubusercontent.com/66276711/139735467-f1e51dde-762a-48ec-8cf0-30bcc64dfdb4.png)  
- It is seen that the highest number of crimes is reported in West Bengal followed by Uttar Pradesh, Rajasthan and Madhya Pradesh
- Lakshwadeep is seen to have the least number of crimes reported
- However, this dataset does not account for the population of each state and hence the crime rates cannot be calculated or compared  

![image](https://user-images.githubusercontent.com/66276711/139735924-fe657ade-1fb7-4428-a617-21c6731b3c0e.png)

- The crime trend is seen to increase steeply in most states in India including West Bengal, Lakshwadeep and Karnataka    

 ![image](https://user-images.githubusercontent.com/66276711/139735594-b092e21e-981b-4a41-9dcd-02980e14e1b6.png)  
   
- The crime trend in Andhra Pradesh shows a peculiar trend. The number of reported crimes halves from 2013 and 2014, shown by a sharp dip in the crime trenc graph. On further investigation it was revealed that the state of Andhra Pradesh was split into Andhra Pradesh and Telengana which causes the sharp dip in the number of crimes.
  
    
     
## Task 2
![image](https://user-images.githubusercontent.com/66276711/139734868-7a61c01e-c578-476e-bc91-7874ddc835c6.png)
- The safety index was calculated for each district in India
- The safety index was calculated by taking a weighted sum of the number of crimes. The more common the crime, the less the weight assigned to it. Importation being the least common is assigned the highest weight while domestic violence being the most common is given the least weight.
  
    
    
## Task 3
- It is seen that the safety index shows a gradual decrease in safety index over the years
- The model predicts the same
- A linear regression model is used to predict the safety index based on district and year
