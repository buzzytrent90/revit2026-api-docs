

Revit 2026 API

# ControlledApplication Events  
  
---  
  
The [ControlledApplication](35859972-2407-3910-cb07-bbb337e307e6.md) type exposes the following members.

|  | Name | Description |
| --- | --- | --- |
|  | [ApplicationInitialized](1d917597-712c-cec3-db2a-8301c62a8ee3.md) | Subscribe to this event to get notified after the Revit application has been initialized. |
|  | [DocumentChanged](f7acc5b4-a1b4-12ca-802b-0ee78942589e.md) | Subscribe to the FailuresProcessingEvent event to be notified when Revit document has changed. |
|  | [DocumentClosed](b089cc05-ba85-03c2-e256-9f18ca7affc9.md) | Subscribe to the DocumentClosing event to be notified when Revit is just about to close a document. |
|  | [DocumentClosing](2f0a7a6f-ed8b-0518-c5f8-edb14b321296.md) | Subscribe to the DocumentClosing event to be notified when Revit is just about to close a document. |
|  | [DocumentCreated](89f514bf-f067-308d-0518-f050450bde72.md) | Subscribe to the DocumentCreated event to be notified immediately after Revit has finished creating a new document. |
|  | [DocumentCreating](5814928c-7794-395a-fdcd-5c3bd13b73ed.md) | Subscribe to the DocumentCreating event to be notified when Revit is just about to create a new document. |
|  | [DocumentOpened](7e5bc7a1-0475-b2ec-0aec-c410015737fe.md) | Subscribe to the DocumentOpened event to be notified immediately after Revit has finished opening a document. |
|  | [DocumentOpening](99a0bcc4-fede-b66b-198d-a53f46ecf149.md) | Subscribe to the DocumentOpening event to be notified when Revit is just about to open a document. |
|  | [DocumentPrinted](2bef4cd3-5ef7-8bf9-1d90-f6e9f875ac28.md) | Subscribe to the DocumentPrinted event to be notified immediately after Revit has finished printing a view or ViewSet of the document. |
|  | [DocumentPrinting](4f2f328a-3f67-4679-0f78-a5ee36ae95db.md) | Subscribe to the DocumentPrinting event to be notified when Revit is just about to print a view or ViewSet of the document. |
|  | [DocumentReloadedLatest](9b16d42f-2b88-d162-b266-8afa5222c439.md) | Subscribe to the DocumentReloadedLatestEventArgs event to be notified immediately after Revit has finished reloading a document with central model. |
|  | [DocumentReloadingLatest](07307104-752f-e7da-b124-793dc35cb5ec.md) | Subscribe to the DocumentReloadingLatestEventArgs event to be notified when Revit is just about to reload latest changes from a central model. |
|  | [DocumentSaved](bb944bb2-2141-4116-339f-4d13b6f6a6a5.md) | Subscribe to the DocumentSaved event to be notified immediately after Revit has finished saving a document. |
|  | [DocumentSavedAs](5a68e38b-2156-eab1-c08b-dbc9a815b618.md) | Subscribe to the DocumentSavedAs event to be notified immediately after Revit has finished saving document with a new file name. |
|  | [DocumentSaving](4a70d25a-c609-0e18-dad4-f34c7c349092.md) | Subscribe to the DocumentSaving event to be notified when Revit is just about to save a document. |
|  | [DocumentSavingAs](ebfb171a-041e-636a-0c9e-62c4706cb146.md) | Subscribe to the DocumentSavingAs event to be notified when Revit is just about to save the document with a new file name. This event is raised when Revit is just about to save the document with a new file name. Note that the first save of a newly created document will raise DocumentSavingAs rather than [DocumentSaving](af9cc434-2934-d407-8ecf-960fc95ac569.md) event.  Handlers of this event are permitted to make modifications to any document (including the active document), except for documents that are currently in read-only mode. This event is cancellable, except when it is raised during close of the application. Check the 'Cancellable' property of event's argument to see whether it is cancellable or not. When it is cancellable, call the 'Cancel()' method of event's argument to cancel it. Your application is responsible for providing feedback to the user about the reason for the cancellation.The following API functions are not available for the current document during this event: |

  * [Close](da2f27b9-7255-4950-82a2-86e1432ff9f0.md) and similar overloads.
  * [Save](8dec13b6-71f4-45d2-74e3-b109153721b5.md) .
  * [SaveAs(String)](25c44d4a-b220-5898-b28c-a2cf6a8a8673.md) and similar overloads.

