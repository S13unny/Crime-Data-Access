# Crime-Data-Access
A method to search for all types of crime recorded by the government within a given month and within a triangular 3 co-ordinate area.


This is not the most robust code in the world so keep in mind some tinkering maybe recquired in your area
This code works by accessing the UK Government API and therefore doesn't work internationally. Also the government only holds data for the past three years not including the current month. For example at the time of writing it is March 2019 so data is accessible from February 2016 to February 2019.
Due to limitations on how the API lets indivduals access the data the program is particualrly slow as each location in the specified region will have to be accessed indivdually. Therefore this may be impratical for large areas. Typically a city sized area will take a moderate amount of time so i would advise not exceeding that range.
If a crime hasn't occured in any of the three points in the first 6 months of the year you are searching for then no data boundaries will be returned. Therefore consider widening the search parametres for this code (v) to a larger value (up to 10). This will increase runt time but will more reliably return the data for the area you are searching for.

This code is open for anyone and everyone. Please feel free to use as you please.
