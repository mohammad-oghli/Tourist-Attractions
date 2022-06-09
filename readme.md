## Tourist Attractions Simple Flask App

I attached required dependencies to run the app locally on your machine you can find it in `requirements.txt` file.

To install dependencies run this command on your terminal:

`pip install -r requirements.txt`

All the data of flask app saved using list of objects instantiated from class `location`, check `locations` file to understand functionalities of the class.

You can find the predefined data of locations and their attributes in the `data.csv` file.

You need to set `FLASK_APP` environment variable to load the application:

Run CMD command:

`set FLASK_APP=app`

Or run Powershell command:

`$env:FLASK_APP = "app"`

You can run flask app on your local host by executing this command on your terminal:

`flask run`

It will run on http://127.0.0.1:5000

**Tourist Attractions** is flask app to organize a list of places you want to visit.

Locations fall into 3 main categories:
* Recommended places to visit
* Decided places to visit 
* Places that have been visited.

Each Location class has three attributes:
* Name 
* Description
* Category

The main functionalities of this app:
* Show list of each location's category.
* Add new Location according to the 3 categories.
* Move location from one category to the next category (Recommedned -> Places to Go -> Visited)
* Remove location from category.

**Made with ❤ by Mohamad Oghli**

Email: `mhd.sh.oghli@gmail.com`