<<<<<<< HEAD
# collab
=======
# android

# Architecture Overview

Clean architectures was used to build this project. Specifically MVI. with all layers: domain, data and presentation
Separating everything in their packages to keep everything clean and readable for future developers.


## API endpoints used

### @GET("/api/Auth/departments")
### @GET list of departments
### @POST("/api/Auth/login")
### @POST("/api/Auth/register")
### @GET("/api/Events/categories")
### @POST("/api/Registration/register")
### @DELETE("/api/Registration/unregister/{eventId}")
### @GET("/api/Registration/check/{eventId}")
### @GET("/api/Events/sorted-by-upcoming-date")
### @GET("/api/Events/sorted-by-popularity")
### @GET("/api/Events/{id}")

## Known limitations

Some things are hardcoded, e.g. FAQ. Most of the things could come from the server.

## Future improvement suggestions

Imrpove UI/UX.
>>>>>>> 898a5b9 (initial commit)
