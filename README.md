# Popular Movies
Implementation of the Popular Movies App project for the Udacity Android Developer Nanodegree

********

## The Movie Database
This project uses The Movie Database API to get information about movies. 
In order to build this project, an API key must be provided.
This project is configured to create a build config field and a string resource value by reading 
the property **PopularMovies_MDB_API_KEY** from the user's **_gradle.properties_** file.

Your gradle user properties file (**_gradle.properties_**) can found in the **_.gradle_** folder:
* **Windows**: `C:\Users\<Your username>\.gradle`
* **Mac**: `/Users/<Your username>/.gradle`
* **Linux**: `/home/<Your username>/.gradle`

You need to set the property to your v3 auth API key.
i.e. `PopularMovies_MDB_API_KEY="YourAPIKeyHere"`

Check out this Medium post for more information about setting user properties: 
[Hiding API keys from your Android repository](https://medium.com/code-better/hiding-api-keys-from-your-android-repository-b23f5598b906)

To get an API key for The Movie Database, sign up for account at the [The Movie Database](https://www.themoviedb.org/) website.
After signing up for an account you can request an API key by going to your account **Settings** 
and clicking on **API**. This app uses version 3 of the API so you need the API key labeled as 
**API Key (v3 auth)**.
