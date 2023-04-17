Inventory Direct
===========================
This is a simple Inventory Management System built using Flask and SQLAlchemy. This application allows users to add, update, and delete products and locations. Users can also add movements of products between locations.

Getting Started
---------------

### Prerequisites

-   Python 3.7+
-   Flask
-   Flask_SQLAlchemy

### Installing

1.  Clone this repository
  ```bash
     git clone https://https://github.com/warengeorge/Inventory-Direct.git
  ```

2.  Install the required packages

  ```bash Copy code
      pip install -r requirements.txt
  ```

3.  Run the application

  ```bash
      python app.py
  ```
4.  Open the application in your browser by navigating to  **`http://localhost:5000/`**

## Usage

The Inventory Management System has three main views: home, products, and locations.

-   **Home View**: This is the default view when the application is started. From this view, users can navigate to the products or locations views.
-   **Products View**: From this view, users can add, update, and delete products.
-   **Locations View**: From this view, users can add, update, and delete locations.

### Adding a Product

1.  Navigate to the products view by clicking on the "Products" link in the navigation bar.
2.  Enter the name of the product in the "Product Name" input field.
3.  Click the "Add Product" button.

### Updating a Product

1.  Navigate to the products view by clicking on the "Products" link in the navigation bar.
2.  Click the "Edit" button next to the product you want to update.
3.  Update the product name in the "Product Name" input field.
4.  Click the "Update Product" button.

### Deleting a Product

1.  Navigate to the products view by clicking on the "Products" link in the navigation bar.
2.  Click the "Delete" button next to the product you want to delete.
3.  Click the "Yes" button in the confirmation dialog.

### Adding a Location

1.  Navigate to the locations view by clicking on the "Locations" link in the navigation bar.
2.  Enter the name of the location in the "Location Name" input field.
3.  Click the "Add Location" button.

### Updating a Location

1.  Navigate to the locations view by clicking on the "Locations" link in the navigation bar.
2.  Click the "Edit" button next to the location you want to update.
3.  Update the location name in the "Location Name" input field.
4.  Click the "Update Location" button.

### Deleting a Location

1.  Navigate to the locations view by clicking on the "Locations" link in the navigation bar.
2.  Click the "Delete" button next to the location you want to delete.
3.  Click the "Yes" button in the confirmation dialog.

## Built With

-   [Flask](https://flask.palletsprojects.com/en/2.0.x/) - The web framework used
-   [SQLAlchemy](https://www.sqlalchemy.org/) - The Python SQL Toolkit and ORM

## Authors

-   **Tamunomiebi George** - _Initial work_ - [warengeorge](https://github.com/warengeorge)