Exception [InvalidOperationException](9e715f03-3884-e539-4dd6-8d7545733adc.md) will be thrown if any of the above methods is called during this event.Another event [DocumentSavedAs](6d3e2981-dfe0-fd33-9bd0-57e04815c4fd.md) will be raised immediately after the document has been saved with a new file name.  
| [DocumentSynchronizedWithCentral](5cb6e92e-80b0-24e3-943c-a246566e4318.md)|  Subscribe to the DocumentSynchronizedWithCentral event to be notified immediately after Revit has finished synchronizing a document with central model.   
| [DocumentSynchronizingWithCentral](20644173-bd8c-3598-4ac1-4c874679f8e8.md)|  Subscribe to the DocumentSynchronizingWithCentral event to be notified when Revit is just about to synchronize a document with central model.   
| [ElementTypeDuplicated](470b50f6-5f49-a585-4b00-13b4131fb0c2.md)|  Subscribe to the ElementTypeDuplicated event to be notified immediately after Revit has finished duplicating an element type.   
| [ElementTypeDuplicating](d4e741ea-cacc-a592-f2c1-ab2e4aa633bd.md)|  Subscribe to the ElementTypeDuplicating event to be notified when Revit is just about to duplicate an element type.   
| [FailuresProcessing](388605d5-1096-6017-6b3b-f818a36eeffc.md)|  Subscribe to the FailuresProcessing event to be notified when failures are being processed at the end of transaction.   
| [FamilyLoadedIntoDocument](8c607130-85f3-b6e4-bfb9-a9e2404022c1.md)|  Subscribe to the FamilyLoadedInto event to be notified after Revit loaded a family into a document.   
| [FamilyLoadingIntoDocument](f6b8877c-57ae-f0f3-4a65-e87b26ebbd28.md)|  Subscribe to the FamilyLoadingInto event to be notified when Revit is just about to load a family into a document.   
| [FileExported](b319fd4a-07af-ddac-41a2-f1478d4ff100.md)|  Subscribe to the FileExported event to be notified immediately after Revit has finished exporting files of formats supported by the API.   
| [FileExporting](c1f11a68-7712-17bf-dde3-04a077a7e6cf.md)|  Subscribe to the FileExporting event to be notified when Revit is just about to export files of formats supported by the API.   
| [FileImported](53d944f4-4e2a-3625-d4cb-0eb454ed87aa.md)|  Subscribe to the FileImported event to be notified immediately after Revit has finished importing a file of format supported by the API.   
| [FileImporting](5cd9ac35-6b1f-1084-c1f2-55d7dbc3b3ff.md)|  Subscribe to the FileImporting event to be notified when Revit is just about to import a file of format supported by the API.   
| [LinkedResourceOpened](4173dab8-f4da-ea8d-98c5-d6685349f159.md)|  Subscribe to the LinkedResourceOpened event to be notified immediately after Revit has finished opening a linked resource.   
| [LinkedResourceOpening](7b027897-ea2a-a1ac-18b4-c2bd6717923d.md)|  Subscribe to the LinkedResourceOpening event to be notified when Revit is just about to open a linked resource.   
| [ProgressChanged](ec8d2e0e-dc55-d87b-b80a-32a0acce8246.md)|  Subscribe to the ProgressChanged event to be notified when an operation in Revit has progress bar data available.   
| [ViewPrinted](08ae1e5f-e69a-421e-e04a-73f88711967a.md)|  Subscribe to the ViewPrinted event to be notified immediately after Revit has finished printing a view of the document.   
| [ViewPrinting](af45ed82-9ed8-ba3c-56fc-4df00af0cf35.md)|  Subscribe to the ViewPrinting event to be notified when Revit is just about to print a view of the document.   
|  | [WorksharedOperationProgressChanged](9163633b-1939-f5a2-313a-ebb66aa062d0.md) | # Subscribe to the WorksharedOperationProgressChanged to be notified when progress has changed during Collaboration for Revit's workshared operations: open model and synchronize with central. |
  
#### Reference

[ControlledApplication Class](35859972-2407-3910-cb07-bbb337e307e6.md)

[Autodesk.Revit.ApplicationServices Namespace](91957e18-2935-006c-83ab-3b5b9dbb5928.md)