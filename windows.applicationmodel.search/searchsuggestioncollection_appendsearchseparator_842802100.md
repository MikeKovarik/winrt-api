---
-api-id: M:Windows.ApplicationModel.Search.SearchSuggestionCollection.AppendSearchSeparator(System.String)
-api-type: winrt method
---

<!-- Method syntax
public void AppendSearchSeparator(System.String label)
-->

# Windows.ApplicationModel.Search.SearchSuggestionCollection.AppendSearchSeparator

## -description
Appends a text label that is used to separate groups of suggestions in the search pane.

## -parameters
### -param label
The text to use as a separator. This text should be descriptive of any suggestions that are appended after it.

## -remarks
The search pane can display 5 suggestions, at most. Additionally, each separator you use takes the place of a suggestion and decreases the number of suggestions that you can display. Learn more about displaying suggestions in [Guidelines and checklist for search](http://msdn.microsoft.com/library/c328faa3-f6ae-4970-8372-b413f1290c39).




## -examples

## -see-also
[Search contract sample](http://go.microsoft.com/fwlink/p/?linkid=234892), [Guidelines and checklist for search](http://msdn.microsoft.com/library/c328faa3-f6ae-4970-8372-b413f1290c39), [SearchSuggestionCollection class](searchsuggestioncollection.md), [SearchPane.SuggestionsRequested event](searchpane_suggestionsrequested.md), [SearchPaneSuggestionsRequestedEventArgs class](searchpanesuggestionsrequestedeventargs.md), [SearchPaneSuggestionsRequestedEventArgs.Request property](searchpanesuggestionsrequestedeventargs_request.md), [SearchPaneSuggestionsRequest class](searchpanesuggestionsrequest.md), [SearchPaneSuggestionsRequest.SearchSuggestionCollection property](searchpanesuggestionsrequest_searchsuggestioncollection.md)