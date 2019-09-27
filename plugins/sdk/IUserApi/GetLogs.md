# IUserApi.GetLogs method

获取用户日志列表。

```csharp
public List<ILogInfo> GetLogs(string userName, int totalNum, string action = "")
```

| parameter | description |
| --- | --- |
| userName | 用户名。 |
| totalNum | 需要获取的日志总数。 |
| action | 动作，可以为空。 |

## Return Value

返回用户日志列表。

## See Also

* interface [ILogInfo](../ILogInfo.md)
* interface [IUserApi](../IUserApi.md)
* namespace [SiteServer.Plugin](../../SiteServer.Plugin.md)

<!-- DO NOT EDIT: generated by xmldocmd for SiteServer.Plugin.dll -->