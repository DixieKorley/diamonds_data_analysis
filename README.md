# Diamonds Data Analysis

The dataset represents prices of over 50,000 round cut diamonds. I was able to download the files via [kaggle](https://www.kaggle.com/datasets/devrimtuncr/diamonds). 

## About
| Variable | Description | Example |
| ---------- | :-------- |  :-------- |
| Price | Price in USD | $326--$18,823 |
| Carat | Weight of the diamond | 0.2--5.01 |
| Cut | Quality of the cut| Fair, Good, Very Good, Premium, Ideal |
| Color | Diamond color | D (best) to J (worst) |
| Clarity | Measurement of how clear the diamond is | (I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best)) |
| x | length in mm | 0--10.74 |
| y |  width in mm | 0--58.9 |
| z |  depth in mm| 0--31.8 |
| Depth |  total depth percentage =  z / mean(x, y) = 2 * z / (x + y) | (43--79)  |
| Table |  width on top of diamond relative to the widest point | (43--95) |

## Notes

We are ignoring the data directory containing the set due to it's size. 