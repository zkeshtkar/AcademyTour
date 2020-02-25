# Add assambly name and c# versions to projects

`<langversion>option</langversion>` Causes the compiler to accept only syntax that is included in the chosen C# language specification.

## Arguments  
 `option`  
 The following values are valid:  
  
|Option|Meaning|  
|------------|-------------|  
|default|The compiler accepts all valid language syntax that it can support. <sup id="TDefault">[Default](#FDefault)</sup>| 
|ISO-1|The compiler accepts only syntax that is included in ISO/IEC 23270:2003 C# (1.0/1.1) <sup id="TISO1">[ISO1](#FISO1)</sup>|  
|ISO-2|The compiler accepts only syntax that is included in ISO/IEC 23270:2006 C# (2.0) <sup id="TISO2">[ISO2](#FISO2)</sup>|
|3|The compiler accepts only syntax that is included in C# 3.0 or lower <sup id="TCS3">[CS3](#FCS3)</sup>|
|4|The compiler accepts only syntax that is included in C# 4.0 or lower <sup id="TCS4">[CS4](#FCS4)</sup>|
|5|The compiler accepts only syntax that is included in C# 5.0 or lower <sup id="TCS5">[CS5](#FCS5)</sup>|
|6|The compiler accepts only syntax that is included in C# 6.0 or lower <sup id="TCS6">[CS6](#FCS6)</sup>|
|7|The compiler accepts only syntax that is included in C# 7.0 or lower <sup id="TCS7">[CS7](#FCS7)</sup>|
|latest|The compiler accepts all valid language syntax that it can support. <sup id="TLatest">[Latest](#FLatest)</sup>|
|7.1|The compiler accepts only syntax that is included in C# 7.1 or lower <sup id="TCS71">[CS71](#FCS71)</sup>|
|7.2|The compiler accepts only syntax that is included in C# 7.2 or lower <sup id="TCS71">[CS72](#FCS72)</sup>|
|8|The compiler accepts only syntax that is included in C# 8 or lower <sup id="TCS71">[CS8](#FCS8)</sup>|

## Add build properties

You can add build properties to the project file to further control the build. Now add this  property:

   1. An AssemblyName property to specify the name of the application.

    
    <PropertyGroup>
    <AssemblyName>MSBuildSample</AssemblyName>
    </PropertyGroup>
    

 
### Refrences

1. https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/configure-language-version

2. https://docs.microsoft.com/en-us/visualstudio/msbuild/walkthrough-creating-an-msbuild-project-file-from-scratch?view=vs-2019

3. https://stackoverflow.com/questions/40204195/c-sharp-output-assembly-filename-csproj

4. https://stackoverflow.com/questions/50502570/change-assembly-name-for-build-settings-in-csproj


