# SwaggerGenerator class

Generates a Swagger (OpenAPI) 2.0 file for a service definition.

```csharp
public sealed class SwaggerGenerator : CodeGenerator
```

## Public Members

| name | description |
| --- | --- |
| [SwaggerGenerator](SwaggerGenerator/SwaggerGenerator.md)() | The default constructor. |
| [Json](SwaggerGenerator/Json.md) { get; set; } | True to generate JSON (instead of YAML). |
| [GenerateSwaggerService](SwaggerGenerator/GenerateSwaggerService.md)(…) | Generates Swagger (OpenAPI 2.0) for a service definition. |

## Protected Members

| name | description |
| --- | --- |
| override [GenerateOutputCore](SwaggerGenerator/GenerateOutputCore.md)(…) | Generates a Swagger (OpenAPI 2.0) file for a service definition. |

## See Also

* namespace [Facility.Definition.Swagger](../Facility.Definition.Swagger.md)
* [SwaggerGenerator.cs](https://github.com/FacilityApi/FacilitySwagger/tree/master/src/Facility.Definition.Swagger/SwaggerGenerator.cs)

<!-- DO NOT EDIT: generated by xmldocmd for Facility.Definition.Swagger.dll -->