A new Flutter project - CICD Pipeline with GitHub Actions.

## Getting Started

Consider a scenario where you’re developing a Flutter app and want to automate testing and building using GitHub Actions:

- Triggering reason set
    - pull-request
    - push
- Job Set
    - build
        - set os
        - steps
            - Checkout repository
            - Setup Java
            - Setup Node
            - Setup Flutter
            - Install Dependencies
            - Flutter Test
            - Run Flutter App
            - Build APK
            - Build AAB
            - Build IPA
            - Upload Artifact
            - Retrieve the Current App Version from pubspec.yaml file
            - Create Release with adding app version number to the release repo
                - Add release Note
            - Send mail to the QA Team with Release Note
