---
title: Hadoop Tutorial – Getting Started with HDP
tutorial-id: 100
platform: hdp-2.5.0
tags: [ambari, hive, pig, spark, zeppelin, technical-preview]
---

# Hadoop Tutorial – Getting Started with HDP

## Introduction

Hello World is often used by developers to familiarize themselves with new concepts by building a simple program. This tutorial aims to achieve a similar purpose by getting practitioners started with Hadoop and HDP. We will use an Internet of Things (IoT) use case to build your first HDP application.

This tutorial describes how to refine data for a Trucking IoT  [Data Discovery](https://hortonworks.com/solutions/advanced-analytic-apps/#data-discovery) (aka IoT Discovery) use case using the Hortonworks Data Platform. The IoT Discovery use cases involves vehicles, devices and people moving across a map or similar surface. Your analysis is targeted to linking location information with your analytic data.

For our tutorial we are looking at a use case where we have a truck fleet. Each truck has been equipped to log location and event data. These events are streamed back to a datacenter where we will be processing the data.  The company wants to use this data to better understand risk.

Here is the video of [Analyzing Geolocation Data](http://youtu.be/n8fdYHoEEAM) to show you what you’ll be doing in this tutorial.

## Prerequisites

-   Downloaded and Installed [Hortonworks Sandbox](https://hortonworks.com/downloads/#sandbox)
-   Before entering hello HDP labs, we **highly recommend** you go through [Learning the Ropes of the Hortonworks Sandbox](https://hortonworks.com/hadoop-tutorial/learning-the-ropes-of-the-hortonworks-sandbox/) to become familiar with the Sandbox in a VM and the Ambari Interface.
-   Data Set Used: [**Geolocation.zip**](https://app.box.com/HadoopCrashCourseData)
-   ***Optional*** Install [Hortonworks ODBC Driver](http://hortonworks.com/downloads/#addons)
-   In this tutorial, the Hortonworks Sandbox is installed on an Oracle VirtualBox virtual machine (VM) – your screens may be different.

## Outline

1.  **Concepts** Concepts that will strengthen your foundation in the Hortonworks Data Platform (HDP)
1.  **Lab 1** Loading Sensor Data into HDFS
2.  **Lab 2** Data Manipulation with Hive
3.  **Lab 3** Use Pig to compute Driver Risk Factor
4.  **Lab 4** Use Apache Spark to compute Driver Risk Factor
5.  **Lab 5** Optional Visualization and Reporting with Zeppelin
