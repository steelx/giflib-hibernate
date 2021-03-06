# gif.lib
This application is used in the Spring with Hibernate Treehouse course. The app was originally built in the Spring Basics course, and its functionality is extended in the following ways:
 
- Adds persisted data, using an H2 database
- Manages data with Hibernate

What this app does:

- Serves dynamic web content according to URI, including index and detail pages for categories and GIFs
- Includes database connectivity, where GIF data is stored
- Allows a user to perform CRUD (create, read, update, delete) operations on GIF and category data
- Performs server-side form validation for adding/updating GIFs and categories
- Uses a database
- Serves static assets, such as images, fonts, CSS, and JS

What this app does **NOT** do:

- Implement user authentication

## gradle
`./gradlew bootRun`

### clean
`./gradlew clean`

## H2 TCP Local Server
`java -cp h2-1.4.197.jar org.h2.tools.Server`