# Reverse-geocoder-using-api
## Reverse geocoder using Google API. 

This program utilises the [Google API Key](https://console.cloud.google.com/freetrial/signup/tos) to reverse the geocode.

## Prerequisites

- [Python](https://www.python.org/)
- [Google API Key](https://console.cloud.google.com/freetrial/signup/tos)
- [pandas](https://pandas.pydata.org/) ```!pip install -U pandas```
- [datetime](https://docs.python.org/3/library/datetime.html) (built-in module, no need to install)
- [googlemaps](https://github.com/googlemaps/google-maps-services-python) ```!pip install -U googlemaps```


## How to run

- Go through **Prerequisites** and install all the necessary items required.
- Download the program.
- Place the *file_name.xlsx* file, and *the program* in a new folder.
- Rename the place holder column names and file name in the program to the required specification.
- Run the program.

## How it works

- The program reads the excel file and converts it into a dataframe.
- The program the utilizes the api-key to access google's database and returns the address.
- The program then converts this information into an dictionary which is then converted into a dataframe.
- The output is then exported as an excel file.
