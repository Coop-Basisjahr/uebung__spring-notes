# Notes Backend

In dieser Aufgabe erstellst du ein Backend für eine Notiz-App. Das Frontend wurde bereits rudimentär umgesetzt und ist unter `http://localhost:8080` erreichbar, sobald der Server gestartet wurde.

## Endpunkte

Im Frontend wird erwartet, dass das Backend folgende Endpunkte implementiert:

- `GET /api/notes/`: Gibt alle Notes zurück.
- `GET /api/notes/{id}`: Gibt ein einzelnes Note zurück.
- `POST /api/notes/`: Erstellt ein neues Note.
- `PUT /api/notes/{id}`: Aktualisiert ein bestehendes Note.
- `DELETE /api/notes/{id}`: Löscht ein Note

## Note Objekt

Ein Note Objekt sollte folgende Eigenschaften haben.

- `id (int)`
- `content (String)`

## Aufgabe (Spring Web)

Implementiere die genannten Endpunkte, so dass das Frontend fehlerlos mit dem Backend kommunizieren kann.

## Aufgabe (Spring Data)

Verbinde das Backend mit einer Datenbank und speichere die Note Objekte in der Datenbank.
