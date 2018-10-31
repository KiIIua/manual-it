# Promotion

  
 **Chiavi**

* _Id_

| Campo | Descrizione | Tipo | Dimensione | Note |
| :--- | :--- | :--- | :--- | :--- |
| ActivationMode | Modalità di attivazione | enum |  | 0: Default, 1: Automatic |
| AlternativePaymentId | Id del pagamento alternativo | text | 50 |  |
| CustomerDiscountsRule | Regola per lo sconto cliente | enum |  | 0: Default\_Or\_IncludeForCustomerGroupOnMichelangelo, 1: IncludeForCustomer, 2: IncludeForGrossCost, 3: PreserveDiscountsOnImposedUnitPrice, 4: TakeGrossUnitPrice, 5: TakeNetUnitPrice |
| Description | Descrizione | text | text |  |
| Discount1 | Sconto | dec |  |  |
| Discount2 | Sconto | dec |  |  |
| Discount3 | Sconto | dec |  |  |
| EndDate | Data fine validità | date |  |  |
| GiftFreeQty | Quantità in omaggio nelle promo N+M | dec |  |  |
| GiftPaidQty | Quantità di vendita nelle promo N+M | dec |  |  |
| GiftQtyMode | Indica se la quantità in omaggio è da considerarsi compresa, nelle promo N+M | enum |  | 0: NotIncluded, 1: Included |
| Id | Id | text | 50 |  |
| KitPrice |  | dec |  |  |
| KitQuantity |  | dec |  |  |
| MinAmount | Importo minimo | dec |  |  |
| MinItems | Numero minimo di articoli | int |  |  |
| MinQty | Quantità minima | dec |  |  |
| Notes | Note | text | text |  |
| Number | Numero promozione | text | 50 |  |
| PackUomId |  | text | 20 |  |
| PricePrintingRule | Regole di stampa | enum |  | 0: Print, 1: NoPrint |
| PromotionType | Tipo promozione | enum |  | 0: Classic, 1: Kit, 2: NPlusM, 3: NPlusM\_MonoReference |
| QuantityRange1\_Discount | Sconto | dec |  |  |
| QuantityRange1\_ImposedUnitPrice | Prezzo unitario imposto | dec |  |  |
| QuantityRange1\_Quantity | Quantità | dec |  |  |
| QuantityRange2\_Discount | Sconto | dec |  |  |
| QuantityRange2\_ImposedUnitPrice | Prezzo unitario imposto | dec |  |  |
| QuantityRange2\_Quantity | Quantità | dec |  |  |
| QuantityRange3\_Discount | Sconto | dec |  |  |
| QuantityRange3\_ImposedUnitPrice | Prezzo unitario imposto | dec |  |  |
| QuantityRange3\_Quantity | Quantità | dec |  |  |
| QuantityRange4\_Discount | Sconto | dec |  |  |
| QuantityRange4\_ImposedUnitPrice | Prezzo unitario imposto | dec |  |  |
| QuantityRange4\_Quantity | Quantità | dec |  |  |
| SaleTypeId | Tipo vendita | text | 50 |  |
| StartDate | Data inizio validità | date |  |  |
