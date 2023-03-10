# Life in Between - App

![GitHub](https://img.shields.io/github/license/Caerii/XRTrainRide?style=for-the-badge)

MIT Reality Hack 2023.

3D Map Viewer by Team 2025.

This app was designed to map all services and amenities available to you on the subway line you're currently riding.

![HeaderInBetween](https://user-images.githubusercontent.com/88777150/212558537-bdcd2085-20ea-433e-a01f-478d31a172dc.gif)

## Team Members

- [Sola Babatunde](https://github.com/solajr/)
- [Alif Jakir](https://github.com/Caerii)
- [Yanxiu Luo](https://github.com/AllyYL)
- [Diego Saldivar](https://github.com/neurogamedev)

## What it does

Our mixed reality experience, "Life in Between," allows users to view hyper-local environments around them using 3D mesh data of local buildings. By providing detailed information about the places around them, we aim to enhance people's sense of presence and connection to their community. Users can explore their neighborhood, discover new places and learn more about the history and architecture of the buildings around them.
Our experience can be used for a variety of purposes, including: 
- Community building
- Tourism and local discovery
- Educational and historical exploration 
- Real estate and property management

## Functionalities

| View  | Features |
| ------------- | ------------- |
| ![Search](https://user-images.githubusercontent.com/88777150/212557443-7b32e1aa-6796-4ba7-9342-89f511219731.gif) | One of our main functions is the ability to search like a **wayfinding platform** that focuses on public transportation. When a users makes a search on our app, we use Google Maps API to gather a lot of results and then we filter by the locations near the subway / bus stops. You can search services and places in the subway line of your choice so that you can make sure any detours or locations you visit are always convieniently along the route you travel. This is perfect for helping smaller, impoverished communities get business and traffic where they would otherwise be ignored. |
| ![Bookmarks](https://user-images.githubusercontent.com/88777150/212557428-467d1475-381f-4881-a384-6c70a4dcf483.gif) | Guess what? While you are out and about with our app, we will load a list of offline suggestions for places to visit that are on the subway  / bus line you are currently taking. It enables them to see a 3D representation of the places that are on their subway line. Keep bookmarks of your favorite places or the places you intend to visit halfway through your next commute. Currently it is limited to just cafes and gyms near the user's subway stop|
| ![MapExplore](https://user-images.githubusercontent.com/88777150/212557488-35358300-4549-4eb5-80dc-dc3c7d6aa2fd.gif) | We use ArchGIS to generate a 3D visualization to help people comfortably know what the city is like. Explore in 3D the places exactly above your subway line even as you traverse it! |
| ![Settings](https://user-images.githubusercontent.com/88777150/212557601-7d613aec-35b8-4ca0-8a0d-4d641d40c3d4.gif)  | Adjust your settings for a more comfortable commute.  |

## Dependencies

- Unity 2021.3.16.1f
- Android Studio
- ARCore
- Eris ARCGis (3D Mapping data) SDK
- Vive XR Elite (Passthrough Mixed Reality)
