# Unhandled Promise Rejection in React Native

This repository demonstrates a common issue in React Native applications where unhandled promise rejections can lead to crashes, particularly on iOS. The example showcases an app that fetches data from a remote API.  Due to improper error handling, a network error or any other issue during the fetch process causes an unhandled promise rejection that leads to the application crashing.

## Solution
The solution involves improving the error handling within the `useEffect` hook to catch and handle any errors during the data fetching process.  This prevents the application from crashing and provides a more user-friendly experience.