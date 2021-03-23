# json-server

Installing JSON Server
```
npm install -g json-server
```

# Running The Server:
Als Parameter müssen wir die Datei mit unserer JSON-Struktur (db.json) übergeben. Außerdem verwenden wir den Parameter - watch. Mit diesem Parameter stellen wir sicher, dass der Server im Watch-Modus gestartet wird, was bedeutet, dass er auf Dateiänderungen achtet und die exponierte API entsprechend aktualisiert.
```
json-server --watch db.json
```
# Browser
Now we can open URL http://localhost:3000/employees in the browser 

# Endpunkte
Die folgenden HTTP-Endpunkte werden automatisch vom JSON-Server erstellt:
```
GET    /employees
GET    /employees/{id}
POST   /employees
PUT    /employees/{id}
PATCH  /employees/{id}
DELETE /employees/{id}
```

http://localhost:3000/employees?first_name=Sebastian
http://localhost:3000/employees?q=codingthesmartway