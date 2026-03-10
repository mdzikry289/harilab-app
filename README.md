# harilab-app
The Harilab application is an application that allows clients to rent items based on dates, so clients do not need to worry about the availability of items on the date booked by the client.

This application was built with Laravel 12.35.0 with the following components:
- PHP 8
- Laravel Queue Scheduler
- MySQL Database
- Firebase Notifications
- Laravel Filament

I worked on this project to enable clients to rent items from event organizers or suppliers, eliminating the need for event organizers to manually check availability on a specific date.

This application allows:
- Login/Sign Up with Google (Google API Login)
- Add, edit, and delete divisions or vendors involved in the procurement of items
- Add, edit, and delete item data, and view the availability of rental items on each date
- Add, edit, and delete item categories
- Add, edit, and delete users (superadmin access)
- Add, edit, and delete roles (Filament Roles)
