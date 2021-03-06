# Operators.Checked Module (F#)

This module contains the basic arithmetic operations with overflow checks.

**Namespace/Module Path:** Microsoft.FSharp.Core.Operators

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## [!INCLUDE[System_CAPS_syntax](//System/Token/System_CAPS_syntax_md.md)]

```
module Checked
```

## [!INCLUDE[System_CAPS_remarks](//System/Token/System_CAPS_remarks_md.md)]

## Values


|Value|Description|
|-----|-----------|
|[( &#42; )](http://msdn.microsoft.com/en-us/library/8a3edb1d-f221-4393-b64b-4e790e177b55)<br />**: ^T1 -&gt; ^T2 -&gt; ^T3**|Overloaded multiplication operator (checks for overflow).|
|[( + )](http://msdn.microsoft.com/en-us/library/e33c5aea-8454-4fba-b471-1e833e21d3ea)<br />**: ^T1 -&gt; 'T2 -&gt; 'T3**|Overloaded addition operator (checks for overflow).|
|[( - )](http://msdn.microsoft.com/en-us/library/7c16d973-2ab5-4689-8f01-2fd3a79fe536)<br />**: ^T1 -&gt; ^T2 -&gt; ^T3**|Overloaded subtraction operator (checks for overflow).|
|[( ~- )](http://msdn.microsoft.com/en-us/library/4fa7cd12-8c9f-495f-8741-e5da3d28fd19)<br />**: ^T -&gt; ^T**|Overloaded unary negation (checks for overflow).|
|[byte](http://msdn.microsoft.com/en-us/library/31fafa71-165c-4d79-9e99-551a0334cd4b)<br />**: ^T -&gt; byte**|Converts the argument to **byte**. This is a direct, checked conversion for all primitive numeric types. For strings, the input is converted using **M:System.Byte.Parse(System.String)** with **P:System.Globalization.CultureInfo.InvariantCulture** settings. Otherwise the operation requires an appropriate static conversion method on the input type.|
|[char](http://msdn.microsoft.com/en-us/library/e36ef4bf-61bc-4a08-82b8-91467c889e36)<br />**: ^T -&gt; char**|Converts the argument to **char**. Numeric inputs are converted using a checked conversion according to the UTF-16 encoding for characters. String inputs must be exactly one character long. For other input types the operation requires an appropriate static conversion method on the input type.|
|[int](http://msdn.microsoft.com/en-us/library/3237522e-6e71-436c-b3bf-837ea5a503e4)<br />**: ^T -&gt; int**|Converts the argument to **int**. This is a direct, checked conversion for all primitive numeric types. For strings, the input is converted using **M:System.Int32.Parse(System.String)** with **P:System.Globalization.CultureInfo.InvariantCulture** settings. Otherwise the operation requires an appropriate static conversion method on the input type.|
|[int16](http://msdn.microsoft.com/en-us/library/789392fc-85a7-482e-8abb-f0ae68a7042b)<br />**: ^T -&gt; int16**|Converts the argument to **int16**. This is a direct, checked conversion for all primitive numeric types. For strings, the input is converted using **M:System.Int16.Parse(System.String)** with **P:System.Globalization.CultureInfo.InvariantCulture** settings. Otherwise the operation requires an appropriate static conversion method on the input type.|
|[int32](http://msdn.microsoft.com/en-us/library/6c6f30b6-c960-4137-9c73-d477ae32a287)<br />**: ^T -&gt; int32**|Converts the argument to **int32**. This is a direct, checked conversion for all primitive numeric types. For strings, the input is converted using **M:System.Int32.Parse(System.String)** with **P:System.Globalization.CultureInfo.InvariantCulture** settings. Otherwise the operation requires an appropriate static conversion method on the input type.|
|[int64](http://msdn.microsoft.com/en-us/library/ec10ef63-eb41-4fa6-a65c-0a07beec5656)<br />**: ^T -&gt; int64**|Converts the argument to **int64**. This is a direct, checked conversion for all primitive numeric types. For strings, the input is converted using **M:System.Int64.Parse(System.String)** with **P:System.Globalization.CultureInfo.InvariantCulture** settings. Otherwise the operation requires an appropriate static conversion method on the input type.|
|[nativeint](http://msdn.microsoft.com/en-us/library/876c5aa7-683f-4912-a799-161732109c4f)<br />**: ^T -&gt; nativeint**|Converts the argument to **nativeint**. This is a direct, checked conversion for all primitive numeric types. Otherwise the operation requires an appropriate static conversion method on the input type.|
|[sbyte](http://msdn.microsoft.com/en-us/library/f9d2a1db-8fd7-4e08-8e07-f3b2cc8f64f7)<br />**: ^T -&gt; sbyte**|Converts the argument to **sbyte**. This is a direct, checked conversion for all primitive numeric types. For strings, the input is converted using **M:System.SByte.Parse(System.String)** with **P:System.Globalization.CultureInfo.InvariantCulture** settings. Otherwise the operation requires an appropriate static conversion method on the input type.|
|[uint16](http://msdn.microsoft.com/en-us/library/46d0450e-bf89-42cb-ae1c-fc04ad4eaf02)<br />**: ^T -&gt; uint16**|Converts the argument to **uint16**. This is a direct, checked conversion for all primitive numeric types. For strings, the input is converted using **M:System.UInt16.Parse(System.String)** with **P:System.Globalization.CultureInfo.InvariantCulture** settings. Otherwise the operation requires an appropriate static conversion method on the input type.|
|[uint32](http://msdn.microsoft.com/en-us/library/cccb755b-2e72-47f9-a1ae-cdf53a5aac7f)<br />**: ^T -&gt; uint32**|Converts the argument to **uint32**. This is a direct, checked conversion for all primitive numeric types. For strings, the input is converted using **M:System.UInt32.Parse(System.String)** with **P:System.Globalization.CultureInfo.InvariantCulture** settings. Otherwise the operation requires an appropriate static conversion method on the input type.|
|[uint64](http://msdn.microsoft.com/en-us/library/70fa85e1-3322-4514-a145-fbad90ae9667)<br />**: ^T -&gt; uint64**|Converts the argument to **uint64**. This is a direct, checked conversion for all primitive numeric types. For strings, the input is converted using **M:System.UInt64.Parse(System.String)** with **P:System.Globalization.CultureInfo.InvariantCulture** settings. Otherwise the operation requires an appropriate static conversion method on the input type.|
|[unativeint](http://msdn.microsoft.com/en-us/library/97cec2c5-0e55-4bbe-826b-219a1c08d3a7)<br />**: ^T -&gt; unvativeint**|Converts the argument to **unativeint**. This is a direct, checked conversion for all primitive numeric types. Otherwise the operation requires an appropriate static conversion method on the input type.|

## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Core.Operators Module &#40;F&#35;&#41;](Core.Operators+Module+28%F%2329%.md)

