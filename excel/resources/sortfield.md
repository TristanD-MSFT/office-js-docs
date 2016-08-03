# SortField Object (JavaScript API for Excel)

_Excel 2016, Excel Online, Excel for iPad, Excel for Mac_

Represents a condition in a sorting operation.

## Properties

| Property	   | Type	|Description| Req. Set|
|:---------------|:--------|:----------|:----|
|ascending|bool|Represents whether the sorting is done in an ascending fashion.|1.2||
|color|string|Represents the color that is the target of the condition if the sorting is on font or cell color.|1.2||
|key|int|Represents the column (or row, depending on the sort orientation) that the condition is on. Represented as an offset from the first column (or row).|1.2||

_See property access [examples.](#property-access-examples)_

## Relationships
| Relationship | Type	|Description| Req. Set|
|:---------------|:--------|:----------|:----|
|dataOption|[SortDataOption](sortdataoption.md)|Represents additional sorting options for this field.|1.2||
|icon|[Icon](icon.md)|Represents the icon that is the target of the condition if the sorting is on the cell's icon.|1.2||
|sortOn|[SortOn](sorton.md)|Represents the type of sorting of this condition.|1.2||

## Methods

| Method		   | Return Type	|Description| Req. Set|
|:---------------|:--------|:----------|:----|
|[load(param: object)](#loadparam-object)|void|Fills the proxy object created in JavaScript layer with property and object values specified in the parameter.|1.1|

## Method Details


### load(param: object)
Fills the proxy object created in JavaScript layer with property and object values specified in the parameter.

#### Syntax
```js
object.load(param);
```

#### Parameters
| Parameter	   | Type	|Description|
|:---------------|:--------|:----------|:---|
|param|object|Optional. Accepts parameter and relationship names as delimited string or an array. Or, provide [loadOption](loadoption.md) object.|

#### Returns
void