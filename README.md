# nextflow_flutter_google_signin

## Getting Started

### Firebase project setting

> you don't need to setup **google-services.json** except you need to access those services

1. Don't forget to add SHA1 key to Firebase project, or you will found **ApiError: 10**

<img width="1091" alt="2022-05-16_20-30-35" src="https://user-images.githubusercontent.com/85179/168604560-9217aab4-839d-4a38-8334-8070014f1e07.png">


   1. Go to firebase project's dashboard 
   2. Get into **Android app setting** 
   3. Add your SHA certificate fingerprints (you can get from [running these commands in project's directory](https://stackoverflow.com/questions/51845559/generate-sha-1-for-flutter-react-native-android-native-app)

2. Provide support email, or you will face **[APIError: 12500](https://stackoverflow.com/questions/47632035/google-sign-in-error-12500)**

<img width="867" alt="2022-05-16_20-30-07" src="https://user-images.githubusercontent.com/85179/168604421-ee9e9b26-a77b-43b0-97a1-f83073e8dada.png">
