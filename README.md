# RealEstate Allocation Project

The objective of this project is to create a real estate allocation system, allowing for efficient distribution of available real estate properties. This can be useful in various scenarios, such as rental management, allocation of company properties, or even housing assignments in institutions.

## How it works

Our real estate allocation system is based on an intelligent algorithm that considers multiple criteria to assign properties. Here is a simple example to illustrate how it works:

Suppose we have 5 apartments to allocate to 5 individuals (A, B, C, D, E). Each individual has a certain number of preferences for apartments, rated from 1 to 5 (1 being the highest preference and 5 the lowest).

- Person A prefers apartment 3, then apartment 1, and so on.
- Person B prefers apartment 2, then apartment 4, and so on.
- Person C prefers apartment 1, then apartment 5, and so on.
- Person D prefers apartment 4, then apartment 3, and so on.
- Person E prefers apartment 5, then apartment 2, and so on.

Our system's algorithm takes these preferences into account and strives to maximize overall satisfaction. It will assign the apartments to individuals in a way that maximizes the total number of satisfied preferences.

## How to use this project

1. Clone this repository to your local machine.

2. Configure the preferences of individuals and the real estate properties in the configuration file.

