# get-configuration output Schema

```txt
http://schema.nethserver.org/matrix/get-configuration-output.json
```

Get Matrix configuration

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                   |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [get-configuration-output.json](matrix/get-configuration-output.json "open original schema") |

## get-configuration output Type

`object` ([get-configuration output](get-configuration-output.md))

## get-configuration output Examples

```json
{
  "synapse_domain_name": "matrix.example.com",
  "element_domain_name": "chat.example.com"
}
```

# get-configuration output Properties

| Property                                      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                 |
| :-------------------------------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [synapse\_domain\_name](#synapse_domain_name) | `string` | Optional | cannot be null | [get-configuration output](get-configuration-output-properties-synapse_domain_name.md "http://schema.nethserver.org/matrix/get-configuration-output.json#/properties/synapse_domain_name") |
| [element\_domain\_name](#element_domain_name) | `string` | Optional | cannot be null | [get-configuration output](get-configuration-output-properties-element_domain_name.md "http://schema.nethserver.org/matrix/get-configuration-output.json#/properties/element_domain_name") |

## synapse\_domain\_name

Fully qualified domain name for the Matrix homeserver

`synapse_domain_name`

* is optional

* Type: `string`

* cannot be null

* defined in: [get-configuration output](get-configuration-output-properties-synapse_domain_name.md "http://schema.nethserver.org/matrix/get-configuration-output.json#/properties/synapse_domain_name")

### synapse\_domain\_name Type

`string`

## element\_domain\_name

Fully qualified domain name for the Element web client

`element_domain_name`

* is optional

* Type: `string`

* cannot be null

* defined in: [get-configuration output](get-configuration-output-properties-element_domain_name.md "http://schema.nethserver.org/matrix/get-configuration-output.json#/properties/element_domain_name")

### element\_domain\_name Type

`string`
