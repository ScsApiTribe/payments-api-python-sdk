# PaymentDetails

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**amount** | **float** | The gross amount in Swiss Francs (CHF). Includes the VAT. Negative value represents refund. | 
**description** | **str** | The description or purpose of the payment as shown on the bill. | 
**id** | **str** | The payment transaction identifier generated from the API used to track the transaction. | 
**idempotency_key** | **str** | The key identifier provided by the API consumer used so that the same transaction cannot be made twice.For example, if a request to create a charge fails due to a network connection error, you can retry the request with the same idempotency key to guarantee that only a single charge is created. | [optional] 
**payment_status** | **str** | Specifies the status of the payment transaction. eg: billed,accepted,error | [optional] 
**payment_status_details** | **str** | Details in case the payment transaction is in error status. | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


