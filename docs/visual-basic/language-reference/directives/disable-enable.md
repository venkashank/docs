---
title: Enable and Disable directives
ms.date: 01/28/2021
helpviewer_keywords:
  - "directives, enable"
  - "directives, disable"
  - disable directive
---
# #Disable and #Enable directives (Visual Basic)

The `#Disable` and `#Enable` directives are Visual Basic source code compiler directives. They are used to disable and re-enable specific warnings for regions of code.

```vb
' Suppress warning about no awaits in this method.
#Disable Warning BC42356
    Async Function TestAsync() As Task
        Console.WriteLine("testing")
    End Function
#Enable Warning BC42356
```

You can also disable and enable a comma-separated list of warning codes.

## See also

- [Visual Basic Language Reference](../index.md)
- [How to suppress code analysis warnings](../../../fundamentals/code-analysis/suppress-warnings.md)
