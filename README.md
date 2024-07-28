# iox-brunei-demo

This Android sample app demonstrates how to use state-of-the-art generative AI models (like Gemini) to build AI-powered features and applications. It includes both gnerative AI SDK for prototyping (branch : `feat-genai-template`) as well as VertexAI Firebase SDK (branch : `feat-firebase-vertexai` ) for production-grade applications.

### Prerequisites
This guide assumes that you're familiar with using Android Studio to develop apps for Android.

Make sure that your development environment and Android app meet the following requirements:

* Android Studio (latest version or Ladybug canary)
* Your Android app must target API level 21 or higher.

### Gemini API Setup

Google AI Studio Key (for prototyping)

* Get API Key by following [this guide](https://ai.google.dev/tutorials/setup) from Google AI Studio
* Add `apiKey=YOUR_KEY` in `local.properties`
* Follow complete guide here for [Quickstart: Get started with the Gemini API in Android apps (client SDK) ](https://ai.google.dev/tutorials/android_quickstart)

Gemini API using the Vertex AI for Firebase SDK  (for production-grade VertexAI powered Applications)

* Setup a irebase project and connect your app to Firebase by following [this guide](https://firebase.google.com/docs/vertex-ai/get-started?platform=android#set-up-firebase)

### Running the sample

#### From Android Studio

* File -> New -> Import Project -> Specify the root `iox-brunei-demo` folder.
* Choose the app from the run configuration dropdown list.
* Click Run.

### Features
This sample showcases the following API capablilites:

- Prompts
- Function Calling
