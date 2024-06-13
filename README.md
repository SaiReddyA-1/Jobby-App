# Jobby App

In this project, I have built the **Jobby App** fulfilling all the specified functionalities.

## Demo Videos

**To view the videos:**
Click on the links below to watch the video outputs of the application:

- [Success Output Video](https://assets.ccbp.in/frontend/content/react-js/jobby-app-success-output-v0.mp4)
- [Failure Output Video](https://assets.ccbp.in/frontend/content/react-js/jobby-app-failure-output-v1.mp4)

If the videos do not play, try downloading them and viewing them locally on your device.

## Design Files

### Login Route

- [Extra Small (Size < 576px) and Small (Size >= 576px) - Login](https://assets.ccbp.in/frontend/content/react-js/jobby-app-login-sm-outputs.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Login](https://assets.ccbp.in/frontend/content/react-js/jobby-app-login-lg-output.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Login Failure](https://assets.ccbp.in/frontend/content/react-js/jobby-app-login-failure-lg-output.png)

### Home Route

- [Extra Small (Size < 576px) and Small (Size >= 576px) - Home](https://assets.ccbp.in/frontend/content/react-js/jobby-app-home-sm-output.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Home](https://assets.ccbp.in/frontend/content/react-js/jobby-app-home-lg-output.png)

### Jobs Route

- [Extra Small (Size < 576px) and Small (Size >= 576px) - Jobs](https://assets.ccbp.in/frontend/content/react-js/jobby-app-jobs-sm-outputs.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Jobs Success](https://assets.ccbp.in/frontend/content/react-js/jobby-app-jobs-success-lg-output-v0.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - No Jobs](https://assets.ccbp.in/frontend/content/react-js/jobby-app-no-jobs-lg-output-v0.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Profile Failure](https://assets.ccbp.in/frontend/content/react-js/jooby-app-profile-failure-lg-output-v0.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Jobs Failure](https://assets.ccbp.in/frontend/content/react-js/jobby-app-jobs-failure-lg-output-v0.png)

### Job Item Details Route

- [Extra Small (Size < 576px) and Small (Size >= 576px) - Job Details Success](https://assets.ccbp.in/frontend/content/react-js/jobby-app-job-details-success-sm-output-v0.png)
- [Extra Small (Size < 576px) and Small (Size >= 576px) - Job Details Failure](https://assets.ccbp.in/frontend/content/react-js/jobby-app-job-details-failure-sm-output.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Job Details Success](https://assets.ccbp.in/frontend/content/react-js/jobby-app-job-details-success-lg-output-v0.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Job Details Failure](https://assets.ccbp.in/frontend/content/react-js/jobby-app-job-details-failure-lg-output.png)

### Not Found Route

- [Extra Small (Size < 576px) and Small (Size >= 576px) - Not Found](https://assets.ccbp.in/frontend/content/react-js/jobby-app-not-found-sm-output-v0.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Not Found](https://assets.ccbp.in/frontend/content/react-js/jobby-app-not-found-lg-output-v0.png)

## Set Up Instructions

- Download dependencies by running `npm install`
- Start up the app using `npm start`

## Completion Instructions

### Functionality to be added

The app has been implemented with the following functionalities:

- **Login Route**
  - Displays appropriate error messages for invalid credentials
  - Redirects authenticated and unauthenticated users based on access permissions

- **Home Route**
  - Navigates to the Jobs Route when the user clicks on "Find Jobs"

- **Jobs Route**
  - Fetches and displays jobs based on various criteria like employment type, salary range, and search input
  - Handles retry logic for API failures and displays appropriate views for success and failure scenarios

- **Job Item Details Route**
  - Fetches job details and displays related information including similar jobs
  - Opens company website URL on clicking the "Visit" button

- **Not Found Route**
  - Handles unknown URLs by redirecting to the Not Found Route

- **Header**
  - Provides navigation links and logout functionality

- **Additional Features**
  - Integrates loader components and ensures accessibility with appropriate alt texts for images

### API Requests & Responses

Detailed API documentation and response formats are integrated into the app as per the specifications.


## Important Note

Ensure adherence to provided instructions and specifications for seamless integration and testing of the application.

## Resources

### Image URLs

- [https://assets.ccbp.in/frontend/react-js/home-sm-bg.png](https://assets.ccbp.in/frontend/react-js/home-sm-bg.png)
- [https://assets.ccbp.in/frontend/react-js/home-lg-bg.png](https://assets.ccbp.in/frontend/react-js/home-lg-bg.png)
- [https://assets.ccbp.in/frontend/react-js/profile-bg.png](https://assets.ccbp.in/frontend/react-js/profile-bg.png)
- [https://assets.ccbp.in/frontend/react-js/logo-img.png](https://assets.ccbp.in/frontend/react-js/logo-img.png) alt should be **website logo**
- [https://assets.ccbp.in/frontend/react-js/failure-img.png](https://assets.ccbp.in/frontend/react-js/failure-img.png) alt should be **failure view**
- [https://assets.ccbp.in/frontend/react-js/no-jobs-img.png](https://assets.ccbp.in/frontend/react-js/no-jobs-img.png) alt should be **no jobs**
- [https://assets.ccbp.in/frontend/react-js/jobby-app-not-found-img.png](https://assets.ccbp.in/frontend/react-js/jobby-app-not-found-img.png) alt should be **not found**

### Colors

- Hex: #64748b
- Hex: #4f46e5
- Hex: #f8fafc
- Hex: #272727
- Hex: #ffffff
- Hex: #b6c5ff
- Hex: #6366f1
- Hex: #2c364c
- Hex: #000000
- Hex: #f1f5f9
- Hex: #fbbf24
- Hex: #202020
- Hex: #cbd5e1
- Hex: #7e858e
- Hex: #121212
- Hex: #475569
- Hex: #ff0b37

### Font-families

- Roboto
