﻿# &lt;stl:contents&gt; 内容列表

```html
<stl:contents
  align="整体对齐"
  cellPadding="填充"
  cellSpacing="间距"
  channelIndex="栏目索引"
  channelName="栏目名称"
  class="Css类"
  columns="列数"
  direction="方向"
  group="指定显示的内容组"
  groupChannel="指定显示的栏目组"
  groupChannelNot="指定不显示的栏目组"
  groupContent="指定显示的内容组"
  groupContentNot="指定不显示的内容组"
  groupNot="指定不显示的内容组"
  height="整体高度"
  isColor="仅显示醒目内容"
  isDynamic="是否动态显示"
  isFile="仅显示附件内容"
  isHot="仅显示热点内容"
  isImage="仅显示图片内容"
  isNoDup="不显示重复标题的内容"
  isRecommend="仅显示推荐内容"
  isRelatedContents="显示相关内容列表"
  isTop="仅显示置顶内容"
  isVideo="仅显示视频内容"
  itemAlign="项水平对齐"
  itemClass="项Css类"
  itemHeight="项高度"
  itemVerticalAlign="项垂直对齐"
  itemWidth="项宽度"
  layout="指定列表布局方式"
  order="排序"
  scope="内容范围"
  startNum="从第几条信息开始显示"
  tags="指定标签" 
  topLevel="从首页向下的栏目级别"
  totalNum="显示内容数目"
  upLevel="上级栏目的级别"
  where="获取内容列表的条件判断"
  width="整体宽度">
</stl:contents>
```

## 使用说明

通过 stl:contents 标签在模板中显示内容列表

stl:contents是列表标签，用于内容列表循环。
channelIndex="栏目索引"，channelName="栏目名称"，parent="显示父栏目属性"，upLevel="上级栏目的级别"以及topLevel="从首页向下的栏目级别"用于定位到具体的栏目。

## 注意

columns、direction 以及 layout 属性用于控制生成列表的HTML 标签。
columns 控制生成列表的列数，direction 控制生成列表的方向，layout 控制生成列表的HTML标签。
layout 为Table时系统使用 `<table>` 标签生成列表，layout 为Flow时系统使用 `<span>` 标签生成列表，默认为None，即仅循环列表项。

如果需要在内容页中显示与当前内容相关的内容列表，使用 isRelatedContents="true" 属性，系统将根据标签判断是否相关内容。

使用 isNoDup="true" 属性，系统将判断标题时候重复，重复标题的内容只显示一次。

如果设置了 channelIndex 属性，系统将寻找对应此栏目索引的栏目并显示此栏目的内容列表。
如果设置了 channelName 属性，系统将寻找对应此栏目名称的栏目并显示此栏目的内容列表。
如果设置了 parent 或 upLevel 属性，系统将寻找上级或上几级的栏目并对其内容进行循环显示。
如果设置了 topLevel 属性，系统将寻找从首页向下的栏目级别并对其内容进行循环显示。
如果以上属性都未设置，系统将寻找当前栏目并对内容进行循环显示。

`<stl:contents>` 标签对应的实体为{stl:contents}。

## 属性

| 属性              | 说明                   |
| ----------------- | ---------------------- |
| channelIndex      | 栏目索引               |
| channelName       | 栏目名称               |
| upLevel           | 上级栏目的级别         |
| topLevel          | 从首页向下的栏目级别   |
| scope             | 内容范围               |
| groupChannel      | 指定显示的栏目组       |
| groupChannelNot   | 指定不显示的栏目组     |
| group             | 指定显示的内容组       |
| groupNot          | 指定不显示的内容组     |
| groupContent      | 指定显示的内容组       |
| groupContentNot   | 指定不显示的内容组     |
| tags              | 指定标签               |
| isTop             | 仅显示置顶内容         |
| isRecommend       | 仅显示推荐内容         |
| isHot             | 仅显示热点内容         |
| isColor           | 仅显示醒目内容         |
| totalNum          | 显示内容数目           |
| startNum          | 从第几条信息开始显示   |
| order             | 排序                   |
| isImage           | 仅显示图片内容         |
| isVideo           | 仅显示视频内容         |
| isFile            | 仅显示附件内容         |
| isNoDup           | 不显示重复标题的内容   |
| isRelatedContents | 显示相关内容列表       |
| where             | 获取内容列表的条件判断 |
| cellPadding       | 填充                   |
| cellSpacing       | 间距                   |
| class             | Css类                  |
| columns           | 列数                   |
| direction         | 方向                   |
| layout            | 指定列表布局方式       |
| height            | 整体高度               |
| width             | 整体宽度               |
| align             | 整体对齐               |
| itemHeight        | 项高度                 |
| itemWidth         | 项宽度                 |
| itemAlign         | 项水平对齐             |
| itemVerticalAlign | 项垂直对齐             |
| itemClass         | 项Css类                |