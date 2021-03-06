---
-api-id: M:Windows.Storage.PathIO.ReadLinesAsync(System.String,Windows.Storage.Streams.UnicodeEncoding)
-api-type: winrt method
---

<!-- Method syntax
public Windows.Foundation.IAsyncOperation<Windows.Foundation.Collections.IVector<string>> ReadLinesAsync(System.String absolutePath, Windows.Storage.Streams.UnicodeEncoding encoding)
-->

# Windows.Storage.PathIO.ReadLinesAsync

## -description
Reads the contents of the file at the specified path or Uniform Resource Identifier (URI) using the specified character encoding and returns lines of text.

## -parameters
### -param absolutePath
The path of the file to read.

### -param encoding
The character encoding of the file.

## -returns
When this method completes successfully, it returns the contents of the file as a list (type [IVector](../windows.foundation.collections/ivector_1.md)) of lines of text. Each line of text in the list is represented by a [String](https://docs.microsoft.com/dotnet/api/system.string?redirectedfrom=MSDN) object.

## -remarks

## -examples

## -see-also
[ReadLinesAsync(String)](pathio_readlinesasync_1023781572.md)