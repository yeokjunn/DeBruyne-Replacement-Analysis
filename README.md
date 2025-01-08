# ⚽ Kevin De Bruyne Replacement - Analysis Project ⚽

## Overview

This project aims to analyze football players' performance metrics using various statistical techniques, including Min-Max normalization and Z-score normalization. The analysis focuses on identifying player similarities based on their performance data, which can be useful for scouting, team selection, and performance evaluation.

## Table of Contents

1. [Introduction](#introduction)
2. [Data](#data)
3. [Normalization Techniques](#normalization-techniques)
4. [Results](#results)
5. [Players Appearing in Both Results](#players-appearing-in-both-results)
6. [Conclusion](#conclusion)
7. [License](#license)

## Introduction

In modern football analytics, understanding player performance is crucial for making informed decisions. This project utilizes statistical methods to normalize player performance data and calculate Euclidean distances to identify similar players.

## Data

The dataset used in this project includes various performance metrics for football players, such as:

- Player names
- Performance statistics
- Euclidean distances calculated after normalization

## Normalization Techniques

Two normalization techniques were applied to the dataset:

1. **Min-Max Normalization**: This technique scales the data to a fixed range, typically [0, 1]. It is useful for ensuring that all features contribute equally to the distance calculations.

2. **Z-Score Normalization**: This method standardizes the data based on the mean and standard deviation, allowing for comparison across different scales.

## Results

The results of the analysis include the Euclidean distances of players after applying both normalization techniques. The following players appeared in both results:

### Players Appearing in Both Results

1. **Aleksei Miranchuk**
   - Min-Max Distance: 0.101267
   - Z-Score Distance: 1.340595

2. **Luka Modrić**
   - Min-Max Distance: 0.207610
   - Z-Score Distance: 1.893687

3. **Thomas Müller**
   - Min-Max Distance: 0.211948
   - Z-Score Distance: 1.929590

4. **Raphinha**
   - Min-Max Distance: 0.178372
   - Z-Score Distance: 1.879958

5. **Imran Louza**
   - Min-Max Distance: 0.213094
   - Z-Score Distance: 2.113787

6. **Ivan Rakitić**
   - Min-Max Distance: 0.159258
   - Z-Score Distance: 2.220394

7. **Arne Maier**
   - Min-Max Distance: 0.203464
   - Z-Score Distance: 2.179026

8. **Harvey Elliott**
   - Min-Max Distance: 0.194671
   - Z-Score Distance: 1.930605

## Conclusion

This project demonstrates the application of statistical normalization techniques to analyze football player performance data. The findings can assist coaches, scouts, and analysts in making data-driven decisions regarding player selection and performance evaluation.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Your Data Source] - for providing the dataset.
- [Any Libraries or Tools Used] - for their contributions to the project.
