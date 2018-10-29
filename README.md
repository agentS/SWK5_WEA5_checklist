Checklist for the SWK5 and WEA5 project which is part of the software engineering bachelor study at the university of applied sciences Upper Austria

- Mind a good UI design
	- Try to immerse yourself in the user's perspective
		- I want to see today's weather
		- I want to add a weather station
- Generate realistic test data in order to create a great visualisation
	- Simulate a winter, spring, summer and autumn day
	- Simulate a rainy day, a sunny day and a cloudy day
- Don't show primary or foreign keys in the UI
- Don't show any exceptions in the UI, just display an error page
- Don't use SQL statements in the application layer, limit them to the data access layer
- Don't put all data in the data, consider using a content repository
- Don't use SQL statements in the application layer, limit them to the persistence layer
- Don't put all data in the database, consider using a content repository
- Stress test your application's performance by generating 10,000 to 50,000 database records
- Caching data can bring performance benefits
- Mind simultaneous access, so stick to multithreading principles and synchronisation
