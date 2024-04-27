# # ShipmentDTO

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Идентификатор отгрузки. | [optional]
**plan_interval_from** | **\DateTime** | Начало планового интервала отгрузки. | [optional]
**plan_interval_to** | **\DateTime** | Конец планового интервала отгрузки. | [optional]
**shipment_type** | [**\YandexMarketApi\Model\ShipmentType**](ShipmentType.md) |  | [optional]
**warehouse** | [**\YandexMarketApi\Model\PartnerShipmentWarehouseDTO**](PartnerShipmentWarehouseDTO.md) |  | [optional]
**warehouse_to** | [**\YandexMarketApi\Model\PartnerShipmentWarehouseDTO**](PartnerShipmentWarehouseDTO.md) |  | [optional]
**external_id** | **string** | Идентификатор отгрузки в вашей системе. Если вы еще не передавали идентификатор, вернется идентификатор из параметра &#x60;id&#x60;. | [optional]
**delivery_service** | [**\YandexMarketApi\Model\DeliveryServiceDTO**](DeliveryServiceDTO.md) |  | [optional]
**pallets_count** | [**\YandexMarketApi\Model\PalletsCountDTO**](PalletsCountDTO.md) |  | [optional]
**order_ids** | **int[]** | Идентификаторы заказов в отгрузке. | [optional]
**draft_count** | **int** | Количество заказов, запланированных к отгрузке. | [optional]
**planned_count** | **int** | Количество отгруженных заказов. | [optional]
**fact_count** | **int** | Количество заказов, принятых в сортировочном центре или пункте приема. | [optional]
**current_status** | [**\YandexMarketApi\Model\ShipmentStatusChangeDTO**](ShipmentStatusChangeDTO.md) |  | [optional]
**available_actions** | [**\YandexMarketApi\Model\ShipmentActionType[]**](ShipmentActionType.md) | Доступные действия над отгрузкой. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
