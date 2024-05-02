# covid_19

We create a StatefulWidget called CovidDescriptionPage.
In the state class _CovidDescriptionPageState, we define a method fetchCovidDescription() to make an HTTP GET request to the COVID-19 API.
In the initState() method, we call fetchCovidDescription() to fetch the COVID-19 description when the widget is initialized.
In the build() method, we display the fetched description in the UI using a Text widget.
We handle loading state with a CircularProgressIndicator until the data is fetched.
In the main() function, we run the app with CovidDescriptionPage as the home page.
## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
