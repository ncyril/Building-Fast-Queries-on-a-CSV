# Building-Fast-Queries-on-a-CSV

**Overview**
This Jupyter Notebook presents a guided project focused on optimizing data queries for a CSV file containing laptop inventory information. The notebook is structured as follows:

**Reading the Inventory**: This section reads the CSV file into a list of rows, where each row represents a laptop.

**Inventory Class**: An **Inventory** class is introduced to organize and manipulate the laptop inventory. The class loads data from the CSV file, converts the price column to integers, and precomputes a dictionary for faster ID lookups.

**Finding a Laptop From the ID**: This section defines a method to find a laptop by its unique identifier within the inventory.

**Improving ID Lookups**: An optimized method for ID lookups is introduced using a precomputed dictionary, significantly improving performance.

**Comparing Performance**: This section compares the performance of both ID lookup methods and provides an analysis of the results.

**Two Laptop Promotion**: A method is implemented to determine if a given amount of money can be spent on one or two laptops.

**Optimizing Laptop Promotion**: A faster version of the promotion method is created using data structures to improve performance.

**Comparing Promotion Functions**: The performance of both promotion methods is compared, and the results are analyzed.

**Finding Laptops Within a Budget**: Methods for finding laptops within a specified budget and the first laptop more expensive than a target price are implemented.

**How to Use** 

To utilize this notebook and understand the content, follow these steps:

**Prerequisites**: Ensure that you have a Python environment set up with Jupyter Notebook installed.

**Dataset**: Make sure you have the "laptops.csv" file in the same directory as this notebook. This dataset should contain the laptop inventory information.

**Execution**: Execute each cell sequentially to observe the code in action and understand the performance improvements achieved at each stage.

**Customization**: Feel free to modify the code or experiment with your datasets to apply the techniques learned here to other scenarios.

**Analysis**: Pay attention to the provided analysis sections, as they offer insights into the performance gains achieved through optimization.

**Documentation**: Refer to the comments in the code for explanations and detailed guidance at each step.

**Conclusion**
This notebook is an excellent resource for learning how to optimize data queries and improve the performance of code that handles large datasets. It demonstrates the process of creating an inventory class, optimizing ID lookups, and enhancing promotion functions. By following this project, you'll gain valuable insights into efficient data processing techniques.

You can find the notebook [here](https://github.com/ncyril/Building-Fast-Queries-on-a-CSV/blob/main/Basics.ipynb)!
