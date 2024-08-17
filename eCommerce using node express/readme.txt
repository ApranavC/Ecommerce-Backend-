1 created node app
2 installed all the dependencies bcrypt, jsonwebtoken, express, mongoose
3 created model {
    created server 
    created mongodb database 
    created collection 
    added admin (used bcrypt to hash the password)
}
4 created API for signUp{
    created controller and wrote logic to add user 
    connected the controller to model
    created route which accept post request and handover to controller
    connected app with route
    added midddleware app.use(express.json()) to decode json to jsobject
}

5 Signin {
    created new controller function{
    check if user exist
    check if pass matches
    }
    create access token with given TTL
}

** if controller and route is configured successfully then the API is ready for use 
