# Meal Planner

A simple, web-based meal planning application. Each `Meal` consists of one or more `Dish` which are grouped by `DishType` (e.g. Main, Starch, Vegetable, Dessert).
This way, you can ensure each Meal this week is covered.

## Features:
- Recipe history
- User defined dish types and categories
- Calendar views

## Uses
- [Grails 3.1](http://docs.grails.org/3.1.x/)
- [FullCalendar](https://fullcalendar.io/)


## Installation
The easiest way to install most binaries on OS X is via [Homebrew](http://brew.sh/) and [SDKMAN](http://sdkman.io/).

 - Java 8: Download the latest [JDK 8](http://www.oracle.com/technetwork/java/javase/downloads/index.html)
 - Grails 3.1.12: `$ sdk install grails 3.1.12`
 - Gradle (latest): `$ sdk install gradle`
 - Groovy (latest): `$ sdk install groovy`
 - PostgreSQL: `$ brew install postgresql`


## Usage

Run the application with Gradle. This also calls the `clientRefresh` task to build client-side dependencies
```
./gradlew bootRun
```

Refresh the client side dependencies after updating them in  `build.gradle`
```
./gradlew clientRefresh
```

## Contributing
View [CONTRIBUTING.md](CONTRIBUTING.md)

## License
TODO: Write license