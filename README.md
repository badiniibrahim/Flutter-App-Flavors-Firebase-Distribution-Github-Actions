# Flutter-App-Flavors-Firebase-Distribution-Github-Actions

This repository contains a Flutter application configured with multiple flavors for development, staging, and production environments. It leverages Firebase for distribution and uses GitHub Actions for continuous integration and continuous deployment (CI/CD).

## Features

- Flutter App Flavors: Supports different configurations for various environments.
- Firebase Distribution: Automated distribution of the app to Firebase App Distribution.
- GitHub Actions: CI/CD pipeline to automate testing and deployment.

## Workflows

The repository includes a GitHub Actions workflow that:

- Runs unit tests on each push to the main branch.
- Distributes the app to Firebase App Distribution if the tests pass.

## Getting Started

- Clone the repository.
- Configure the flavors for different environments.
- Set up Firebase for app distribution.
- Push changes to the main branch to trigger the CI/CD pipeline.

## Environment Variables

- FIREBASE_CLI_TOKEN: Your Firebase CLI token for authentication.
- FIREBASE_APP_ID: The App ID for your Firebase project.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
