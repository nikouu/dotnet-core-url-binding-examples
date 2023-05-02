# .NET Core URL Binding Examples

👀 I wrote about this here: [What Does Asterisk *, Plus +, and Double Colon :: Mean in ASP.NET Core URLs?](https://www.nikouusitalo.com/blog/what-does-asterisk-plus-and-double-colon-mean-in-asp-net-core-urls/)

A repo designed just to simply test out [different bindings](https://learn.microsoft.com/en-us/aspnet/core/fundamentals/servers/kestrel/endpoints?view=aspnetcore-7.0#url-prefixes).

To play around with this head over to appsettings.json and change the URLs. For example, you could change them to any of the following:

```
http://*:5400
http://+:5401
http://€:5400
http://*-+!@#$%^&*():5401
http://0.0.0.0:5400
http://[::]:5400
```
