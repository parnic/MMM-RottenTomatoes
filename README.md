# Module: Rotten Tomatoes
The `MMM-RottenTomatoes` module is designed to, without any API keys, show movies that are ranking at the box office, opening this week, or coming soon. For each movies the Rotten Tomato meter score is shown (if available) as well as release date or box office gross.

Example:

![Full](images/example.jpg) 

## Dependencies / Requirements

Please run `npm install` from the MMM-RottenTomatoes module directory inside your Magic Mirror installation directory.

## Operation

This module is straight-forward to use and requires no special configuration other than standard Magic Mirror positioning. 

Optional configurations are available, see below for more.

## Configuration options

The following properties can be configured:

|Option|Description|
|---|---|
|`showHeader`|Boolean value, should a header be shown. If true, will show "Rotten Tomatoes".<br><br>**Example**: `false`<br>**Default value:** `true`<br>This value is **OPTIONAL**|
|`showBoxOffice`|Boolean value, should the box office section be shown.<br><br>**Example:** `false`<br>**Default value:** `true`<br>This value is **OPTIONAL**
|`showOpeningThisWeek`|Boolean value, should the movies opening this week section be shown.<br><br>**Example:** `false`<br>**Default value:** `true`<br>This value is **OPTIONAL**
|`showComingSoon`|Boolean value, should the movies coming soon section be shown.<br><br>**Example:** `false`<br>**Default value:** `true`<br>This value is **OPTIONAL**
|`limitBoxOffice`|The number of movies to be shown in the box office listing. Setting to zero will show all available.<br><br>**Example:** `4`<br>**Default value:** `3`
|`limitOpeningThisWeek`|The number of movies to be shown in the opening this week listing. Setting to zero will show all available.<br><br>**Example:** `4`<br>**Default value:** `3`
|`limitComingSoon`|The number of movies to be shown in the coming soon listing. Setting to zero will show all available.<br><br>**Example:** `4`<br>**Default value:** `3`
|`boxOfficeAfter`|Boolean value, should the box office listing be shown after the opening this week / coming soon sections. If set to false will be shown before.<br><br>**Example:** `false`<br>**Default value:** `true`
|`mergeOpeningAndComingSoon`|Boolean value, should the opening this week and coming soon sections be merged or seperate.<br><br>**Example:** `false`<br>**Default value:** `true`<br>This value is **OPTIONAL**
