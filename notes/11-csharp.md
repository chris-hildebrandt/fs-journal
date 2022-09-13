# MVC

notes on dotnet, auth0 and c-sharp
do not put hyphens spaces or hashtags in c# project names. just do camelcase
appsettings is a lot like .eventsprogram.cs is the entrypoint for the app the "using" command is a lot like an import and the startup file has a bunch of using commands like the json from nodejs.
the "[]" in the route, strips off the word in the bracket making the endpoint whatever is left.
a private method inside of a controller means that only the controller itself cac access it.
internal means that anything in the same namespace can access the method.
public, internal, private
c# requires a ternary to null check edit fields.
constructor is a public method with the name of the class ctrl . on the class to make the constructor!!!
rightclick in the controller folder to make a new apicontroller
cannot implicitly convert blah blah blah because ok is an actionresult so you have to include ActionResult<Cat>
start with the model, then make a controller, then the service
rightclick the respositories and click new class
