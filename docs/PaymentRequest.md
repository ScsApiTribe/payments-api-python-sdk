# PaymentRequest

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**amount** | **float** | The gross amount in Swiss Francs (CHF). Includes the VAT. Negative value represents refund. | 
**description** | **str** | The description or purpose of the payment to be shown on the bill. The description should be encoded in ISO-8859-1 charset, since those are guaranteed to be properly printed on the Swisscom bill. | 
**idempotency_key** | **str** | The key identifier provided by the API consumer used so that the same payment transaction cannot be made twice.For example, if a request to create a charge fails due to a network connection error, you can retry the request with the same idempotency key to guarantee that only a single charge is created. | 
**payer_id** | [**PaymentRequestPayerId**](PaymentRequestPayerId.md) |  | [optional] 
**tax_rate** | **float** | Tax rate (VAT) expressed in percent. Valid values 0.0, 2.5, 8.0. Default value is 0.0 | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


