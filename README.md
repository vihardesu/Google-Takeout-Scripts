# Human-Data-Point
###### Overview: This is a jupyter notebook that creates CSV files of your personal data collected by Google. You can access your raw personal data in a zip file from Google at https://takeout.google.com/settings/takeout?pli=1

###### Your data may include: Chrome Browsing History, Location History, Google Search History, Youtube History, Clicked Advertisements, Searched Images on Google Images, Searched Locations & Directions on Google Maps

##### Usage
###### Your folder should look like this...

- YOUR_FOLDER_NAME
   - footprinting.ipynb

###### Place your Google Takeout Zip File in the same folder
###### Run footprinting.ipynb with jupyter notebook

###### Your folder should now look like this:

- YOUR_FOLDER_NAME
    - footprinting.ipynb
    - YOUR takeout.zip file from Google
    - Takeout
      - unzipped Takeout File
    - Preprocess
        - chromeHistory.html
        - clickedAdsHistory.html
        - googleSearchHistory.html
        - imageSearchHistory.html
        - Labeled places.json
        - Location History.json
        - mapsSearchHistory.html
        - MyActivity.html
        - Profile.json
        - videoSearchHistory.html
        - youtubeHistory.html
    - Raw
        - chromeHistory.csv
        - clickedAdsHistory.csv
        - googleSearchHistory.csv
        - imageSearchHistory.csv
        - mapsSearchHistory.csv
        - videoSearchHistory.csv
        - youtubeHistory.csv
