---
title: Introduction
permalink: /docs/introduction/
redirect_from: /docs/index.html
---

The Estimote Unity plugin allows you to use the Estimote SDK within Unity and deploy to iOS or Android. Whether you are using Estimote beacons or any other iBeacon manufacturer this plugin will work for you (excluding the cloud based Estimote features).

We do however recommend you use [Estimote beacons](https://estimote.com/) as they are fantastic and reliable.

## Quick Start
There are a few quick and easy steps to get started with the plugin. Follow the instructions below to get started.

1. Create a new GameObject and rename it to EstimoteUnity.
2. Ensure the EstimoteUnity GameObject is selected.
3. Click “Add Component” on the EstimoteUnity GameObject inspector and add the Estimote Unity script.
4. Inside the custom EstimoteUnity inspector you will see some red errors. This is because we do not ship the Estimote iOS/Android SDK’s within the package. (If you see no red errors then you are already setup and good to go).
5. Click on the button below the red warnings to open up the Estimote Unity Setup window.
6. Now follow the instructions within that window to properly install the iOS and Android SDK’s within your project. NOTE: If you are only supporting one platform you do not need to install the other for the plugin to work.
7. Once you have setup the SDK’s properly you will notice that the warnings have now changed from red to green.
8. Now we need to ensure you have your UUID’s setup within the inspector so you can scan for beacons.
9. Select the EstimoteUnity GameObject and within the General Properties section ensure your beacon UUID’s are added into the list. If you are using Estimote beacons then you can click the handy button to add it for you.
10. Complete! You are now all setup and ready to start scanning for beacons.
11. When building to a device please ensure you have targetted the correct OS/API levels as stated under the System Requirements section above.
