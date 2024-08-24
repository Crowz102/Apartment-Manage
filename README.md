# Rental Property Management Project

This project is a simple rental property management tool designed to run on Google Colab. It utilizes several Python libraries to manage and visualize data related to rental properties, customers, and attachments.

## Project Structure

The project relies on three CSV files to store and manage data:

- **Room.csv**: Contains information about the rooms available for rent.
- **Customer_ap.csv**: Stores data related to customers who have applied or rented properties.
- **attachment.csv**: Manages various attachments related to the properties or customers.

## Libraries Used

The project uses the following Python libraries:

- `pandas`: For data manipulation and analysis.
- `matplotlib`: For data visualization.
- `google.colab`: To interact with Google Drive and manage file uploads/downloads within Google Colab.
- `ipywidgets`: To create interactive widgets in the notebook.
- `IPython.display`: For displaying various types of output such as HTML, images, etc.
- `PIL`: For image processing tasks.

***bash
pip install pandas matplotlib ipywidgets pillow

## Setup and Usage

To use this project, you need to run it in Google Colab. Make sure the required CSV files are uploaded to your Google Drive and update the file paths accordingly.

```python
csv_path = '/content/drive/MyDrive/CSV/Room.csv'
csv_pathCus = '/content/drive/MyDrive/CSV/Customer_ap.csv'
csv_pathAttachment = '/content/drive/MyDrive/CSV/attachment.csv'
