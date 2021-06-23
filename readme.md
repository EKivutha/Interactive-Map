

## How to use it ?
* Upload a `.csv` file which contain dataset. The uploaded `.csv` must be according to the format specified at `data.csv` located in `server/data` directory. 
For greater insight about dataset you may visit [here](https://www.kaggle.com/c/predicting-cab-booking-cancellations/data) 
Apart from uploading your own dataset you can also proceed by clicking `USE DUMMY DATA` button.
<p align="center">
  <img src="https://github.com/gerkibz/Interactive-Map/blob/master/upload.PNG" width="800">
</p>


* After uploading the suitable `.csv` file. Your screen would seem quite similar to as shown below. 
You may click `SHOW CHARTS` button (located in top right corner) in order to see the charts.
<p align="center">
  <img src="https://github.com/gerkibz/Interactive-Map/blob/master/first_preview.PNG" width="800">
</p>


* After you'll clicked the button. You can also filter content by clicking on individual bars. 
Now in case you wish to revert back to unfiltered state, you can do that by clicking the `UNDO` button (located below `SHOW CHARTS` button).
<p align="center">
  <img src="https://github.com/gerkibz/Interactive-Map/blob/master/filtered_preview.PNG" width="800">
</p>


## How to run it locally ?
In order to run this project in your machine you first need to create a Mapbox account and grab Access Token. 
Then you need to paste it in `map.js`. After doing it you can run app locally using three commands that are shown below.
* `npm install` : It would install all the necessary packages
* `npm run dev` : It would run development server for our React Frontend. 
* `npm start`   : It would run node server for our Backend.

