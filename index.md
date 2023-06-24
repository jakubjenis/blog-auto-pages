---
title: Welcome to my blog
---

## Testing home page

``` C#
var app = builder.Build();

// Configure the HTTP request pipeline
if (app.Environment.IsDevelopment())
{
    app.UseSwagger();
    app.UseSwaggerUI();
}

app.MapGet("/", () => "WeatherApi running");
app.MapWeatherApi();
//app.MapControllers();

app.Run();
```