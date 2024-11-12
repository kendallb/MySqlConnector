---
title: MySqlConnectionOpenedConditions
---

# MySqlConnectionOpenedConditions enumeration

Bitflags giving the conditions under which a connection was opened.

```csharp
[Flags]
public enum MySqlConnectionOpenedConditions
```

## Values

| name | value | description |
| --- | --- | --- |
| None | `0x0` | No specific conditions apply. This value may be used when an existing pooled connection is reused without being reset. |
| New | `0x1` | A new physical connection to a MySQL Server was opened. This value is mutually exclusive with Reset. |
| Reset | `0x2` | An existing pooled connection to a MySQL Server was reset. This value is mutually exclusive with New. |

## See Also

* namespace [MySqlConnector](../../MySqlConnectorNamespace/)
* assembly [MySqlConnector](../../MySqlConnectorAssembly/)

<!-- DO NOT EDIT: generated by xmldocmd for MySqlConnector.dll -->