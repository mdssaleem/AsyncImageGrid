# Image Grid

A Swift project that displays a 3-column square image grid. The images are center-cropped and loaded asynchronously from an API. The implementation includes caching mechanisms and error handling for efficient and robust image loading.

## Features

- **3-Column Square Image Grid**: Displays images in a 3-column grid layout with center-cropping.
- **Asynchronous Image Loading**: Loads images asynchronously from a specified API.
- **Scroll Through 100+ Images**: Allows scrolling through at least 100 images.
- **Caching Mechanism**: Uses both memory and disk caching for efficient image retrieval.
- **Error Handling**: Handles network errors and image loading failures gracefully with informative error messages or placeholders.

## API Details

Images are loaded from the following API URL:

imageURL = domain + "/" + basePath + "/0/" + key


## Requirements
- Swift
- iOS 13.0+
- Xcode 11+


## Result



<img width="359" alt="Screenshot 2024-05-09 at 12 21 22 PM" src="https://github.com/mdssaleem/TaskApp/assets/32189409/29fab559-2703-4425-a445-6e2041be9d1f">
