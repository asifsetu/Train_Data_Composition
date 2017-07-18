# Train_Data_Composition
Please install python and pip first then install requirement.txt to run the programme. When all the required programme 
will be installed then just hit http://127.0.0.1:8000/ in web browser and the webpage will show you the Train Composition. 
Thanks in advance for viewing. 

***The page is integrate digitrafic.fi JSON API's. from https://rata.digitraffic.fi/api/v1/live-trains?station=SLO 
to get a list of trains passing by a station. 
***Train compositions can be fetched from https://rata.digitraffic.fi/api/v1/compositions/960?departure_date=2017-05-02

***You can find the HTML file in the below location:
/TrainComposition/apps/templates/home.html
***You can find the base HTML file in the below locaion:
/TrainComposition/templates/base.html
***You can find the live JSON data fached in the below location in views.py file:
/TrainComposition/apps/views.py
