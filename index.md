## Performing Analysis Of Meteorological Data


In this blog, we will discuss a [Data Analysis](https://www.kaggle.com/muthuj7/weather-dataset) done which is based on the following [dataset](https://drive.google.com/open?id=1ScF_1a-bkHi1qe8Rn78uxK6_5QwUD9Bu).

**“Has the Apparent temperature and humidity compared monthly across 10 years of the data indicate an increase due to Global warming"**


### Following is the Hypothesis for the analysis.
The Hypothesis means we need to find whether the average Apparent temperature for the month of a month say April starting from 2006 to 2016 and the average humidity for the same period have increased or not. This monthly analysis has to be done for all 12 months over the 10 year period. So you are basically resampling your data from hourly to monthly, then comparing the same month over the 10 year period. Support your analysis by appropriate visualizations using matplotlib and / or seaborn library.

### Step 1: Importing of libraries and Dataset

![image](https://user-images.githubusercontent.com/82140149/138288634-2a17f84e-571d-47a2-926c-3400a79e838b.png)

![image](https://user-images.githubusercontent.com/82140149/138288956-f85b8699-6f38-4368-8695-5fc125acffbf.png)


### Step 2: Looking at the dataset.
![image](https://user-images.githubusercontent.com/82140149/138292836-68c40769-6a2a-4566-8a39-f9c574299532.png)


### Step 3: Cleaning Dataset
In this step, we will prepare our data for the plotting for which we will first drop the unwanted columns(all except temperature and humidity).

![image](https://user-images.githubusercontent.com/82140149/138293153-2139fd6d-2164-4313-bd3b-5839066595ad.png)

![image](https://user-images.githubusercontent.com/82140149/138293319-edd786d7-0276-488d-83c3-99dfc85402ad.png)

Then, we will convert the Timezone to +00:00 UTC.

![image](https://user-images.githubusercontent.com/82140149/138293558-5cb38b47-d886-41f3-828a-eaaba1cb10f4.png)


### Step 4: Plotting of data 

Firstly, we will see for a specific month as a example

![image](https://user-images.githubusercontent.com/82140149/138294155-7951b026-893f-4472-8a19-8a7681343981.png)

Secondly, we will plot the whole dataset for all months(together)

![image](https://user-images.githubusercontent.com/82140149/138295093-241c39c7-eda0-4a6c-b0e3-e848c824eb27.png)

Then, we will analyse and plot monthwise


### January

![image](https://user-images.githubusercontent.com/82140149/138403788-2847ef6c-1c25-40a7-9b4b-e68738ff9f4a.png)


### February

![image](https://user-images.githubusercontent.com/82140149/138403863-17aa20f5-440f-478c-bd2b-6ffb0ace5b0f.png)


### March

![image](https://user-images.githubusercontent.com/82140149/138403984-d3b7f439-7a34-4032-a8a0-7aa5f39d50ef.png)


### April

![image](https://user-images.githubusercontent.com/82140149/138404075-6aa3c5d0-3f60-48ec-b612-d4701403a5e7.png)


### May

![image](https://user-images.githubusercontent.com/82140149/138404113-b0d46561-abec-47f9-b8b3-b9032138612b.png)


### June

![image](https://user-images.githubusercontent.com/82140149/138404181-22a45741-0270-4542-928a-786c1b56f641.png)


### July

![image](https://user-images.githubusercontent.com/82140149/138404295-1bf20f2f-99b6-4022-b0b4-b69551be8bbc.png)


### August

![image](https://user-images.githubusercontent.com/82140149/138404399-f2490200-0ec7-4e18-ab27-216f2fd1e434.png)


### September

![image](https://user-images.githubusercontent.com/82140149/138404598-80ea4335-8062-404f-aea3-c8a7289a17c1.png)


### October

![image](https://user-images.githubusercontent.com/82140149/138404680-3f4d61dd-6c9b-4623-99f2-8322ceff6d7f.png)


### November

![image](https://user-images.githubusercontent.com/82140149/138404809-846d0a6c-7854-4617-9ec9-0a934cababf3.png)


### December

![image](https://user-images.githubusercontent.com/82140149/138404914-168d2070-ad41-4783-a8c4-ba8fcd79da4c.png)

### Anlaysis : From the month of April to the month of August, there is slightly change in temperature but nearly no change in humidity for the 10 years(2006-2010). Whereas for the month from September to March there is a vast change in the temperature but again humidity remains unchanged.


### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/sachetutekar/MeteorologicalDataset_Analysis/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Connect me on LinkedIn: [LinkedIn](https://www.linkedin.com/in/sachet-utekar-b23728205/)

You can reach me out via: [E-Mail](Sachet.Utekar@gmail.com)
