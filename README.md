# ShopSim

This code is a customer simulation created using Pygame library. The simulation consists of a group of customers who move towards a product in the market. The objective of the simulation is to test the customer flocking psychology towards 3 different products based on different parameters (pricing, shelving, and packaging quality). The simulation records data and statistics that can be used to analyze the behavior of customers.

## Libraries used
- Pygame
- Pyautogui
- Math
- Datetime
- Numpy
- Matplotlib
- Sys

## Parameters
The simulation consists of different parameters that can be modified to get different results. The following is the list of parameters used in the simulation:

- **Pricing (the higher the number, the lower the price), Shelving, Packaging Quality**: Parameters that define the different groups of customers in the market.
- **Weightage of Pricing, Shelving, Packaging Quality**: Weightage given to the different parameters to calculate the final score of each customer group.
- **Customer Flocking Psychology**: Parameters that define the behavior of customers towards each other.
- **Setup**: Parameters that define the initial setup of the simulation.
- **Print Data**: Boolean parameters that define whether to print data and statistics or not.
- **Startup**: Initial parameters that define the simulation.

## Customer Class
The Customer class defines the attributes and behavior of the customers in the simulation. The following are the attributes of the Customer class:

- **size**: The size of the customer.
- **degrees**: The angle of the customer.
- **limit**: The limit of the customer within the screen.
- **speed_lim**: The maximum speed limit of the customer.
- **sightRange**: The sight range of the customer.
- **Customers**: A list of all the customers in the simulation.

The following are the methods of the Customer class:

- **attraction**: Calculates the attraction force of the customer towards the product.
- **__init__**: Initializes the customer with a position, velocity, and target.
- **__str__**: Returns the position and velocity of the customer.
- **x**: Gets and sets the x-coordinate of the customer.

## Conclusion
The customer simulation is a simple yet effective simulation that can be used to test the customer flocking psychology towards the product in the market. The simulation provides data and statistics that can be analyzed to optimize the marketing strategies and increase the sales of the product.
