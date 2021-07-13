# CompilationJob.CreateFromString Method

Creates a new [`CompilationJob`](/api/csharp/yarn.compiler/compilationjob.md) using the contents
of a string.


```csharp
public static CompilationJob CreateFromString(string fileName, string source, Library library = null)
```

## Parameters
|Parameter|Description|
|:---|:---|
|[`string`](https://docs.microsoft.com/dotnet/api/System.String) fileName|The name to assign to the compiled file.|
|[`string`](https://docs.microsoft.com/dotnet/api/System.String) source|The text to compile.|
|[`Library`](/api/csharp/yarn/library.md) library||
## Return Type
[`CompilationJob`](/api/csharp/yarn.compiler/compilationjob.md): A new [`CompilationJob`](/api/csharp/yarn.compiler/compilationjob.md).



<div class="class-metadata">

Parent: [`CompilationJob`](/api/csharp/yarn.compiler/compilationjob.md), Namespace: [`Yarn.Compiler`](/api/csharp/yarn.compiler/README.md), Assembly: YarnSpinner.Compiler.dll
</div>

## Source
Defined in [YarnSpinner.Compiler/Compiler.cs](https://github.com/YarnSpinnerTool/YarnSpinner//blob/develop/YarnSpinner.Compiler/Compiler.cs#L533), line 533.