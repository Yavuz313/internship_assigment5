# Automated Exam Management System

## Overview

The Automated Exam Management System is designed to efficiently manage seating arrangements and faculty allocations for various student batches across different domains. The system utilizes k-means clustering to automate the seating plan and faculty allocation, optimizing the use of available resources and ensuring a smooth exam process.

## Features

- **Data Collection**: Collects and preprocesses data about students and rooms.
- **K-Means Clustering**: Uses k-means clustering to group students based on their domain and batch.
- **Seating Plan**: Generates an optimized seating plan based on room capacities and student clusters.
- **Faculty Allocation**: Allocates faculty members to rooms based on student domains and clusters.
- **Reporting**: Provides a summary report of the seating plan and faculty allocations.

## Usage

1. **Prepare your data**: Ensure that you have the student and room data in the required format.

2. **Run the Jupyter Notebook**: Open the notebook using Jupyter and execute the cells to perform data collection, preprocessing, clustering, and generate the seating plan and faculty allocation.

    ```bash
    jupyter notebook internship_assigment5.ipynb
    ```

3. **Check the output**: The notebook will generate reports and display the results.

## Code Explanation

### Data Collection

Collects student data (domain and term) and room data (capacity) for clustering and seating arrangements.

### Data Preprocessing

Converts categorical data to numerical format using `LabelEncoder` to prepare for k-means clustering.

### K-Means Clustering

Uses k-means clustering to group students based on their domain and term. Determines the optimal number of clusters using the Elbow method.

### Seating Plan

Creates a seating plan based on room capacities and student clusters. Allocates students to rooms ensuring no room exceeds its capacity.

### Faculty Allocation

Assigns faculty members to rooms based on student domains. Ensures that each room has faculty members relevant to the students' domains.

### Reporting

Generates a summary report of the seating plan and faculty allocation for review.

