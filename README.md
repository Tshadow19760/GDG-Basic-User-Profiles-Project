# GDG-Basic-User-Profiles-Project
This is a simple user profile API where users can register, view profiles, and update their information.

## Endpoints:
- POST /users: Registers a new user.
- GET /users: Lists all users.
- GET /users/{user_id}: Retrieves a user profile.
-  PUT /users/{user_id}: Updates user information.
### Example

- Registering a user: 

``` 
    POST /users with {
            "name": "Alice", 
            "email": "alice@example.com", 
            "bio": "Data enthusiast" 
}
```
- Retrieving all users: 
```
    GET /users returns [ { 
            "id": 1, 
            "name": "Alice" 
} ]
```

### Focus

Introducing unique constraints for fields like email and handling updates to user profiles.