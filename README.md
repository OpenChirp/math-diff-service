[![Build Status](https://travis-ci.org/OpenChirp/math-diff-service.svg?branch=master)](https://travis-ci.org/OpenChirp/math-diff-service)

# Math-Diff OpenChirp Service

## Overview
This is a simple OpenChirp service that output the running diff of the data.

# Service Config
| Key Name | Key Description | Key Example | Is Required? |
| - | - | - | - |
| `InputTopics` | Comma separated list of input topics to apply the diff to | frequency, temp | Required |
| `OutputTopics` | Comma separated list of corresponding output topics | frequency_diff, temp_diff | Optional |
