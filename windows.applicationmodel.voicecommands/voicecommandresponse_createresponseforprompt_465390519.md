---
-api-id: M:Windows.ApplicationModel.VoiceCommands.VoiceCommandResponse.CreateResponseForPrompt(Windows.ApplicationModel.VoiceCommands.VoiceCommandUserMessage,Windows.ApplicationModel.VoiceCommands.VoiceCommandUserMessage)
-api-type: winrt method
---

<!-- Method syntax
public Windows.ApplicationModel.VoiceCommands.VoiceCommandResponse CreateResponseForPrompt(Windows.ApplicationModel.VoiceCommands.VoiceCommandUserMessage message, Windows.ApplicationModel.VoiceCommands.VoiceCommandUserMessage repeatMessage)
-->

# Windows.ApplicationModel.VoiceCommands.VoiceCommandResponse.CreateResponseForPrompt

## -description
Creates a [VoiceCommandResponse](voicecommandresponse.md) object used in calls to [RequestConfirmationAsync](voicecommandserviceconnection_requestconfirmationasync.md) or [RequestDisambiguationAsync](voicecommandserviceconnection_requestdisambiguationasync.md).

## -parameters
### -param message
The initial message that is spoken by **Cortana** and shown on the **Cortana** canvas. 
This message should be one of the following:

+ An unambiguous question that can be answered with either yes or no on confirmation screens (see [RequestConfirmationAsync](voicecommandserviceconnection_requestconfirmationasync.md)).
+ A request for the user to select from the list of choices presented on disambiguation screens (see [RequestDisambiguationAsync](voicecommandserviceconnection_requestdisambiguationasync.md)).


### -param repeatMessage
The secondary message that is spoken by **Cortana** and shown on the **Cortana** canvas, if a response was not understood.
This message should be both a variation of the first message and one of the following:

+ An unambiguous question that can be answered with either yes or no on confirmation screens (see [RequestConfirmationAsync](voicecommandserviceconnection_requestconfirmationasync.md)).
+ A request for the user to select from the list of choices presented on disambiguation screens (see [RequestDisambiguationAsync](voicecommandserviceconnection_requestdisambiguationasync.md)).


## -returns
The response from the background app service for progress, completion, confirmation, or disambiguation screens displayed on the **Cortana** canvas.

## -remarks

## -examples

## -see-also
[CreateResponseForPrompt(VoiceCommandUserMessage, VoiceCommandUserMessage, IIterable(VoiceCommandContentTile))](voicecommandresponse_createresponseforprompt_1964297975.md), [ elements and attributes v1.2](https://docs.microsoft.com/en-us/uwp/schemas/voicecommands/voice-command-elements-and-attributes-1-2), [Cortana interactions](http://msdn.microsoft.com/library/4c11a7cf-da26-4ca1-a9b9-fe52670101f5), [Cortana design guidelines](http://msdn.microsoft.com/library/a92c084b-9913-4718-9a04-569d51ace55d), [Cortana voice command sample](http://go.microsoft.com/fwlink/p/?LinkID=619899)