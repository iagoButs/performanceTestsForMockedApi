# Performance Tests for Mocked API

## Introduction

This repository contains performance tests for a mocked API using JMeter. 

## Prerequisites

Before running the performance tests, ensure you have JMeter installed. You can download it from the following link:

[JMeter Download](https://jmeter.apache.org/download_jmeter.cgi)

## Setup Instructions

1. **Download JMeter**: Visit the [JMeter download page](https://jmeter.apache.org/download_jmeter.cgi) and download the latest version.
  
2. **Extract the Files**: After downloading, extract the contents of the zip folder.

3. **Open JMeter**:
   - Navigate to the extracted JMeter folder.
   - Open the `bin` directory.
   - Run the `ApacheJMeter.jar` file.

4. **Load the Test Plan**: 
   - In JMeter, open the test plan file named `loadTestForGetAllUserEndpoints`, which is located in the cloned directory.

## Thread Groups

The test plan includes three thread groups:

1. **Testing `getAllUsers` Endpoint**: This thread group tests the performance of the `getAllUsers` API endpoint.

2. **Testing `getUserById` Endpoint**: This thread group tests the performance of the `getUserById` API endpoint.

3. **Testing `createUser` Endpoint**: This thread group tests the performance of the `createUser` API endpoint.

## Running the Tests

Once you've opened the test plan in JMeter, you can start the performance tests by clicking the **Start** button (the green triangle) in the toolbar.


