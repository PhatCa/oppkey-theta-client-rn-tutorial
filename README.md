## What I'm trying to do

I am a computer science student at UH Manoa and am trying to learn mobile development. I wanted to build my first React Native application using [theta-client-package](https://www.npmjs.com/package/theta-client-react-native) to connect with my THETA camera. Prior to this, I have had limited experience with mobile development (mainly just web development).

I want to have a few buttons on the app to view camera photo images, and want to use livepreview before taking a photo so I can see what the photo will look like before I take the picture.

I am trying to learn the function of theta-client, the THETA SDK, from the package via their [Github repository](https://github.com/ricohapi/theta-client/tree/main/demos/demo-react-native/src).

## What I have built so far:

Step 1: Generating React Native application without using any react-native framework

```

npx @react-native-community/cli@latest init Tutorial

```

Step 2: Installing the [theta-client-react-native](https://www.npmjs.com/package/theta-client-react-native) package

```

Npm i theta-client-react-native

```

Step 3: Install all dependencies from package.json file of the react native project

```

Yarn install

```

Step 4: install all the dependencies for ios project

```

Cd ios

Pod install

```

Step 5: Run application

```

Yarn run ios

```

## Current Stage of my application:

Using documentation from [github theta-client](https://github.com/ricohapi/theta-client/tree/main/demos/demo-react-native/src) function to personalize my application. I have successfully built a basic React Native application and have tested a function from the github repo (initialize) which displays the camera information after connecting to the camera. The app is currently running on a physical iPhone 12 Pro Max and is connected to the THETA via the camera hotspot.

## Current Issues and Next Steps:

I'm working on implementing getLivePreview to display the camera view after connecting to the camera. However, I am encountering an error when attempting to use this function.

![|155x373](https://lh7-rt.googleusercontent.com/docsz/AD_4nXcPyZJM_PznpOQQVpNc9JiFKNr-grRlIle_4cGBDZko2rKEFSZyBxzjZupgoBN0rNvg0hSP6bldYXe0EqRiz0uw3XoxBTcpxJqfY9Bb2pcr2EHdVx1qajdyWwhXgI6X3_U0OS2EzQ?key=1-VQgXbrESzj75alanMXA5T-)

With limited experience in mobile app development, I am uncertain if it was my setup that caused the issue or if the error was from a misunderstanding of the function.

Additionally, when connecting to camera wifi, I am unable to use a React Native debugging tool. Which makes it more difficult to troubleshoot errors.

I am planning to fix this by trying another easier function to grab photos (data) from the camera and show it on the app after clicking and viewing an image.