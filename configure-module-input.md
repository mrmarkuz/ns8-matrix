# configure-module input Schema

```txt
http://schema.nethserver.org/matrix/configure-module-input.json
```

Configure Matrix chat service

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                               |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [configure-module-input.json](matrix/configure-module-input.json "open original schema") |

## configure-module input Type

`object` ([configure-module input](configure-module-input.md))

## configure-module input Examples

```json
{
  "synapse_domain_name": "matrix.example.com",
  "element_domain_name": "chat.example.com",
  "dex_ldap_domain": "users.example.com"
}
```

# configure-module input Properties

| Property                                      | Type      | Required | Nullable       | Defined by                                                                                                                                                                           |
| :-------------------------------------------- | :-------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [synapse\_domain\_name](#synapse_domain_name) | `string`  | Required | cannot be null | [configure-module input](configure-module-input-properties-synapse_domain_name.md "http://schema.nethserver.org/matrix/configure-module-input.json#/properties/synapse_domain_name") |
| [element\_domain\_name](#element_domain_name) | `string`  | Required | cannot be null | [configure-module input](configure-module-input-properties-element_domain_name.md "http://schema.nethserver.org/matrix/configure-module-input.json#/properties/element_domain_name") |
| [lets\_encrypt](#lets_encrypt)                | `boolean` | Optional | cannot be null | [configure-module input](configure-module-input-properties-lets_encrypt.md "http://schema.nethserver.org/matrix/configure-module-input.json#/properties/lets_encrypt")               |
| [dex\_ldap\_domain](#dex_ldap_domain)         | `string`  | Required | cannot be null | [configure-module input](configure-module-input-properties-dex_ldap_domain.md "http://schema.nethserver.org/matrix/configure-module-input.json#/properties/dex_ldap_domain")         |

## synapse\_domain\_name

Fully qualified domain name for the Matrix homeserver

`synapse_domain_name`

* is required

* Type: `string`

* cannot be null

* defined in: [configure-module input](configure-module-input-properties-synapse_domain_name.md "http://schema.nethserver.org/matrix/configure-module-input.json#/properties/synapse_domain_name")

### synapse\_domain\_name Type

`string`

### synapse\_domain\_name Constraints

**minimum length**: the minimum number of characters for this string is: `1`

**hostname**: the string must be a hostname, according to [RFC 1123, section 2.1](https://tools.ietf.org/html/rfc1123 "check the specification")

## element\_domain\_name

Fully qualified domain name for the Element web client

`element_domain_name`

* is required

* Type: `string`

* cannot be null

* defined in: [configure-module input](configure-module-input-properties-element_domain_name.md "http://schema.nethserver.org/matrix/configure-module-input.json#/properties/element_domain_name")

### element\_domain\_name Type

`string`

### element\_domain\_name Constraints

**minimum length**: the minimum number of characters for this string is: `1`

**hostname**: the string must be a hostname, according to [RFC 1123, section 2.1](https://tools.ietf.org/html/rfc1123 "check the specification")

## lets\_encrypt

Enable Let's Encrypt certificate management

`lets_encrypt`

* is optional

* Type: `boolean`

* cannot be null

* defined in: [configure-module input](configure-module-input-properties-lets_encrypt.md "http://schema.nethserver.org/matrix/configure-module-input.json#/properties/lets_encrypt")

### lets\_encrypt Type

`boolean`

## dex\_ldap\_domain

LDAP domain name for Dex authentication (optional)

`dex_ldap_domain`

* is required

* Type: `string`

* cannot be null

* defined in: [configure-module input](configure-module-input-properties-dex_ldap_domain.md "http://schema.nethserver.org/matrix/configure-module-input.json#/properties/dex_ldap_domain")

### dex\_ldap\_domain Type

`string`

### dex\_ldap\_domain Constraints

**unknown format**: the value of this string must follow the format: `domain-name`
