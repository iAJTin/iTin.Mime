# MimeMapping.Parse method

Returns the MIME mapping for the specified file extension.

```csharp
public static string Parse(string fileExtension)
```

| parameter | description |
| --- | --- |
| fileExtension | The file extension that is used to determine the MIME type. |

## Return Value

A String that contains the MIME type.

## Examples

The following code example, you get the mime type for pdf extension.

```csharp
using System;   

using iTin.AspNet.Web;

class SampleClass   
{   
    static int Main()   
    {
         // Gets the mime type.
         string mime = MimeMapping.GetMimeMapping("pdf");

         // Print the result => 'application/pdf'
         Console.WriteLine("MIME type for pdf extension is {0}", mime); 
    }
}   
```

## See Also

* class [MimeMapping](../MimeMapping.md)
* namespace [iTin.Mime](../../iTin.Mime.md)

<!-- DO NOT EDIT: generated by xmldocmd for iTin.Mime.dll -->
