# PiC4YOU - Photo Editor App

## Project Overview
PiC4YOU is a Flutter-based photo editor application that allows users to pick images from their device gallery or take pictures using their camera. The app provides tools to edit images and save them to the gallery (or download them to the web). It supports both mobile and web platforms.

## Features
- **Image Picker**: Choose an image from the gallery or take a picture using the camera.
- **Image Editor**: Edit images with basic operations (e.g., crop, rotate, etc.).
- **Save/Download**: Save the edited image to the device gallery (mobile) or download it to the browser (web).

## Tech Stack
- **Flutter**: Cross-platform framework for building natively compiled applications for mobile, web, and desktop.
- **Dart**: Programming language used to build the app.
- **image_picker**: A package for picking images from the gallery or camera.
- **image_editor_plus**: A package to edit images within the app.
- **image_gallery_saver**: A package to save images to the gallery on mobile.
- **dart:html**: To handle image downloads and camera access in the web version.

## Platform Support
- **Mobile**: iOS, Android (Supports camera and gallery access)
- **Web**: Uses the webcam for image capture and allows image downloads.

## Getting Started

### Prerequisites
To run this app locally, you need to have Flutter installed. If you haven't installed Flutter, follow the official installation guide: [Flutter Installation](https://flutter.dev/docs/get-started/install).
