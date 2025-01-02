# Data Dictionary

This document provides details about the dataset, including the column names, data types, and descriptions.

| **Column Name**     | **Data Type** | **Description**                                                                            | **Example Value** |
| ------------------- | ------------- | ------------------------------------------------------------------------------------------ | ----------------- |
| `car_make`          | String        | The manufacturer or brand of the car.                                                      | Porsche           |
| `car_model`         | String        | The specific model name or identifier of the car.                                          | 911               |
| `year`              | Integer       | The manufacturing year of the car.                                                         | 2022              |
| `engine_size`       | Float         | The engine displacement in liters.                                                         | 3.0               |
| `horsepower`        | Float         | The engine's power output, measured in horsepower.                                         | 379.0             |
| `acceleration_time` | Float         | The time in seconds the car takes to accelerate from 0 to 60 mph.                          | 4.0               |
| `price`             | Integer       | The retail price of the car in US dollars.                                                 | 101200            |
| `mileage`           | Float         | The total mileage the car has been driven, measured in miles (used or pre-owned vehicles). | 39900.0           |

## Notes

- All monetary values (`price`) are in US dollars.
- Mileage (`mileage`) is applicable to pre-owned vehicles; new cars may show minimal mileage for testing purposes.
- `engine_size` and `horsepower` reflect the car's performance capabilities.

This data dictionary is intended to aid in understanding and analyzing the dataset effectively.
