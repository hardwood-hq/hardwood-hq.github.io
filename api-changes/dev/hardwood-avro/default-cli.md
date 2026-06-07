
# Compatibility Report

![semver MINOR](https://img.shields.io/badge/semver-MINOR-orange?logo=semver "semver MINOR")

## Summary

> [!WARNING]
>
> Compatible changes found while checking backward compatibility of version `1.0.0-SNAPSHOT` with the previous version `unknown`.

<details markdown="1">
<summary>Expand to see options used.</summary>

- **Report only summary**: No
- **Report only changes**: Yes
- **Report only binary-incompatible changes**: No
- **Access modifier filter**: `PROTECTED`
- **Old archives**:
- **New archives**:
  - ![hardwood-avro 1.0.0-SNAPSHOT](https://img.shields.io/badge/hardwood_avro-1.0.0_SNAPSHOT-blue "hardwood-avro 1.0.0-SNAPSHOT")
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

| Status | Type                                             | Serialization       | Compatibility Changes |
|--------|--------------------------------------------------|---------------------|-----------------------|
| Added  | [dev.hardwood.avro.AvroReaders]                  | ![Not serializable] | ![Method added to public class] |
| Added  | [dev.hardwood.avro.AvroReaders$RowReaderBuilder] | ![Not serializable] | ![Method added to public class] |
| Added  | [dev.hardwood.avro.AvroRowReader]                | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.avro.internal.AvroSchemaConverter] | ![Not serializable] | ![Method added to public class] |

<details markdown="1">
<summary>Expand for details.</summary>

___

<a id="user-content-dev.hardwood.avro.avroreaders"></a>
### `dev.hardwood.avro.AvroReaders`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                | Type      | Name              | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|--------------------------|-----------|-------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`public`** | **Class** | **`AvroReaders`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers                 | Generics | Type                     | Method                                      | Annotations | Throws | Compatibility Changes |
|--------|---------------------------|----------|--------------------------|---------------------------------------------|-------------|--------|-----------------------|
| Added  | **`static`** **`public`** |          | **[`RowReaderBuilder`]** | **`buildRowReader`**([`ParquetFileReader`]) |             |        | ![Method added to public class] |
| Added  | **`static`** **`public`** |          | **[`AvroRowReader`]**    | **`rowReader`**([`ParquetFileReader`])      |             |        | ![Method added to public class] |

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

| Status | Modifiers    | Type      | Name                | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|--------------|-----------|---------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`public`** | **Class** | **`AvroRowReader`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface             | Compatibility Changes |
|--------|-----------------------|-----------------------|
| Added  | **[`AutoCloseable`]** | ![No changes]         |


#### Methods

| Status | Modifiers    | Generics | Type                  | Method            | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-----------------------|-------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`void`**            | **`close`**()     |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`Schema`]**        | **`getSchema`**() |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **`boolean`**         | **`hasNext`**()   |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`GenericRecord`]** | **`next`**()      |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.avro.internal.avroschemaconverter"></a>
### `dev.hardwood.avro.internal.AvroSchemaConverter`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                | Type      | Name                      | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|--------------------------|-----------|---------------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`public`** | **Class** | **`AvroSchemaConverter`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers                 | Generics | Type           | Method                        | Annotations | Throws | Compatibility Changes |
|--------|---------------------------|----------|----------------|-------------------------------|-------------|--------|-----------------------|
| Added  | **`static`** **`public`** |          | **[`Schema`]** | **`convert`**([`FileSchema`]) |             |        | ![Method added to public class] |


</details>


___

*Generated on: 2026-06-07 19:06:22.768+0000*.

[Interface added]: https://img.shields.io/badge/Interface_added-orange "Interface added"
[Method added to public class]: https://img.shields.io/badge/Method_added_to_public_class-yellow "Method added to public class"
[No changes]: https://img.shields.io/badge/No_changes-green "No changes"
[Not serializable]: https://img.shields.io/badge/Not_serializable-green "Not serializable"
[`AutoCloseable`]: # "java.lang.AutoCloseable"
[`AvroRowReader`]: # "dev.hardwood.avro.AvroRowReader"
[`ColumnProjection`]: # "dev.hardwood.schema.ColumnProjection"
[`FileSchema`]: # "dev.hardwood.schema.FileSchema"
[`FilterPredicate`]: # "dev.hardwood.reader.FilterPredicate"
[`GenericRecord`]: # "org.apache.avro.generic.GenericRecord"
[`Object`]: # "java.lang.Object"
[`ParquetFileReader`]: # "dev.hardwood.reader.ParquetFileReader"
[`RowReaderBuilder`]: # "dev.hardwood.avro.AvroReaders$RowReaderBuilder"
[`Schema`]: # "org.apache.avro.Schema"
[dev.hardwood.avro.AvroReaders]: #user-content-dev.hardwood.avro.avroreaders
[dev.hardwood.avro.AvroReaders$RowReaderBuilder]: #user-content-dev.hardwood.avro.avroreaders$rowreaderbuilder
[dev.hardwood.avro.AvroRowReader]: #user-content-dev.hardwood.avro.avrorowreader
[dev.hardwood.avro.internal.AvroSchemaConverter]: #user-content-dev.hardwood.avro.internal.avroschemaconverter
