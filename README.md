# Brief Reference ASP.NET
Brief reference of the ASP.NET framework.

---

#### Use static files
```
public void Configure(IApplicationBuilder app, IWebHostEnvironment env)
{
    app.UseStaticFiles();
}

NOTE: The static files must be on wwwroot folder (on the root).
```
