# bgdemo

## Purpose

This application is used to demonstrate how to use Openshift/Jenkins Pipeline.

## How to use this demonstration

1. Create a project in Openshift
2. Copy/paste https://github.com/clerixmaxime/bgdemo in "GIT repository URL" field
3. Click on show advanced routing, build and deployment options
4. Uncheck the following fields under "Build Configuration" section: 
    - Automatically build a new image when the builder image changes
    - Automatically build a new image when the build configuration changes
5. Uncheck the following fields under "Deployment Configuration" section: 
    - New image is available
    - Deployment configuration changes
    
6. Click on "create" button

After that, you should see your application available in the project overview section. Clicking on "Start pipeline" will launch the build and deploy steps.
