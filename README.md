Checklist for the SWK5 and WEA5 project which is part of the software engineering bachelor study at the university of applied sciences Upper Austria

- Mind a good UI design
- Don't show primary or foreign keys in the UI
- Don't show any exceptions in the UI, just display an error page
- Don't use SQL statements in the application layer, limit them to the persistence layer
- Don't put all data in the database, consider using a content repository
- Stress test your application's performance by generating 10,000 to 50,000 database records
- Caching data can bring performance benefits
- Mind simultaneous access, so stick to multithreading principles and synchronisation
