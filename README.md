# TempeSalon

## User Manual

### Installation

1. Place the csv files on your desktop and open psql on your terminal.
2. Create four tables (salon, services, hours, amenities) in your POSTGRESQL database and copy the csv into the respective databases.
3. Open Terminal and cd into the directory where the project folder is saved.
4. Type ‘make’ and hit enterType ‘make’ and hit enter.
5. Type ‘make run’ and hit enter again. This should print the URL where the flask app is active.
6. Open your browser and navigate to the URL. This should show you the homepage of the Salon Finder.

### Features

The app shows you the top 10 salons in Tempe on the homepage and you have multiple filters in the form of checkboxes to filter out you results based on your preferences.

The following filters are present based on the Services offered by a salon:

1. Coloring
2. Blowout
3. Hair Treatment
4. Kids Haircut
5. Bridal Service
6. Hair Extension
7. Hairstyling
8. Makeup
9. Men’s Haircut
10. Women’s Haircut

The following filters are available based on the Amenities offered by a salon:

1. Mask Required
2. Accepts Card
3. Accepts Android Pay
4. Accepts Apple Pay
5. Good For Kids
6. Car Parking
7. Bike Parking
8. Free Wi-Fi
9. Wheelchair Access
10. Restroom
11. Appointment Only

The user can also select what day they would like to see the hours for, by selecting a day.

The user can also filter the results based on their budget that is represented by ‘$’ symbol
