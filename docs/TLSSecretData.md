# TLSSecretData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TlsCrt** | Pointer to **string** |  | [optional] 
**TlsKey** | Pointer to **string** |  | [optional] 

## Methods

### NewTLSSecretData

`func NewTLSSecretData() *TLSSecretData`

NewTLSSecretData instantiates a new TLSSecretData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTLSSecretDataWithDefaults

`func NewTLSSecretDataWithDefaults() *TLSSecretData`

NewTLSSecretDataWithDefaults instantiates a new TLSSecretData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTlsCrt

`func (o *TLSSecretData) GetTlsCrt() string`

GetTlsCrt returns the TlsCrt field if non-nil, zero value otherwise.

### GetTlsCrtOk

`func (o *TLSSecretData) GetTlsCrtOk() (*string, bool)`

GetTlsCrtOk returns a tuple with the TlsCrt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTlsCrt

`func (o *TLSSecretData) SetTlsCrt(v string)`

SetTlsCrt sets TlsCrt field to given value.

### HasTlsCrt

`func (o *TLSSecretData) HasTlsCrt() bool`

HasTlsCrt returns a boolean if a field has been set.

### GetTlsKey

`func (o *TLSSecretData) GetTlsKey() string`

GetTlsKey returns the TlsKey field if non-nil, zero value otherwise.

### GetTlsKeyOk

`func (o *TLSSecretData) GetTlsKeyOk() (*string, bool)`

GetTlsKeyOk returns a tuple with the TlsKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTlsKey

`func (o *TLSSecretData) SetTlsKey(v string)`

SetTlsKey sets TlsKey field to given value.

### HasTlsKey

`func (o *TLSSecretData) HasTlsKey() bool`

HasTlsKey returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


