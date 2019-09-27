# IParseContext interface

STL解析上下文。

```csharp
public interface IParseContext
```

## Members

| name | description |
| --- | --- |
| [BodyCodes](IParseContext/BodyCodes.md) { get; } | 生成的Html页面中包含在body标签内的代码。 |
| [ChannelId](IParseContext/ChannelId.md) { get; } | 栏目Id。 |
| [ContentId](IParseContext/ContentId.md) { get; } | 内容Id。 |
| [ContentInfo](IParseContext/ContentInfo.md) { get; } | 内容实体。 |
| [FootCodes](IParseContext/FootCodes.md) { get; } | 生成的Html页面中包含在页面最底部的代码。 |
| [HeadCodes](IParseContext/HeadCodes.md) { get; } | 生成的Html页面中包含在head标签内的代码。 |
| [IsStlElement](IParseContext/IsStlElement.md) { get; } | 判断当前解析的STL标签是STL元素还是STL实体，如果是元素，则返回true；如果是实体，则返回false。 |
| [SiteId](IParseContext/SiteId.md) { get; } | 站点Id。 |
| [StlAttributes](IParseContext/StlAttributes.md) { get; } | 当前解析的STL标签的属性键值集合。 |
| [StlInnerHtml](IParseContext/StlInnerHtml.md) { get; } | 当前解析的STL标签内部的内容。 |
| [StlOuterHtml](IParseContext/StlOuterHtml.md) { get; } | 当前解析的STL标签的完整代码，而不仅限于标签内部的内容。 |
| [TemplateId](IParseContext/TemplateId.md) { get; } | 模板Id。 |
| [TemplateType](IParseContext/TemplateType.md) { get; } | 模板类型。 |
| [Get&lt;T&gt;](IParseContext/Get.md)(…) | 从STL解析上下文中获取指定键的值。 |
| [Set&lt;T&gt;](IParseContext/Set.md)(…) | 将键/值对放入STL解析上下文中，对包含下级标签STL解析情况下共享数据有用。 注意：该数据是不稳定的 —— 它在当前STL解析完成后将丢失。 |

## See Also

* namespace [SiteServer.Plugin](../SiteServer.Plugin.md)

<!-- DO NOT EDIT: generated by xmldocmd for SiteServer.Plugin.dll -->