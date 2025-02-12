# Campus Safety Office Work Order Management System

## Description

This Shiny application serves as a management tool for the Campus Safety Office to efficiently enter, track, and manage work orders related to campus maintenance issues. It facilitates the logging of who attended to specific work orders and manages details such as time, date, and involved personnel.

## Features

- **Data Entry Interface**: Utilizes `rhandsontable` for interactive data entry and automatic saving.
- **Time Validation**: Ensures valid times for work orders with formatted inputs.
- **Dynamic Dropdowns**: Uses dropdown menus populated with data from the database for selecting employees and trades.
- **Data Validation and Formatting**: Ensures that all entered data meets predefined standards and formats, including work order number validation.
- **Integration with PostgreSQL Database**: Maintains a connection to a PostgreSQL database for persistent data storage.
- **User Interface Customization**: Incorporates custom logos and styles to align with the campus safety office branding.

## Installation

1. **Clone the repository:**

  ```
  git clone https://github.com/asadow/appDataEntry.git
  cd appDataEntry
  ```

2. **Set up the database connection:**
- Ensure you have PostgreSQL installed and running.
- Create a database and user with appropriate permissions.
- Modify the database connection settings in the app to match your configuration.

## Running the App

To deploy the app locally, open the R project and run:

```r
renv::install()
rhino::app()
```
