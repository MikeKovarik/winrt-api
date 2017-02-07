---
-api-id: T:Windows.UI.Xaml.Media.Animation.TransitionCollection
-api-type: winrt class
---

<!-- Class syntax.
public class TransitionCollection : Windows.Foundation.Collections.IIterable<Windows.UI.Xaml.Media.Animation.Transition>, Windows.Foundation.Collections.IVector<Windows.UI.Xaml.Media.Animation.Transition>
-->

# Windows.UI.Xaml.Media.Animation.TransitionCollection

## -description
Represents a collection of [Transition](transition.md) objects. Each [Transition](transition.md) object represents a different theme transition, part of the Windows Runtime animation library.

## -xaml-syntax
```xaml
<TransitionCollection>
    oneOrMoreTransitions
</TransitionCollection>
```


## -remarks
[TransitionCollection](transitioncollection.md) is used as the value type for these properties:
+ [Border.ChildTransitions](../windows.ui.xaml.controls/border_childtransitions.md)
+ [ContentControl.ContentTransitions](../windows.ui.xaml.controls/contentcontrol_contenttransitions.md) (on content controls such as [Button](../windows.ui.xaml.controls/button.md) or AppBar)
+ [ContentPresenter.ContentTransitions](../windows.ui.xaml.controls/contentpresenter_contenttransitionsproperty.md)
+ [ItemsControl.ItemContainerTransitions](../windows.ui.xaml.controls/itemscontrol_itemcontainertransitions.md) (on items controls such as [GridView](../windows.ui.xaml.controls/gridview.md), [ListBox](../windows.ui.xaml.controls/listbox.md), [ListView](../windows.ui.xaml.controls/listview.md) and [Selector](../windows.ui.xaml.controls.primitives/selector.md))
+ [ItemsPresenter.FooterTransitions](../windows.ui.xaml.controls/itemspresenter_footertransitions.md)
+ [ItemsPresenter.HeaderTransitions](../windows.ui.xaml.controls/itemspresenter_headertransitions.md)
+ [ListViewBase.FooterTransitions](../windows.ui.xaml.controls/listviewbase_footertransitions.md)
+ [ListViewBase.HeaderTransitions](../windows.ui.xaml.controls/listviewbase_headertransitions.md)
+ [Panel.ChildrenTransitions](../windows.ui.xaml.controls/panel_childrentransitions.md) (on [Grid](../windows.ui.xaml.controls/grid.md), [StackPanel](../windows.ui.xaml.controls/stackpanel.md) and other panels)
+ [Popup.ChildTransitions](../windows.ui.xaml.controls.primitives/popup_childtransitions.md)
+ [SettingsFlyoutTemplateSettings.ContentTransitions](../windows.ui.xaml.controls.primitives/settingsflyouttemplatesettings_contenttransitions.md)
+ [UIElement.Transitions](../windows.ui.xaml/uielement_transitions.md) (on hundreds of classes)




> [!IMPORTANT]
> The XAML syntax for all properties that use a [TransitionCollection](transitioncollection.md) value is unusual in that you must declare an explicit [TransitionCollection](transitioncollection.md) object element as the value, and then provide object elements as child elements of [TransitionCollection](transitioncollection.md) for each of the transition animations you want to use. For most other XAML collection properties you could omit the collection object element because it can be implicit, but properties that use [TransitionCollection](transitioncollection.md) don't support the implicit collection usage. For more info on implicit collections and XAML, see [XAML syntax guide](http://msdn.microsoft.com/library/a57fe7b4-9947-4aa0-bc99-5fe4686b611d).

Transition animations are preconfigured animations from the Windows Runtime animation library. Transition animations run automatically upon the conditions that the transition animation is associated with, using the property owner where the [TransitionCollection](transitioncollection.md) is set as the target. The properties being animated vary depending on which transition you use. 
<!--For more info, see Transition animations and theme animations.-->

[VisualStateGroup.Transitions](../windows.ui.xaml/visualstategroup_transitions.md) does not use the [TransitionCollection](transitioncollection.md) type. [VisualStateGroup.Transitions](../windows.ui.xaml/visualstategroup_transitions.md) uses a built-in collection(list or vector) of [VisualTransition](../windows.ui.xaml/visualtransition.md) objects.


<!--Begin NET note for IEnumerable support-->
### Enumerating the collection in C# or Microsoft Visual Basic

A [TransitionCollection](transitioncollection.md) is enumerable, so you can use language-specific syntax such as **foreach** in C# to enumerate the items in the collection. The compiler does the type-casting for you and you won't need to cast to `IEnumerable<Transition>` explicitly. If you do need to cast explicitly, for example if you want to call [GetEnumerator](XREF:TODO:M:System.Collections.Generic.IEnumerable`1.GetEnumerator), cast to [IEnumerable&lt;T&gt;](XREF:TODO:T:System.Collections.Generic.IEnumerable`1) with a [Transition](transition.md) constraint.


<!--End NET note for IEnumerable support-->

## -examples
This example shows the XAML syntax for setting a [TransitionCollection](transitioncollection.md) object element as part of setting the [UIElement.Transitions](../windows.ui.xaml/uielement_transitions.md) property inline.



[!code-xml[EntranceThemeTransitionSimple](../windows.ui.xaml.media.animation/code/EntranceThemeTransition/csharp/BlankPage.xaml#SnippetEntranceThemeTransitionSimple)]



[!code-xml[EntranceThemeTransitionStyle](../windows.ui.xaml/code/EntranceThemeTransitionStyle/csharp/BlankPage.xaml#SnippetEntranceThemeTransitionStyle)]

## -see-also
[UIElement.Transitions](../windows.ui.xaml/uielement_transitions.md), [ContentControl.ContentTransitions](../windows.ui.xaml.controls/contentcontrol_contenttransitions.md), [Panel.ChildrenTransitions](../windows.ui.xaml.controls/panel_childrentransitions.md), [IVector&lt;T&gt;](../windows.foundation.collections/ivector_1.md), [IIterable&lt;T&gt;](../windows.foundation.collections/iiterable_1.md), [IList&lt;T&gt;](XREF:TODO:T:System.Collections.Generic.IList`1)
d), [IIterable&lt;T&gt;](../windows.foundation.collections/iiterable_1.md), [IList&lt;T&gt;](XREF:TODO:T:System.Collections.Generic.IList`1)