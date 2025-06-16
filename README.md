markdown
# cars-by-api-ninjas MCP Server

## Overview

The `cars-by-api-ninjas` MCP server provides a robust and comprehensive solution for accessing detailed information on a vast array of car models from numerous automakers. This server is designed to cater to users who need detailed automotive data for various purposes, from industry analysis to personal research.

### Key Features
- **Extensive Database**: Access detailed data on tens of thousands of vehicle models from a wide range of automakers.
- **Diverse Search Parameters**: Utilize a variety of parameters to tailor your search and find the most relevant vehicle data.
- **Updated Information**: The server is constantly refreshed with the latest data to ensure accuracy and relevance.

## Tools and Usage

The server is equipped with a primary tool group designed for efficient data retrieval:

### Tool Group: `/v1/cars`
- **Function Name**: `/v1/cars`
  - **Description**: This tool is the main endpoint for retrieving car data.

#### Tool Parameters

- **Model**: (Optional) The specific model of the vehicle you are interested in.
- **Make**: (Optional) The manufacturer of the vehicle.
- **Min City MPG**: (Optional) The minimum city fuel efficiency in miles per gallon.
- **Max City MPG**: (Optional) The maximum city fuel efficiency in miles per gallon.
- **Min Hwy MPG**: (Optional) The minimum highway fuel efficiency in miles per gallon.
- **Max Hwy MPG**: (Optional) The maximum highway fuel efficiency in miles per gallon.
- **Min Comb MPG**: (Optional) The minimum combined (city + highway) fuel efficiency in miles per gallon.
- **Max Comb MPG**: (Optional) The maximum combined (city + highway) fuel efficiency in miles per gallon.
- **Cylinders**: (Optional) The number of cylinders, with possible values ranging from 2 to 16.
- **Transmission**: (Optional) The type of transmission, either manual or automatic.
- **Year**: (Optional) The model year of the vehicle.
- **Drive**: (Optional) The type of drive transmission, such as fwd (front-wheel drive), rwd (rear-wheel drive), awd (all-wheel drive), or 4wd (four-wheel drive).
- **Fuel Type**: (Optional) The type of fuel used, which can be gas, diesel, or electricity.
- **Limit**: (Optional) The number of results to return, ranging from 1 to 30, with a default of 5.

This powerful and flexible toolset ensures that users can retrieve the specific car data they need efficiently and accurately. Whether you're conducting market research or simply curious about vehicle specifications, the `cars-by-api-ninjas` MCP server is your go-to resource for comprehensive car data. 

For further details on using these tools, refer to the server's internal documentation.