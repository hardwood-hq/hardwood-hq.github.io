
# Compatibility Report

![semver MAJOR](https://img.shields.io/badge/semver-MAJOR-red?logo=semver "semver MAJOR")

## Summary

> [!CAUTION]
>
> Incompatible changes found while checking backward compatibility of version `1.0.0.Beta2` with the previous version `1.0.0.Beta1`.

<details markdown="1">
<summary>Expand to see options used.</summary>

- **Report only summary**: No
- **Report only changes**: Yes
- **Report only binary-incompatible changes**: No
- **Access modifier filter**: `PROTECTED`
- **Old archives**:
  - ![hardwood-avro 1.0.0.Beta1](https://img.shields.io/badge/hardwood_avro-1.0.0.Beta1-blue "hardwood-avro 1.0.0.Beta1")
- **New archives**:
  - ![hardwood-avro 1.0.0.Beta2](https://img.shields.io/badge/hardwood_avro-1.0.0.Beta2-blue "hardwood-avro 1.0.0.Beta2")
- **Evaluate annotations**: Yes
- **Include synthetic classes and class members**: No
- **Include specific elements**: No
- **Exclude specific elements**: Yes
  - `dev.hardwood.internal`
- **Ignore all missing classes**: No
- **Ignore specific missing classes**: No
- **Treat changes as errors**:
  - Any changes: No
  - Binary incompatible changes: No
  - Source incompatible changes: No
  - Incompatible changes caused by excluded classes: Yes
  - Semantically incompatible changes: No
  - Semantically incompatible changes, including development versions: No
- **Classpath mode**: `ONE_COMMON_CLASSPATH`
- **Old classpath**:
```

```
- **New classpath**:
```

```

</details>


## Results

| Status   | Type                                             | Serialization       | Compatibility Changes |
|----------|--------------------------------------------------|---------------------|-----------------------|
| Modified | [dev.hardwood.avro.AvroReaders]                  | ![Not serializable] | ![Method removed] ![Method added to public class] |
| Added    | [dev.hardwood.avro.AvroReaders$RowReaderBuilder] | ![Not serializable] | ![Method added to public class] |
| Modified | [dev.hardwood.avro.AvroRowReader]                | ![Not serializable] | ![No changes]         |
| Modified | [dev.hardwood.avro.internal.AvroSchemaConverter] | ![Not serializable] | ![No changes]         |

<details markdown="1">
<summary>Expand for details.</summary>

___

<a id="user-content-dev.hardwood.avro.avroreaders"></a>
### `dev.hardwood.avro.AvroReaders`

- [ ] Binary-compatible
- [ ] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers        | Type  | Name          | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|------------------|-------|---------------|------------|--------|---------------------|-----------------------|
| Modified | `final` `public` | Class | `AvroReaders` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Methods

| Status  | Modifiers                 | Generics | Type                     | Method                                       | Annotations | Throws | Compatibility Changes |
|---------|---------------------------|----------|--------------------------|----------------------------------------------|-------------|--------|-----------------------|
| Added   | **`static`** **`public`** |          | **[`RowReaderBuilder`]** | **`buildRowReader`**([`ParquetFileReader`])  |             |        | ![Method added to public class] |
| Removed | ~~`static`~~ ~~`public`~~ |          | ~~[`AvroRowReader`]~~    | ~~`createRowReader`~~([`ParquetFileReader`]) |             |        | ![Method removed]     |
| Removed | ~~`static`~~ ~~`public`~~ |          | ~~[`AvroRowReader`]~~    | ~~`createRowReader`~~([`ParquetFileReader`], [`FilterPredicate`]) |  |  | ![Method removed] |
| Removed | ~~`static`~~ ~~`public`~~ |          | ~~[`AvroRowReader`]~~    | ~~`createRowReader`~~([`ParquetFileReader`], [`ColumnProjection`]) |  |  | ![Method removed] |
| Removed | ~~`static`~~ ~~`public`~~ |          | ~~[`AvroRowReader`]~~    | ~~`createRowReader`~~([`ParquetFileReader`], [`ColumnProjection`], [`FilterPredicate`]) |  |  | ![Method removed] |
| Added   | **`static`** **`public`** |          | **[`AvroRowReader`]**    | **`rowReader`**([`ParquetFileReader`])       |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.avro.avroreaders$rowreaderbuilder"></a>
### `dev.hardwood.avro.AvroReaders$RowReaderBuilder`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name                   | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|------------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`RowReaderBuilder`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers    | Generics | Type                     | Method                                 | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|--------------------------|----------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **[`AvroRowReader`]**    | **`build`**()                          |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`RowReaderBuilder`]** | **`filter`**([`FilterPredicate`])      |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`RowReaderBuilder`]** | **`head`**(`long`)                     |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`RowReaderBuilder`]** | **`projection`**([`ColumnProjection`]) |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`RowReaderBuilder`]** | **`tail`**(`long`)                     |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.avro.avrorowreader"></a>
### `dev.hardwood.avro.AvroRowReader`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers | Type  | Name            | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|-----------|-------|-----------------|------------|--------|---------------------|-----------------------|
| Modified | `public`  | Class | `AvroRowReader` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |

___

<a id="user-content-dev.hardwood.avro.internal.avroschemaconverter"></a>
### `dev.hardwood.avro.internal.AvroSchemaConverter`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers        | Type  | Name                  | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|------------------|-------|-----------------------|------------|--------|---------------------|-----------------------|
| Modified | `final` `public` | Class | `AvroSchemaConverter` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |


</details>


___

*Generated on: 2026-06-05 09:27:08.165+0000*.

[Method added to public class]: https://img.shields.io/badge/Method_added_to_public_class-yellow "Method added to public class"
[Method removed]: https://img.shields.io/badge/Method_removed-red "Method removed"
[No changes]: https://img.shields.io/badge/No_changes-green "No changes"
[Not serializable]: https://img.shields.io/badge/Not_serializable-green "Not serializable"
[`AvroRowReader`]: # "dev.hardwood.avro.AvroRowReader"
[`ColumnProjection`]: # "dev.hardwood.schema.ColumnProjection"
[`FilterPredicate`]: # "dev.hardwood.reader.FilterPredicate"
[`Object`]: # "java.lang.Object"
[`ParquetFileReader`]: # "dev.hardwood.reader.ParquetFileReader"
[`RowReaderBuilder`]: # "dev.hardwood.avro.AvroReaders$RowReaderBuilder"
[dev.hardwood.avro.AvroReaders]: #user-content-dev.hardwood.avro.avroreaders
[dev.hardwood.avro.AvroReaders$RowReaderBuilder]: #user-content-dev.hardwood.avro.avroreaders$rowreaderbuilder
[dev.hardwood.avro.AvroRowReader]: #user-content-dev.hardwood.avro.avrorowreader
[dev.hardwood.avro.internal.AvroSchemaConverter]: #user-content-dev.hardwood.avro.internal.avroschemaconverter
