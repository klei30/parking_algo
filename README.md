# parking_algo

Sure, here's a more concise version:

# Bike Rack Parking Optimizer

A JavaScript program to determine the optimal parking spot on a bike rack to maximize distance from other bikes.

## How It Works

The solution considers two scenarios:

1. Between two bikes: park in the middle of the largest gap.
2. At rack ends: if the largest gap is between a bike and the rack end, park at that end.

## Usage

Here's how you use it:

```javascript
console.log(findParkingSpot([2, 5, 9], 10));  // Output: 7
console.log(findParkingSpot([1, 3, 6], 10));  // Output: 9
```
