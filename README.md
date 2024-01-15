# Renko System ReadMe File

This ReadMe file provides information on the Renko System code. The Renko System is a trading strategy developed by the Forex Robot Easy Team. For detailed reviews and trading results of this product, please visit [Forex Robot Easy - Renko System Review](https://forexroboteasy.com/forex-robot-review/renko-system-review-forex-trading-with-timeless-indicators/).

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Expert Advisor Functions](#expert-advisor-functions)
- [Execution of Program](#execution-of-program)

## Introduction
The Renko System is designed to generate Renko bars, calculate moving averages, display wicks, show a datetime indicator, send custom notifications, and raise events for Expert Advisors. The code provides a class `CRenkoSystem` with methods to perform these tasks.

## Installation
To use the Renko System code, you need to include the necessary libraries. The required libraries are:
- `Trade/PositionInfo.mqh`
- `Trade/Trade.mqh`
- `Technical/Indicators/MA.mqh`
- `Notifications/Notification.mqh`

## Usage
The Renko System is implemented as a class `CRenkoSystem`, which takes four parameters in its constructor:
1. `renkoThreshold`: The Renko bar threshold.
2. `maPeriod`: The moving average period.
3. `showWicks`: A flag to display wicks.
4. `showDatetime`: A flag to display the datetime indicator.

The main entry point of the Renko System is the `Run()` method, which executes the following tasks:
1. Generates Renko bars.
2. Calculates moving averages.
3. Displays wicks if the `showWicks` flag is set to `true`.
4. Displays the datetime indicator if the `showDatetime` flag is set to `true`.
5. Sends custom notifications.
6. Raises events for Expert Advisors.

To use the Renko System, create an instance of `CRenkoSystem` and call the `Run()` method.

## Expert Advisor Functions
The Expert Advisor functions section is where you can implement necessary trading functions specific to the Renko System. This section is left empty in the provided code, and you need to implement the required trading functions based on your trading strategy.

## Execution of Program
The `OnStart()` function is the entry point of the program. In this function, the Renko System is initialized by creating an instance of `CRenkoSystem` with the desired parameters. Then, the `Run()` method is called to execute the Renko System.

Please note that Forex Robot Easy is not the official developer of this product. This code is provided as a sample that can work as described in the product review. To find the official developer of this product, please refer to MQL5.
