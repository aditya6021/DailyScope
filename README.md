
# DailyScope

Daily Scope is a comprehensive news application designed to keep you informed with the latest updates from various categories such as technology, science, sports, health, business, entertainment, and more. By aggregating news articles from popular sources, Daily Scope provides a convenient platform to browse through a diverse range of topics, all within a single app. Stay up-to-date with breaking headlines and trending stories effortlessly, with Daily Scope delivering curated news content straight to your fingertips.

## Interface 
![1](https://github.com/aditya6021/DailyScope/assets/105545824/05d207f0-47a8-440b-bd70-b41f69130d14)

![3](https://github.com/aditya6021/DailyScope/assets/105545824/156dacf4-fc8d-402d-9c64-5ed1ed6d6314)
![2](https://github.com/aditya6021/DailyScope/assets/105545824/aaeee774-9279-4bcb-9a96-af5487c48ef8)

## Usage


In Daily Scope, you can easily stay updated with the latest news across various categories. Here's how to use the app:

### Browse News Categories

- Scroll through the news categories available in the app, including Sports, Science, Technology, Business, Entertainment, and Health.
- Select any category of your interest by tapping on it.

### View Latest News

- Once you select a category, Daily Scope will display the latest news articles within that category.
- Browse through the articles to stay informed about the most recent developments and events.

### Read Full Articles

- Tap on any news article to read a summary or preview.
- For full access to the article, tap on the "Read Full Article" button.
- Daily Scope will redirect you to the article's source website, where you can read the complete article.
## Technologies and Libraries Used:
- Java: java is  primary programming language that I have  used for the development of this application . 

- Picasso : Picasso is a powerful image loading and caching library for Android. It simplifies the process of loading images from various sources (such as URLs, files, or resources) into ImageView components in Android applications. Picasso Version 2.8 is  used in this  project. 
```bash
  implementation ("com.squareup.picasso:picasso:2.8")
```
- Retrofit : Retrofit is a type-safe HTTP client for Android and Java applications. It makes it easy to consume RESTful web services by converting HTTP API calls into Java interfaces. Version 2.11.0 is  used in this  project.
```bash
  implementation ("com.squareup.retrofit2:retrofit:2.11.0")
```
- Retrofit Gson Converter 2.11.0: Retrofit Gson Converter is an extension library for Retrofit that facilitates serialization and deserialization of JSON data using Gson. It seamlessly integrates Gson, a JSON parsing library, with Retrofit, allowing you to convert JSON responses from API calls into Java objects and vice versa.
```bash
   implementation ("com.squareup.retrofit2:converter-gson:2.11.0")
```


## API Service used 
### newsapi.org: 
About News API: [News API](https://newsapi.org) is a simple HTTP REST API for searching and retrieving live articles from all over the web. 
You can search for articles with any combination of the following criteria:

- Keyword or phrase. Eg: find all articles containing the word 'Microsoft'.
- Date published. Eg: find all articles published yesterday.
- Source domain name. Eg: find all articles published on thenextweb.com.
- Language. Eg: find all articles written in English.
You can read full documentation Of News API  [here](https://newsapi.org/docs).

 **Usage**: The NewsAPI key is used to fetch news articles across various categories such as sports, technology, business, entertainment, health, and more, from different countries.
#### Urls used :
- To fetch news by categories 
```bash
  https://newsapi.org/v2/top-headlines?
  country=in&category="+category+"&apikey=933a8e68dbc94c11b157402db81bbccd

```
- Base Url
```bash
  https://newsapi.org/
```




