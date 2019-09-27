# IDatabaseApi.GetString method (1 of 2)

获取数据库字符串类型值。

```csharp
public string GetString(IDataReader rdr, int i)
```

| parameter | description |
| --- | --- |
| rdr | IDataReader 对象。 |
| i | 位于第几列，从零开始计算。 |

## Return Value

数据库中存储的字符串类型值。

## See Also

* interface [IDatabaseApi](../IDatabaseApi.md)
* namespace [SiteServer.Plugin](../../SiteServer.Plugin.md)

---

# IDatabaseApi.GetString method (2 of 2)

获取数据库字符串类型值。

```csharp
public string GetString(IDataReader rdr, string name)
```

| parameter | description |
| --- | --- |
| rdr | IDataReader 对象。 |
| name | 需要获取的列名称。 |

## Return Value

数据库中存储的字符串类型值。

## See Also

* interface [IDatabaseApi](../IDatabaseApi.md)
* namespace [SiteServer.Plugin](../../SiteServer.Plugin.md)

<!-- DO NOT EDIT: generated by xmldocmd for SiteServer.Plugin.dll -->