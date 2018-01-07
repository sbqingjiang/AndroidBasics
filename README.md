# AndroidBasics

## Data persistence
|Persistence Option| Type of data saved | Length of time saved |
|------------------|--------------------|----------------------|
|onSavedInstanceSate|key/value (complex values)| While app is open|
|SharePreferences|key/value (primitive values)|Between app and phone restarts|
|SQLite database|organized,more complicated text/numerica/boolean data|Between app and phone restarts|
|Internal/External storage|multimedia or large data|Between app and phone restarts|
|Server(ex. Firebase)|data that multiple phones will access|Between app and phones restarts,deletting app, using a different phone.|
