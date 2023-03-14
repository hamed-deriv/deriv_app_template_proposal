# Deriv App Template Proposal

## Introduction

The purpose of this proposal is to provide an overview of the Flutter packages that we have used in our projects and how we plan to create a template for future applications based on these packages.

## Package Overview

### flutter_deriv_api

`flutter_deriv_api` is a package that we have used for connecting to a server, managing connectivity, fetching, and request data in our projects. This package will be used in most parts of our application that require communication with a server.

### deriv_auth

`deriv_auth` is a package that we have used for handling authentication and sign up for users in our projects. While the logic for this package is already in place, we needed to extract the UI from another project as a standalone package.

### flutter_deriv_bloc_manager

`flutter_deriv_bloc_manager` is a package that we have used for managing state in our application using the observer pattern and event bus, as well as the service locator pattern. This package has been useful for managing the flow of data and state within the application.

### update_checker

`update_checker` is a package that we have used for managing application updates in our projects. This package has been useful for ensuring that our app is always up to date.

### analytics

`analytics` is a package that we have used to collect and send analytical information to Firebase in our projects. This package has been useful for tracking user behavior and app usage.

### deriv_chart

`deriv_chart` is a package that we have used for displaying chart data to the user in our projects. Depending on the nature of future applications, this package may or may not be used extensively.

## Creating a Template

To create a template for future applications based on these packages, we plan to first analyze the structure of our existing project and identify reusable components and patterns. We will then create a basic structure for future applications, including pages, components, and services. We also need to create a separate package for the UI components of `deriv_auth` that can be easily integrated into future applications.

To make it easy for developers to use these packages, we will create documentation that includes instructions for how to use the packages, guidelines, and a list of reusable components.

## Conclusion

By creating a template for future applications based on these packages, we can streamline the development process and ensure consistency throughout our projects. These packages provide useful functionalities such as connecting to a server, managing state, and collecting analytics data.
