# Components
- UI
	- Figma will be used to design UI
	- Car selection
	- Map display
	- Emission readout
	- Emission visualization
- APIs
	- Edmunds API
		- For accessing car information
	- Google maps API
		- For speed and route calcuation
		- Will be used to show route on screen for navigation
- Storage
	- Will store the data of the type of car being driven
	- Will store carbon footprint data after it is calculated
		- Allows recollection of data from any previous use of the application
	- Will use local storage on smartphone
		- Makes data visualization faster if it does not have to download data first
		- Allows data to be savedd even if the user is driving somewhere without cell service
- Back end
	- Will be developed using Android Studio
		- Written in Java
---
# Understanding the Components
- UI
	- The UI have to interact with Edmunds API in order to allow the user to select their vehicle. It will 
	have to interact with the Maps API in order to display route information to the user. It will also interect 
	with algorithm used to calculate emissions in order to display those results to the user. 
- Maps API
	- The Maps API will use the GPS hardware in the device in order to get speed and location information. It will
	pass this data along to be used for calculating the emissions of trips. The Maps API will also be used to create 
	the navigation visualization.
- Edmunds API
	- The Edmunds API will pass along vehicle information to be used for emissions calculations. This API will be 
	used to create a drop down menu in the UI so that users can easily select their year, make, and model of vehicle.
- Back end
	- The programming that will handle the integration of these APIs, and coordinate the data they produce will 
	be created in Android Studio. This will handle the process of sending the user's vehicle information to internal storage,
	and fetching it when needed. It will take the route information suplied by the Maps API, and the vehicle information that the
	user selected from the Edmunds API and calculate emissions from it. It will take the calculations, and store them to be 
	displayed when the user wants.
---
# Breaking down components
- Back end
	- Will have to take info from Edmunds API and give it to UI
	- Will take to take Maps API info and give it to UI
	- Will have to use info taken from APIs to calculate emissions
	- Will have to access storage to save data
	- Will have to access accelerometer to detect when user is driving
- UI
	- The UI will have to allow users to select a vehicle
	- The UI will show the emissions information to the user
	- The UI will give graphical representation of emissions
	- Navigation screen will be shown when app is in use
- Maps API
	- Will have to extract travel distance and speed
	- Will have to map info to display to user
- Edmunds API
	- Will access Edmunds vehicle database in order to fetch vehicle data
	- Will be used to create drop down menu in UI
---
# Order of Priority
- Maps API
	- Access info from Maps APIs
	- Show route info to user
- Back end
	- Take info from Maps and manipulate it
	- Give Maps info to UI
- UI
	- Create clean visual theme
	- Dislay Maps information
	- Display drop down menu from Edmunds API










	