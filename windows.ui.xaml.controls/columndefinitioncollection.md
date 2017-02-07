---
-api-id: T:Windows.UI.Xaml.Controls.ColumnDefinitionCollection
-api-type: winrt class
---

<!-- Class syntax.
public class ColumnDefinitionCollection : Windows.Foundation.Collections.IIterable<Windows.UI.Xaml.Controls.ColumnDefinition>, Windows.Foundation.Collections.IVector<Windows.UI.Xaml.Controls.ColumnDefinition>
-->

# Windows.UI.Xaml.Controls.ColumnDefinitionCollection

## -description
Provides access to an ordered, strongly typed collection of [ColumnDefinition](columndefinition.md) objects.

## -xaml-syntax
```xaml
<Grid ...>
  <Grid.ColumnDefinitions>
    oneOrMoreColumnDefinitions
  </Grid.ColumnDefinitions>
</Grid>
```


## -remarks
<!--Begin NET note for IEnumerable support-->
### Enumerating the collection in C# or Microsoft Visual Basic

A [ColumnDefinitionCollection](columndefinitioncollection.md) is enumerable, so you can use language-specific syntax such as **foreach** in C# to enumerate the items in the collection. The compiler does the type-casting for you and you won't need to cast to `IEnumerable<ColumnDefinition>` explicitly. If you do need to cast explicitly, for example if you want to call [GetEnumerator](XREF:TODO:M:System.Collections.Generic.IEnumerable`1.GetEnumerator), cast to [IEnumerable&lt;T&gt;](XREF:TODO:T:System.Collections.Generic.IEnumerable`1) with a [ColumnDefinition](columndefinition.md) constraint.


<!--End NET note for IEnumerable support-->

## -examples

## -see-also
[Grid](grid.md), [ColumnDefinition](columndefinition.md), [IVector&lt;T&gt;](../windows.foundation.collections/ivector_1.md), [IIterable&lt;T&gt;](../windows.foundation.collections/iiterable_1.md), [IList&lt;T&gt;](XREF:TODO:T:System.Collections.Generic.IList`1)