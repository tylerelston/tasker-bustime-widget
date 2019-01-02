# Tasker BusTime Widget

Utilizes Tasker and Minimalistic Text: Widgets to display bus number, departure, and arrival times for the best route home on your home screen

<img src="https://user-images.githubusercontent.com/24640479/50578135-4bfeaa00-0dea-11e9-8884-cc93b8f20ba1.jpg" width="200">

## Required
- [Tasker](https://play.google.com/store/apps/details?id=net.dinglisch.android.taskerm)

- [AutoRemote](https://play.google.com/store/apps/details?id=com.joaomgcd.autoremote)

- [Minimal Text: Widgets](https://play.google.com/store/apps/details?id=de.devmil.minimaltext)

- [Google Maps API key](https://developers.google.com/places/web-service/get-api-key)

## Instructions

1. Import the BusTime task

2. Edit the task:

   - Set %dest to your destination, + sperated
   - Set %mapkey to your Google Maps API key
   - Edit the JavaScriplet json indexes to the names/times of your liking
   
3. Add a Minimalistic Text widget to your home screen
   - Inside the layout tab, add three Locale variables and set them to Bus, Depart, Arrive

4. Create a profile that runs BusTime as frequently as you wish

## Additional Functionality
- Link the widget tap behaviour to the BusTime task to update it
