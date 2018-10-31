# MarketingForm

  
 **Chiavi**

* _Id_
* AccountId, FormTypeId

| Campo | Descrizione | Tipo | Dimensione | Note |
| :--- | :--- | :--- | :--- | :--- |
| AccountId | Id del cliente | text | 50 |  |
| CreationDate | Data di creazione | dt |  |  |
| CreatorId | Id dell'agente che ha creato il record | text | 50 |  |
| EntityStatus | Campo che definisce lo stato del record | enum |  | 0: ImportedFromErp, 1: ExportedToErp, 2: ImportedByErp, 3: ExportingToErp, 4: Deleted, 5: CommittingExportToErp, 6: ToExportToErp, 7: Editing, 8: UploadedToServer |
| FormFamilyId | Id della famiglia della scheda marketing | text | 50 |  |
| FormTypeId | Id del tipo di scheda marketing | text | 50 |  |
| Id | Id | text | 50 |  |
| IsDeleted | Indica se il record è stato cancellato | bool |  |  |
| LastModifiedTimeStamp | Data dell'ultima modifica | dt |  |  |
| LastModifiedUserId | Id dell'agente che ha effettuato l'ultima modifica | text | 50 |  |
| RegistryTypeId | Id del tipo di registrazione | text | 50 |  |
| SyncReference | Riferimento | text | 50 |  |
| UploadToServerTimeStamp |  | dt |  |  |
