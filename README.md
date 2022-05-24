
# Streamlit-Project
Overview - 
A basic EDA App using the Streamlit library

Motivation -
My main motivation behind creating this app was to learn the hyped Streamlit library and use it to create a data science web application. The web application displays data of stocks of top 500 companies in the world by ranking. It is very sorted so it can be used for information purposes.

Technical Aspect - 
•	Markdown function to show the introduction to the website in streamlit.
•	we use st.sidebar.header to create a header for user input features where they can select the different sectors and we will put it in the sidebar.
•	@st.cache will cache the data once it's been run and we won't need to run it again and again.
•	load_data will load the data from the wikipedia and then load it into data frame df. Later, group it by sectors using df.groupby function. 
•	line no 32-33 - it will enable user to select the sectors which they want to view from the sidebar. multiselect function will help in selecting from multiple sectors and sorted function will help in segregation of sectors.
•	df_selected_sector stores the sectors selectedn by the users from the sidebars and it is used as a paramter/argument in the dataframe.
•	filedownload custom function helps to download the data into csv format from the website
•	download function will help us to directly download the data from yfinance into 
•	the price_plot is a function which will help us to create plots 
•	slidebar function will display a finite no of companies from a particular sector selected in the sidebar

Screenshots - 
![0](https://user-images.githubusercontent.com/68967217/170130815-94f80d0e-fef9-420a-b6f9-94e7b1e06615.PNG)
![Capture](https://user-images.githubusercontent.com/68967217/170130822-11c1b299-c9b3-4300-b7a6-bbac06d26809.PNG)
