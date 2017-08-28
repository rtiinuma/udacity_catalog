# Project: Item Catalog

Submission for "Project: Item Catalog" for Udacity Full-Stack Program.

Author: Renee Iinuma

Date: 8/28/2017

## To Run

- Ensure **Python 2** (Developed with Python 2.7.12) is installed
- If not not running on Udacity's Full Stack Vagrant image, run `pip install -r requirements.txt`
- Run `python project.py`
- Open a browser and navigate to `http://localhost:5000/`
- This screen always you to log in and out using Google
- Users can view restaurants and menu items
- If logged in, users can edit and delete restaurants and menu items that they have created

## API JSON endpoints
Data must exist in database
- Get list of restaurants
  - `/restaurant/JSON`
  - Ex: `http://localhost:5000/restaurant/JSON`
- Get restaurant menu by restaurant id
  - `/restaurant/<restaurant_id>/menu/JSON`
  - Ex: `http://localhost:5000/restaurant/1/menu/JSON`
- Get menu item by restaurant id and menu item id
  - `/restaurant/<restaurant_id>/menu/<menu_id>/JSON`
  - Ex: `http://localhost:5000/restaurant/1/menu/2/JSON`

## References
- This project is built off the base code provided in the `https://github.com/udacity/ud330` Udacity repository