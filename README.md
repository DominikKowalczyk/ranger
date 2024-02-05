# Ranger
Fusion 360 add-on that takes Leica rangefinder data as input and uses it as output for dimensions to geometry in an active sketch

# Development path for a Fusion 360 Add-On for Leica Rangefinder Data

## Introduction
This guide will walk you through creating a Fusion 360 add-on that leverages Leica rangefinder data. We'll cover setting up your development environment, accessing the Leica API, and integrating with Fusion 360.

## Prerequisites
- Basic knowledge of Python or C++ programming languages.
- Access to the Fusion 360 software.
- Account on the Geosystems Developer Network to access the Leica API.

## Step 1: Understand the Fusion 360 API
Before starting, familiarize yourself with the Fusion 360 API documentation to understand how to interact with Fusion 360 programmatically.

## Step 2: Access the Leica API
Sign up on the Geosystems Developer Network to get access to the Leica API, which allows you to retrieve data from Leica rangefinders.

## Step 3: Create a Manifest File for Fusion 360 Add-On
Every Fusion 360 add-on requires a manifest file with metadata about the add-on. 


## Step 4: Develop the Add-In Code
Write the add-in code using Python or C++. Your code will need to:
- Connect to the Leica API and retrieve the necessary data.
- Process the data within your add-in logic.
- Use the Fusion 360 API to create or modify designs based on the Leica data.
- For more detailed guidance on developing the add-in, refer to our [Roadmap](/documentation/roadmap.md)

## Step 5: Test Your Add-In
Ensure your add-in works correctly with the Leica API and integrates well with Fusion 360. Perform thorough testing to identify and fix any issues.

## Step 6: Package Your Add-In
Package your add-in according to Fusion 360's packaging guidelines, including the manifest file and your add-in code.

## Step 7: Distribute Your Add-In
Decide how you want to distribute your add-in. If you choose to publish it on the Autodesk App Store, follow Autodesk's submission guidelines.
