# <img src="object-count.svg" alt="Object Count Logo" width="150" style="vertical-align: middle; display: inline;">Object Count - Bug Reports and Feature Requests 

<!-- ![object-count](https://github.com/user-attachments/assets/c1bb1e3d-b866-49ff-86cf-6d30a5c4fed2) -->

Welcome to the Object Count repository. This repository is dedicated to tracking bug reports, feature requests, and improvements for the Object Count web application. This space serves as the primary hub for submitting and discussing issues that can enhance our application.

## Table of Contents
- [Overview](#overview)
- [How to Report a Bug](#how-to-report-a-bug)
- [How to Request a Feature](#how-to-request-a-feature)
- [Issue Guidelines](#issue-guidelines)

## Overview

The Object Count application empowers users to efficiently and accurately count objects in images by harnessing advanced deep learning techniques, such as class-agnostic counting and image segmentation. With the ability to work from just a few reference examples, it delivers rapid and reliable results across a wide range of use cases, including traffic analysis, retail inventory tracking, and industrial process monitoring. This repository serves as the issue tracker where users can:

- Report bugs and unexpected behavior
- Suggest new features
- Propose enhancements to the user interface, performance, or functionality

Please make sure to follow the provided templates and guidelines to help maintainers address the issues or requests efficiently.

## About Object Count - Count Anything

## How to Report a Bug

If you encounter any bugs or issues with the Object Count web application, please first search the [existing issues](https://github.com/aiml-au/objectcount/issues) to see if the problem has already been reported. If not, [click here](https://github.com/aiml-au/objectcount/issues/new?assignees=&labels=&projects=&template=bug_report.md&title=) or follow the steps below to submit a new bug report:

1. Navigate to the **Issues** tab.
2. Click on the **New Issue** button.
3. Choose the **Get Started** next to **Bug Report** option.
4. Provide detailed information in the template:
   - **Description**: A concise description of the issue.
   - **Steps to Reproduce**: Clear and detailed steps that can help replicate the issue.
   - **Expected Behavior**: What you expected to happen.
   - **Actual Behavior**: What actually happened.
   - **Screenshots/Logs**: Include any relevant screenshots or error logs.
   - **Environment**: Information about your browser, device, or any other relevant setup details.
5. Submit the issue, and our team will review and investigate as soon as possible.

### Bug Report Template
```
  **Describe the bug**
  A clear and concise description of what the bug is.
  
  **To Reproduce**
  Steps to reproduce the behavior:
  1. Go to '...'
  2. Click on '....'
  3. Scroll down to '....'
  4. See error
  
  **Expected behavior**
  A clear and concise description of what you expected to happen.
  
  **Screenshots**
  If applicable, add screenshots to help explain your problem.
  
  **Desktop (please complete the following information):**
   - OS: [e.g. iOS]
   - Browser [e.g. chrome, safari]
   - Version [e.g. 22]
  
  **Smartphone (please complete the following information):**
   - Device: [e.g. iPhone6]
   - OS: [e.g. iOS8.1]
   - Browser [e.g. stock browser, safari]
   - Version [e.g. 22]
  
  **Additional context**
  Add any other context about the problem here.
```

<details>
  <summary>Click to see an example bug report</summary>

### Example Feature Request
   
**Describe the bug**

When uploading a photo to the object count application, the app fails to return a result and instead displays an error message: "Image processing failed. Please try again later." This issue occurs consistently with images larger than 5MB.

**To Reproduce**

Steps to reproduce the behavior:
1. Go to the object count application website.
2. Click on the "Upload Photo" button.
3. Select an image file larger than 5MB (e.g., a high-resolution JPEG).
4. Wait for the processing to complete.
5. See the error message instead of the object count result.

**Expected behavior**

The application should process the uploaded image regardless of its size (up to the maximum allowed limit) and return the correct object count.

**Screenshots**

[Error Message Screenshot]

**Desktop (please complete the following information):**

- OS: Windows 10
- Browser: Google Chrome
- Version: 95.0.4638.69

**Smartphone (please complete the following information):**

- Device: Samsung Galaxy S21
- OS: Android 11
- Browser: Chrome Mobile
- Version: 95.0.4638.74

**Additional context**

- The issue does not occur with images smaller than 5MB.
- There is no indication on the upload page about a file size limit.
- Compressing the image to below 5MB allows it to be processed successfully.
- Internet connection is stable, and other applications handle large file uploads without issue
</details>
      
## How to Request a Feature

Do you have an idea that could improve the Object Count web application? [Click here](https://github.com/aiml-au/objectcount/issues/new?assignees=&labels=&projects=&template=feature_request.md&title=) or follow the steps to submit a feature request:

1. Navigate to the **Issues** tab.
2. Click on the **New Issue** button.
3. Choose the **Get Started** next to **Feature Request** option.
4. Provide details in the template:
   - **Description**: A summary of the requested feature.
   - **Use Case**: How the feature will benefit users.
   - **Proposed Solution**: Any ideas on how the feature can be implemented.
   - **Alternatives**: Any alternatives you’ve considered.

### Feature Request Template
```
   **Is your feature request related to a problem? Please describe.**
  Explain the problem you're facing or what you want to solve. 
  What will this feature help with?
  
  **Describe the solution you'd like**
  A clear and concise description of what you want to happen.
  
  **Describe alternatives you've considered**
  A clear and concise description of any alternative solutions or features you've considered.
  
  **Additional context**
  Add any other context or screenshots about the feature request here.
```

<details>
  <summary>Click to see the example feature request</summary>
   
### Example Feature Request

**Is your feature request related to a problem? Please describe.**  

The object count application currently only supports single object types for counting (e.g., only counting one category such as cars, people, etc.). I often need to count multiple object types in a single image (e.g., both cars and people). This limitation means I have to manually count the second object type, which adds time to my workflow. 

**Describe the solution you'd like**  

I would like to see multi-class object detection added to the application, where the app can count multiple object types within a single image. For example, after uploading an image, the app should return the number of cars, people, and other relevant objects, all in one result.

**Describe alternatives you've considered**  

One alternative is to upload the same image to different applications that specialize in counting specific object types, but this is time-consuming and inefficient. Another approach is to use general-purpose object detection models via an API, but they are often not as user-friendly as the object count application.

**Additional context**  

- This feature would be especially useful for users dealing with complex scenes, such as crowded environments or urban areas.
- A potential UI improvement could involve selecting which object categories to detect from a predefined list.
- Below is an example of an image where detecting both cars and people would be useful:  
  [Example Image]
</details>

## Issue Guidelines

To ensure smooth and effective issue management:

- **Be clear and concise**: Provide as much detail as possible to help us understand the issue or request.
- **One issue per report**: Do not combine multiple bugs or feature requests into a single issue. This helps in organising and addressing each one separately.
- **Search before posting**: Check if your bug or feature request has already been submitted by someone else to avoid duplication.

---

Thank you for your interest in helping us improve the Object Count application. We highly value your feedback and suggestions to enhance the application's performance and features!
