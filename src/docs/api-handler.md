# API Handler

## class APIHandler

## Constructors

### constructor

\+ **new APIHandler**(`client`: Client): APIHandler

#### Parameters:

| Name     | Type   |
| :------- | :----- |
| `client` | Client |

**Returns:** APIHandler

Defined in: [src/APIHandler.ts:10](https://github.com/Gencord/gencord/blob/a52c25b/src/APIHandler.ts#L10)

## Interfaces

### APIOptions

| Name       | Type                                  |
| :--------- | :------------------------------------ |
| `endpoint` | string                                |
| `method`   | GET \| POST \| DELETE \| PUT \| PATCH |
| `body?`    | any                                   |

## Methods

### fetch

▸ **fetch**(`options`: APIOptions): _Promise_<void\>

#### Parameters:

| Name      | Type       |
| :-------- | :--------- |
| `options` | APIOptions |

**Returns:** _Promise_<void\>

Defined in: [src/APIHandler.ts:13](https://github.com/Gencord/gencord/blob/a52c25b/src/APIHandler.ts#L13)
