## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See **Deployment** for notes on how to deploy the project on a live system.

```
git clone https://github.com/Gopher-Industries/Nutrihelp
```

### Prerequisites

The project requires Android studio for application to run.

We are using Expo for this application, follow the guide below to install expo


### Installing expo

We first need to make sure we have NodeJs installed

To install NodeJs,go to https://nodejs.org/en/download/ and download the latest version of NodeJs. If you have anLTS release greater than 12 please move to next section.

After you have installed NodeJs, Open the NodeJs Terminal to install Expo.

To install Expo
```
npm install -g expo-cli
```

For Android Studio, go to https://developer.android.com/studio and download the file. It should be ~1gb.
Do a standard Install of Android Studio.


## Deployment

For a step by step deployment and android walkthrough, please go through the User Manual section in the handover document.
The handover document of T2-2022 and T3-2022 has relevant information about the feature research as well as the steps to login to your GCP account and using Android studio.

After cloning this repo run the following command:
```
npm install
```

After you have installed all the dependencies, to run the application use:

```
npx expo start --android 
```