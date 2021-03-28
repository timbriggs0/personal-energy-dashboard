# Personal Energy Dashboard
A project using  the ashrae energy prediction dataset to understand and develop models to see how weather effects building performance, and Heroku Servaces to explore user interactions with data.

Future thoughts would be to merge this dataset with one that links building efficency with internal temperatures and comfort of those that inhabit the buildings.

### :open_file_folder: File Structure 
personal-energy-dashboard<br/>
└──:open_file_folder: data<br/>
|&nbsp;&nbsp;&nbsp;&nbsp;├──:open_file_folder: ashrae-energy-prediction<br/>
|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;├── building_metadata.csv<br/>
|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;├── test.csv<br/>
|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;├── train_clean.csv<br/>
|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;├── train.csv<br/>
|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;├── weather_test.csv<br/>
|&nbsp;&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;&nbsp;└── weather_train.csv<br/>
|&nbsp;&nbsp;&nbsp;&nbsp;|<br/>
|&nbsp;&nbsp;&nbsp;&nbsp;├── data_cleaning.ipynb<br/>
|&nbsp;&nbsp;&nbsp;&nbsp;└── data_exploration.ipynb<br/>
|<br/>
├──:open_file_folder: design<br/>
|<br/>
├── .gitignore<br/>
└── README.md<br/>

## Work Log
3/28/2021: worked on data exploration and cleaning. started creating a function that removed outliers based on the average slope of the past inputs to help clean out bad data. Also began merging weather with building performance to see if there are any connections.

## Dashboard Design
All design files including sketches and working files are included in the design folder.