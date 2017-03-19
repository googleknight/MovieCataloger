# MovieCataloger
> Movie Cataloger is a cataloging and organizing software developed for personal use only.
> It will help the user to maintain their movie collection efficiently in an organized way.
> It is capable to scan and search recursively the desired folders, drives for movies and adds them to catalog.
> It is capable of retrieving movie’s name and other important meta data like, language, runtime, quality etc from the file.
> It have the ability to directly fetch movie data from internet movie database (IMDb) using [OMDB](http://www.omdbapi.com/) API.
> User can see the collection of their movies in a single window despite their actual files located across various drives and folders. 
> User can mark those movies which he/she have watched. They can give a rating for a movie. 
> The data fetched from internet will help user to know more about that particular movie, by showing its poster, IMDb rating, genre, year of release, plot summary, etc like details.
> It can fetch multiple movies information from IMDB at once and user can update movie details of individual movie too.
> User can play that movie, find its location on drive, can search for a particular movie in Catalog.

## Screenshot

<p align="center">
  <img src="https://raw.githubusercontent.com/googleknight/MovieCataloger/master/MovieCataloger/Screenshots/MainWindow.jpg" alt="Screenshot"/>
</p>

## System Requirements
* Any 64-bit Windows OS
* [Java Runtime Environment 64-bit 1.8 or higher](http://www.oracle.com/technetwork/java/javase/downloads/jre8-downloads-2133155.html)

## Instructions to import project in Eclipse
* Download the repo, extract it.
* Create a New Java Project in Eclipse.
* Right Click your project and select Import, then under General choose File System, and then browse and select the extracted folder
* In Package Explorer expand your project and then expand res folder, select all JAR files and add them to Build Path.
* Right Click your Project and go to configure build path and select Libraries tab and add Class Folder and select lib folder in project.
* Run project by MainWindow.java

## Instructions to install the latest build.
* Download the [setup](https://raw.githubusercontent.com/googleknight/MovieCataloger/master/Setup/MovieCatalogerSetup.exe) and follow on screen instructions.
* ### Do not install it in C Drive, there it will not going to work properly.

## Instructions for first time users
* Run the program, and select Scan Folders first, then select Set Folders  and set your folders which contains movies ,not tutorials or tv series.
* Then select Add Movies and wait.
* Connect to internet and select batch update and choose Update selected and wait.
* Then select Update by Filtering movie name.
* Now update rest of the movies individually, and explore the software now. Your Catalog is ready.

## Things that needs to be done in future
* Update movie by giving IMDB ID manually.
* Auto search for new movies in selected folders at boot up of software and asks to add them in catalog.
* Import export database and files.
* Create a new menu item which generates custom view which will shows movies categorized in genre, year, language, country, director wise and generate pie chart of the data.
* Provide a new window to copy movies to another source.
* Write JUnit files for unit testing all methods.
* Make it cross platform compatible.
* Improve regular expression used to retrieve movie name from file name.
* Write an independent API/ mechanism to extract movie details from IMDB, in case OMDB API is not working.
* Improve documentation, add more comments wherever it is required.
* Find new bugs and fix them.
* Imrove design, imporve button names, etc.
* Add new items in menu bar.


#### Contributors are welcomed to contribute to this project, just fork this repo and raise a pull request.
