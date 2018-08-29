# IUserApi.GetUserInfoByAccount method

通过用户账号获取用户对象实例。

```csharp
public IUserInfo GetUserInfoByAccount(string account)
```

| parameter | description |
| --- | --- |
| account | 用户名、用户邮箱或者用户手机均可作为用户账号。 |

## Return Value

如果用户名、用户邮箱或者用户手机均不存在，则返回 null，否则返回指定的用户对象实例。

## See Also

* interface [IUserInfo](sdk/IUserInfo.md)
* interface [IUserApi](sdk/IUserApi.md)
* namespace [SiteServer.Plugin](sdk/README.md)

<!-- DO NOT EDIT: generated by xmldocmd for SiteServer.Plugin.dll -->