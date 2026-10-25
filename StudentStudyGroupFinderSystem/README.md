# Student Study Group Finder System

Layered Java console app (Maven + SQLite).

## Run
```
mvn compile exec:java
```
Requires Java 17+ and Maven.

## Structure
- `dao` - DatabaseConnection, UserDao (all SQL, PreparedStatement)
- `model` - User (record)
- `ui` - MenuUI (menus)
- `Main.java` - entry point
