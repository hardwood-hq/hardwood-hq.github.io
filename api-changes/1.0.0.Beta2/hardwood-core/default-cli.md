
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
  - ![hardwood-core 1.0.0.Beta1](https://img.shields.io/badge/hardwood_core-1.0.0.Beta1-blue "hardwood-core 1.0.0.Beta1")
- **New archives**:
  - ![hardwood-core 1.0.0.Beta2](https://img.shields.io/badge/hardwood_core-1.0.0.Beta2-blue "hardwood-core 1.0.0.Beta2")
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

| Status   | Type                                                         | Serialization       | Compatibility Changes |
|----------|--------------------------------------------------------------|---------------------|-----------------------|
| Modified | [dev.hardwood.Hardwood]                                      | ![Not serializable] | ![Method return type changed] |
| Modified | [dev.hardwood.metadata.ColumnChunk]                          | ![Not serializable] | ![Method added to public class] |
| Added    | [dev.hardwood.metadata.LogicalType$VariantType]              | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Modified | [dev.hardwood.reader.ColumnReader]                           | ![Not serializable] | ![No changes]         |
| Added    | [dev.hardwood.reader.ColumnReaders]                          | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added    | [dev.hardwood.reader.FilterPredicate$UUIDColumnPredicate]    | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Removed  | [dev.hardwood.reader.MultiFileColumnReaders]                 | ![Not serializable] | ![Class removed] ![Superclass removed] ![Interface removed] ![Method removed] |
| Removed  | [dev.hardwood.reader.MultiFileParquetReader]                 | ![Not serializable] | ![Class removed] ![Superclass removed] ![Interface removed] ![Method removed] ![Constructor removed] |
| Removed  | [dev.hardwood.reader.MultiFileRowReader]                     | ![Not serializable] | ![Class removed] ![Superclass removed] ![Interface removed] ![Method removed] |
| Modified | [dev.hardwood.reader.ParquetFileReader]                      | ![Not serializable] | ![Method removed] ![Method added to public class] |
| Added    | [dev.hardwood.reader.ParquetFileReader$ColumnReaderBuilder]  | ![Not serializable] | ![Method added to public class] |
| Added    | [dev.hardwood.reader.ParquetFileReader$ColumnReadersBuilder] | ![Not serializable] | ![Method added to public class] |
| Added    | [dev.hardwood.reader.ParquetFileReader$RowReaderBuilder]     | ![Not serializable] | ![Method added to public class] |
| Modified | [dev.hardwood.reader.RowReader]                              | ![Not serializable] | ![Method added to interface] ![Method new static added to interface] |
| Added    | [dev.hardwood.reader.SchemaIncompatibleException]            | ![Compatible]       | ![Interface added]    |
| Added    | [dev.hardwood.row.FieldAccessor]                             | ![Not serializable] | ![No changes]         |
| Added    | [dev.hardwood.row.PqInterval]                                | ![Not serializable] | ![Method added to public class] |
| Added    | [dev.hardwood.row.PqVariant]                                 | ![Not serializable] | ![No changes]         |
| Added    | [dev.hardwood.row.PqVariantArray]                            | ![Not serializable] | ![Interface added]    |
| Added    | [dev.hardwood.row.PqVariantObject]                           | ![Not serializable] | ![Interface added]    |
| Modified | [dev.hardwood.row.StructAccessor]                            | ![Not serializable] | ![Interface added]    |
| Added    | [dev.hardwood.row.VariantType]                               | ![Compatible]       | ![Interface added] ![Method added to public class] |
| Added    | [dev.hardwood.row.VariantTypeException]                      | ![Compatible]       | ![Interface added] ![Method added to public class] |
| Modified | [dev.hardwood.schema.FileSchema]                             | ![Not serializable] | ![No changes]         |
| Modified | [dev.hardwood.schema.ProjectedSchema]                        | ![Not serializable] | ![Method added to public class] |
| Modified | [dev.hardwood.schema.SchemaNode$GroupNode]                   | ![Not serializable] | ![Method added to public class] ![Constructor removed] |

<details markdown="1">
<summary>Expand for details.</summary>

___

<a id="user-content-dev.hardwood.hardwood"></a>
### `dev.hardwood.Hardwood`

- [ ] Binary-compatible
- [ ] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers | Type  | Name       | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|-----------|-------|------------|------------|--------|---------------------|-----------------------|
| Modified | `public`  | Class | `Hardwood` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Methods

| Status   | Modifiers | Generics | Type                                                            | Method                         | Annotations | Throws          | Compatibility Changes |
|----------|-----------|----------|-----------------------------------------------------------------|--------------------------------|-------------|-----------------|-----------------------|
| Modified | `public`  |          | ~~[`MultiFileParquetReader`]~~ &rarr; **[`ParquetFileReader`]** | `openAll`([`List<InputFile>`]) |             | [`IOException`] | ![Method return type changed] |

___

<a id="user-content-dev.hardwood.metadata.columnchunk"></a>
### `dev.hardwood.metadata.ColumnChunk`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers        | Type  | Name          | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|------------------|-------|---------------|------------|--------|---------------------|-----------------------|
| Modified | `final` `public` | Class | `ColumnChunk` | [`Record`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers    | Generics | Type       | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`long`** | **`chunkStartOffset`**() |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.metadata.logicaltype$varianttype"></a>
### `dev.hardwood.metadata.LogicalType$VariantType`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name              | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|-------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`VariantType`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface           | Compatibility Changes |
|--------|---------------------|-----------------------|
| Added  | **[`LogicalType`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor              | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|--------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`VariantType`**(`int`) |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type           | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|----------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`final`** **`public`** |          | **`boolean`**  | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**      | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`int`**      | **`specVersion`**()      |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`String`]** | **`toString`**()         |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.reader.columnreader"></a>
### `dev.hardwood.reader.ColumnReader`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers | Type  | Name           | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|-----------|-------|----------------|------------|--------|---------------------|-----------------------|
| Modified | `public`  | Class | `ColumnReader` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |

___

<a id="user-content-dev.hardwood.reader.columnreaders"></a>
### `dev.hardwood.reader.ColumnReaders`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers    | Type      | Name                | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|--------------|-----------|---------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`public`** | **Class** | **`ColumnReaders`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface             | Compatibility Changes |
|--------|-----------------------|-----------------------|
| Added  | **[`AutoCloseable`]** | ![No changes]         |


#### Methods

| Status | Modifiers    | Generics | Type                 | Method                            | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|----------------------|-----------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`void`**           | **`close`**()                     |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **`int`**            | **`getColumnCount`**()            |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`ColumnReader`]** | **`getColumnReader`**([`String`]) |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`ColumnReader`]** | **`getColumnReader`**(`int`)      |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.reader.filterpredicate$uuidcolumnpredicate"></a>
### `dev.hardwood.reader.FilterPredicate$UUIDColumnPredicate`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name                      | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|---------------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`UUIDColumnPredicate`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface               | Compatibility Changes |
|--------|-------------------------|-----------------------|
| Added  | **[`FilterPredicate`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor                                                   | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|---------------------------------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`UUIDColumnPredicate`**([`String`], [`Operator`], `byte[]`) |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type             | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|------------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`public`**             |          | **[`String`]**   | **`column`**()           |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`boolean`**    | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`int`**        | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`Operator`]** | **`op`**()               |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]**   | **`toString`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`byte[]`**     | **`value`**()            |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.reader.multifilecolumnreaders"></a>
### `dev.hardwood.reader.MultiFileColumnReaders`

- [ ] Binary-compatible
- [ ] Source-compatible
- [X] Serialization-compatible

| Status  | Modifiers    | Type      | Name                         | Extends        | JDK        | Serialization       | Compatibility Changes |
|---------|--------------|-----------|------------------------------|----------------|------------|---------------------|-----------------------|
| Removed | ~~`public`~~ | ~~Class~~ | ~~`MultiFileColumnReaders`~~ | ~~[`Object`]~~ | ~~JDK 21~~ | ![Not serializable] | ![Class removed] ![Superclass removed] |


#### Implemented Interfaces

| Status  | Interface             | Compatibility Changes |
|---------|-----------------------|-----------------------|
| Removed | ~~[`AutoCloseable`]~~ | ![Interface removed]  |


#### Methods

| Status  | Modifiers    | Generics | Type                 | Method                            | Annotations | Throws | Compatibility Changes |
|---------|--------------|----------|----------------------|-----------------------------------|-------------|--------|-----------------------|
| Removed | ~~`public`~~ |          | ~~`void`~~           | ~~`close`~~()                     |             |        | ![Method removed]     |
| Removed | ~~`public`~~ |          | ~~`int`~~            | ~~`getColumnCount`~~()            |             |        | ![Method removed]     |
| Removed | ~~`public`~~ |          | ~~[`ColumnReader`]~~ | ~~`getColumnReader`~~([`String`]) |             |        | ![Method removed]     |
| Removed | ~~`public`~~ |          | ~~[`ColumnReader`]~~ | ~~`getColumnReader`~~(`int`)      |             |        | ![Method removed]     |

___

<a id="user-content-dev.hardwood.reader.multifileparquetreader"></a>
### `dev.hardwood.reader.MultiFileParquetReader`

- [ ] Binary-compatible
- [ ] Source-compatible
- [X] Serialization-compatible

| Status  | Modifiers    | Type      | Name                         | Extends        | JDK        | Serialization       | Compatibility Changes |
|---------|--------------|-----------|------------------------------|----------------|------------|---------------------|-----------------------|
| Removed | ~~`public`~~ | ~~Class~~ | ~~`MultiFileParquetReader`~~ | ~~[`Object`]~~ | ~~JDK 21~~ | ![Not serializable] | ![Class removed] ![Superclass removed] |


#### Implemented Interfaces

| Status  | Interface             | Compatibility Changes |
|---------|-----------------------|-----------------------|
| Removed | ~~[`AutoCloseable`]~~ | ![Interface removed]  |


#### Constructors

| Status  | Modifiers    | Generics | Constructor | Annotations | Throws              | Compatibility Changes |
|---------|--------------|----------|-------------|-------------|---------------------|-----------------------|
| Removed | ~~`public`~~ |          | ~~`MultiFileParquetReader`~~([`List<InputFile>`], [`HardwoodContextImpl`]) |  | ~~[`IOException`]~~ | ![Constructor removed] |


#### Methods

| Status  | Modifiers    | Generics | Type                           | Method                                                           | Annotations | Throws | Compatibility Changes |
|---------|--------------|----------|--------------------------------|------------------------------------------------------------------|-------------|--------|-----------------------|
| Removed | ~~`public`~~ |          | ~~`void`~~                     | ~~`close`~~()                                                    |             |        | ![Method removed]     |
| Removed | ~~`public`~~ |          | ~~[`MultiFileColumnReaders`]~~ | ~~`createColumnReaders`~~([`ColumnProjection`])                  |             |        | ![Method removed]     |
| Removed | ~~`public`~~ |          | ~~[`MultiFileColumnReaders`]~~ | ~~`createColumnReaders`~~([`ColumnProjection`], [`FilterPredicate`]) |         |        | ![Method removed]     |
| Removed | ~~`public`~~ |          | ~~[`MultiFileRowReader`]~~     | ~~`createRowReader`~~()                                          |             |        | ![Method removed]     |
| Removed | ~~`public`~~ |          | ~~[`MultiFileRowReader`]~~     | ~~`createRowReader`~~([`FilterPredicate`])                       |             |        | ![Method removed]     |
| Removed | ~~`public`~~ |          | ~~[`MultiFileRowReader`]~~     | ~~`createRowReader`~~([`ColumnProjection`])                      |             |        | ![Method removed]     |
| Removed | ~~`public`~~ |          | ~~[`MultiFileRowReader`]~~     | ~~`createRowReader`~~([`ColumnProjection`], [`FilterPredicate`]) |             |        | ![Method removed]     |
| Removed | ~~`public`~~ |          | ~~[`FileSchema`]~~             | ~~`getFileSchema`~~()                                            |             |        | ![Method removed]     |

___

<a id="user-content-dev.hardwood.reader.multifilerowreader"></a>
### `dev.hardwood.reader.MultiFileRowReader`

- [ ] Binary-compatible
- [ ] Source-compatible
- [X] Serialization-compatible

| Status  | Modifiers    | Type      | Name                     | Extends                   | JDK        | Serialization       | Compatibility Changes |
|---------|--------------|-----------|--------------------------|---------------------------|------------|---------------------|-----------------------|
| Removed | ~~`public`~~ | ~~Class~~ | ~~`MultiFileRowReader`~~ | ~~[`AbstractRowReader`]~~ | ~~JDK 21~~ | ![Not serializable] | ![Class removed] ![Superclass removed] |


#### Implemented Interfaces

| Status  | Interface              | Compatibility Changes |
|---------|------------------------|-----------------------|
| Removed | ~~[`RowReader`]~~      | ![Interface removed]  |
| Removed | ~~[`FieldAccessor`]~~  | ![Interface removed]  |
| Removed | ~~[`StructAccessor`]~~ | ![Interface removed]  |
| Removed | ~~[`AutoCloseable`]~~  | ![Interface removed]  |


#### Methods

| Status  | Modifiers       | Generics | Type          | Method                | Annotations | Throws | Compatibility Changes |
|---------|-----------------|----------|---------------|-----------------------|-------------|--------|-----------------------|
| Removed | ~~`public`~~    |          | ~~`void`~~    | ~~`close`~~()         |             |        | ![No changes]         |
| Removed | ~~`protected`~~ |          | ~~`void`~~    | ~~`initialize`~~()    |             |        | ![Method removed]     |
| Removed | ~~`protected`~~ |          | ~~`boolean`~~ | ~~`loadNextBatch`~~() |             |        | ![Method removed]     |

___

<a id="user-content-dev.hardwood.reader.parquetfilereader"></a>
### `dev.hardwood.reader.ParquetFileReader`

- [ ] Binary-compatible
- [ ] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers | Type  | Name                | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|-----------|-------|---------------------|------------|--------|---------------------|-----------------------|
| Modified | `public`  | Class | `ParquetFileReader` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Methods

| Status  | Modifiers                 | Generics | Type                         | Method                                                           | Annotations | Throws              | Compatibility Changes |
|---------|---------------------------|----------|------------------------------|------------------------------------------------------------------|-------------|---------------------|-----------------------|
| Added   | **`public`**              |          | **[`ColumnReaderBuilder`]**  | **`buildColumnReader`**([`String`])                              |             |                     | ![Method added to public class] |
| Added   | **`public`**              |          | **[`ColumnReaderBuilder`]**  | **`buildColumnReader`**(`int`)                                   |             |                     | ![Method added to public class] |
| Added   | **`public`**              |          | **[`ColumnReadersBuilder`]** | **`buildColumnReaders`**([`ColumnProjection`])                   |             |                     | ![Method added to public class] |
| Added   | **`public`**              |          | **[`RowReaderBuilder`]**     | **`buildRowReader`**()                                           |             |                     | ![Method added to public class] |
| Added   | **`public`**              |          | **[`ColumnReader`]**         | **`columnReader`**([`String`])                                   |             |                     | ![Method added to public class] |
| Added   | **`public`**              |          | **[`ColumnReader`]**         | **`columnReader`**(`int`)                                        |             |                     | ![Method added to public class] |
| Added   | **`public`**              |          | **[`ColumnReaders`]**        | **`columnReaders`**([`ColumnProjection`])                        |             |                     | ![Method added to public class] |
| Removed | ~~`public`~~              |          | ~~[`ColumnReader`]~~         | ~~`createColumnReader`~~([`String`])                             |             |                     | ![Method removed]     |
| Removed | ~~`public`~~              |          | ~~[`ColumnReader`]~~         | ~~`createColumnReader`~~([`String`], [`FilterPredicate`])        |             |                     | ![Method removed]     |
| Removed | ~~`public`~~              |          | ~~[`ColumnReader`]~~         | ~~`createColumnReader`~~(`int`)                                  |             |                     | ![Method removed]     |
| Removed | ~~`public`~~              |          | ~~[`ColumnReader`]~~         | ~~`createColumnReader`~~(`int`, [`FilterPredicate`])             |             |                     | ![Method removed]     |
| Removed | ~~`public`~~              |          | ~~[`RowReader`]~~            | ~~`createRowReader`~~()                                          |             |                     | ![Method removed]     |
| Removed | ~~`public`~~              |          | ~~[`RowReader`]~~            | ~~`createRowReader`~~([`FilterPredicate`])                       |             |                     | ![Method removed]     |
| Removed | ~~`public`~~              |          | ~~[`RowReader`]~~            | ~~`createRowReader`~~([`ColumnProjection`])                      |             |                     | ![Method removed]     |
| Removed | ~~`public`~~              |          | ~~[`RowReader`]~~            | ~~`createRowReader`~~([`ColumnProjection`], [`FilterPredicate`]) |             |                     | ![Method removed]     |
| Removed | ~~`public`~~              |          | ~~[`RowReader`]~~            | ~~`createRowReader`~~(`long`)                                    |             |                     | ![Method removed]     |
| Removed | ~~`public`~~              |          | ~~[`RowReader`]~~            | ~~`createRowReader`~~([`ColumnProjection`], `long`)              |             |                     | ![Method removed]     |
| Removed | ~~`public`~~              |          | ~~[`RowReader`]~~            | ~~`createRowReader`~~([`FilterPredicate`], `long`)               |             |                     | ![Method removed]     |
| Removed | ~~`public`~~              |          | ~~[`RowReader`]~~            | ~~`createRowReader`~~([`ColumnProjection`], [`FilterPredicate`], `long`) |     |                     | ![Method removed]     |
| Added   | **`public`**              |          | **`boolean`**                | **`isMultiFile`**()                                              |             |                     | ![Method added to public class] |
| Added   | **`static`** **`public`** |          | **[`ParquetFileReader`]**    | **`openAll`**([`List<InputFile>`])                               |             | **[`IOException`]** | ![Method added to public class] |
| Added   | **`static`** **`public`** |          | **[`ParquetFileReader`]**    | **`openAll`**([`List<InputFile>`], [`HardwoodContext`])          |             | **[`IOException`]** | ![Method added to public class] |
| Added   | **`public`**              |          | **[`RowReader`]**            | **`rowReader`**()                                                |             |                     | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.reader.parquetfilereader$columnreaderbuilder"></a>
### `dev.hardwood.reader.ParquetFileReader$ColumnReaderBuilder`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name                      | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|---------------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`ColumnReaderBuilder`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers    | Generics | Type                        | Method                            | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-----------------------------|-----------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **[`ColumnReader`]**        | **`build`**()                     |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`ColumnReaderBuilder`]** | **`filter`**([`FilterPredicate`]) |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.reader.parquetfilereader$columnreadersbuilder"></a>
### `dev.hardwood.reader.ParquetFileReader$ColumnReadersBuilder`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name                       | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|----------------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`ColumnReadersBuilder`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers    | Generics | Type                         | Method                            | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|------------------------------|-----------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **[`ColumnReaders`]**        | **`build`**()                     |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`ColumnReadersBuilder`]** | **`filter`**([`FilterPredicate`]) |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.reader.parquetfilereader$rowreaderbuilder"></a>
### `dev.hardwood.reader.ParquetFileReader$RowReaderBuilder`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name                   | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|------------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`RowReaderBuilder`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers    | Generics | Type                     | Method                                 | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|--------------------------|----------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **[`RowReader`]**        | **`build`**()                          |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`RowReaderBuilder`]** | **`filter`**([`FilterPredicate`])      |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`RowReaderBuilder`]** | **`firstRow`**(`long`)                 |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`RowReaderBuilder`]** | **`head`**(`long`)                     |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`RowReaderBuilder`]** | **`projection`**([`ColumnProjection`]) |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`RowReaderBuilder`]** | **`tail`**(`long`)                     |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.reader.rowreader"></a>
### `dev.hardwood.reader.RowReader`

- [X] Binary-compatible
- [ ] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers           | Type      | Name        | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|---------------------|-----------|-------------|------------|--------|---------------------|-----------------------|
| Modified | `public` `abstract` | Interface | `RowReader` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers                   | Generics | Type               | Method                   | Annotations | Throws | Compatibility Changes |
|--------|-----------------------------|----------|--------------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`static`** **`public`**   |          | **[`RowReader`]**  | **`create`**([`RowGroupIterator`], [`FileSchema`], [`ProjectedSchema`], [`HardwoodContextImpl`], [`ResolvedPredicate`], `long`) |  |  | ![Method new static added to interface] |
| Added  | **`public`** **`abstract`** |          | **[`PqInterval`]** | **`getInterval`**(`int`) |             |        | ![Method added to interface] |

___

<a id="user-content-dev.hardwood.reader.schemaincompatibleexception"></a>
### `dev.hardwood.reader.SchemaIncompatibleException`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers    | Type      | Name                              | Extends                  | JDK        | Serialization | Compatibility Changes |
|--------|--------------|-----------|-----------------------------------|--------------------------|------------|---------------|-----------------------|
| Added  | **`public`** | **Class** | **`SchemaIncompatibleException`** | **[`RuntimeException`]** | **JDK 21** | ![Compatible] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface            | Compatibility Changes |
|--------|----------------------|-----------------------|
| Added  | **[`Serializable`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor                                   | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-----------------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`SchemaIncompatibleException`**([`String`]) |             |        | ![No changes]         |

___

<a id="user-content-dev.hardwood.row.fieldaccessor"></a>
### `dev.hardwood.row.FieldAccessor`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                   | Type          | Name                | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|-----------------------------|---------------|---------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`public`** **`abstract`** | **Interface** | **`FieldAccessor`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers                   | Generics | Type               | Method                         | Annotations | Throws | Compatibility Changes |
|--------|-----------------------------|----------|--------------------|--------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** **`abstract`** |          | **`byte[]`**       | **`getBinary`**([`String`])    |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`boolean`**      | **`getBoolean`**([`String`])   |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`LocalDate`]**  | **`getDate`**([`String`])      |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`BigDecimal`]** | **`getDecimal`**([`String`])   |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`double`**       | **`getDouble`**([`String`])    |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`int`**          | **`getFieldCount`**()          |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`String`]**     | **`getFieldName`**(`int`)      |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`float`**        | **`getFloat`**([`String`])     |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`int`**          | **`getInt`**([`String`])       |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`PqInterval`]** | **`getInterval`**([`String`])  |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`long`**         | **`getLong`**([`String`])      |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`String`]**     | **`getString`**([`String`])    |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`LocalTime`]**  | **`getTime`**([`String`])      |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`Instant`]**    | **`getTimestamp`**([`String`]) |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`UUID`]**       | **`getUuid`**([`String`])      |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`Object`]**     | **`getValue`**([`String`])     |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`PqVariant`]**  | **`getVariant`**([`String`])   |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`boolean`**      | **`isNull`**([`String`])       |             |        | ![No changes]         |

___

<a id="user-content-dev.hardwood.row.pqinterval"></a>
### `dev.hardwood.row.PqInterval`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                | Type      | Name             | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|--------------------------|-----------|------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`public`** | **Class** | **`PqInterval`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor                              | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|------------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`PqInterval`**(`long`, `long`, `long`) |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type           | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|----------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`public`**             |          | **`long`**     | **`days`**()             |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`boolean`**  | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**      | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`long`**     | **`milliseconds`**()     |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`long`**     | **`months`**()           |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]** | **`toString`**()         |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.row.pqvariant"></a>
### `dev.hardwood.row.PqVariant`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                   | Type          | Name            | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|-----------------------------|---------------|-----------------|----------------|------------|---------------------|-----------------------|
| Added  | **`public`** **`abstract`** | **Interface** | **`PqVariant`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers                   | Generics | Type                    | Method              | Annotations | Throws | Compatibility Changes |
|--------|-----------------------------|----------|-------------------------|---------------------|-------------|--------|-----------------------|
| Added  | **`public`** **`abstract`** |          | **[`PqVariantArray`]**  | **`asArray`**()     |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`byte[]`**            | **`asBinary`**()    |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`boolean`**           | **`asBoolean`**()   |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`LocalDate`]**       | **`asDate`**()      |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`BigDecimal`]**      | **`asDecimal`**()   |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`double`**            | **`asDouble`**()    |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`float`**             | **`asFloat`**()     |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`int`**               | **`asInt`**()       |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`long`**              | **`asLong`**()      |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`PqVariantObject`]** | **`asObject`**()    |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`String`]**          | **`asString`**()    |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`LocalTime`]**       | **`asTime`**()      |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`Instant`]**         | **`asTimestamp`**() |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`UUID`]**            | **`asUuid`**()      |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`boolean`**           | **`isNull`**()      |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`byte[]`**            | **`metadata`**()    |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`VariantType`]**     | **`type`**()        |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`byte[]`**            | **`value`**()       |             |        | ![No changes]         |

___

<a id="user-content-dev.hardwood.row.pqvariantarray"></a>
### `dev.hardwood.row.PqVariantArray`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                   | Type          | Name                 | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|-----------------------------|---------------|----------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`public`** **`abstract`** | **Interface** | **`PqVariantArray`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface           | Compatibility Changes |
|--------|---------------------|-----------------------|
| Added  | **[`Iterable<T>`]** | ![No changes]         |


#### Methods

| Status | Modifiers                   | Generics | Type                        | Method           | Annotations | Throws | Compatibility Changes |
|--------|-----------------------------|----------|-----------------------------|------------------|-------------|--------|-----------------------|
| Added  | **`public`** **`abstract`** |          | **[`PqVariant`]**           | **`get`**(`int`) |             |        | ![No changes]         |
| Added  | **`public`**                |          | **[`Iterator<PqVariant>`]** | **`iterator`**() |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`int`**                   | **`size`**()     |             |        | ![No changes]         |

___

<a id="user-content-dev.hardwood.row.pqvariantobject"></a>
### `dev.hardwood.row.PqVariantObject`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                   | Type          | Name                  | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|-----------------------------|---------------|-----------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`public`** **`abstract`** | **Interface** | **`PqVariantObject`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface             | Compatibility Changes |
|--------|-----------------------|-----------------------|
| Added  | **[`FieldAccessor`]** | ![No changes]         |


#### Methods

| Status | Modifiers                   | Generics | Type                    | Method                      | Annotations | Throws | Compatibility Changes |
|--------|-----------------------------|----------|-------------------------|-----------------------------|-------------|--------|-----------------------|
| Added  | **`public`** **`abstract`** |          | **[`PqVariantArray`]**  | **`getArray`**([`String`])  |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`PqVariantObject`]** | **`getObject`**([`String`]) |             |        | ![No changes]         |

___

<a id="user-content-dev.hardwood.row.structaccessor"></a>
### `dev.hardwood.row.StructAccessor`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers           | Type      | Name             | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|---------------------|-----------|------------------|------------|--------|---------------------|-----------------------|
| Modified | `public` `abstract` | Interface | `StructAccessor` | [`Object`] | JDK 21 | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface             | Compatibility Changes |
|--------|-----------------------|-----------------------|
| Added  | **[`FieldAccessor`]** | ![No changes]         |


#### Methods

| Status  | Modifiers                   | Generics | Type               | Method                         | Annotations | Throws | Compatibility Changes |
|---------|-----------------------------|----------|--------------------|--------------------------------|-------------|--------|-----------------------|
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~`byte[]`~~       | ~~`getBinary`~~([`String`])    |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~`boolean`~~      | ~~`getBoolean`~~([`String`])   |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`LocalDate`]~~  | ~~`getDate`~~([`String`])      |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`BigDecimal`]~~ | ~~`getDecimal`~~([`String`])   |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~`double`~~       | ~~`getDouble`~~([`String`])    |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~`int`~~          | ~~`getFieldCount`~~()          |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`String`]~~     | ~~`getFieldName`~~(`int`)      |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~`float`~~        | ~~`getFloat`~~([`String`])     |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~`int`~~          | ~~`getInt`~~([`String`])       |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~`long`~~         | ~~`getLong`~~([`String`])      |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`String`]~~     | ~~`getString`~~([`String`])    |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`LocalTime`]~~  | ~~`getTime`~~([`String`])      |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`Instant`]~~    | ~~`getTimestamp`~~([`String`]) |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`UUID`]~~       | ~~`getUuid`~~([`String`])      |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`Object`]~~     | ~~`getValue`~~([`String`])     |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~`boolean`~~      | ~~`isNull`~~([`String`])       |             |        | ![No changes]         |

___

<a id="user-content-dev.hardwood.row.varianttype"></a>
### `dev.hardwood.row.VariantType`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                | Type     | Name              | Extends         | JDK        | Serialization | Compatibility Changes |
|--------|--------------------------|----------|-------------------|-----------------|------------|---------------|-----------------------|
| Added  | **`final`** **`public`** | **Enum** | **`VariantType`** | **[`Enum<E>`]** | **JDK 21** | ![Compatible] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface             | Compatibility Changes |
|--------|-----------------------|-----------------------|
| Added  | **[`Serializable`]**  | ![No changes]         |
| Added  | **[`Comparable<T>`]** | ![No changes]         |
| Added  | **[`Constable`]**     | ![No changes]         |


#### Methods

| Status | Modifiers                 | Generics | Type                     | Method                    | Annotations | Throws | Compatibility Changes |
|--------|---------------------------|----------|--------------------------|---------------------------|-------------|--------|-----------------------|
| Added  | **`static`** **`public`** |          | **[`VariantType`]**      | **`valueOf`**([`String`]) |             |        | ![Method added to public class] |
| Added  | **`static`** **`public`** |          | **[`VariantType[]`][1]** | **`values`**()            |             |        | ![Method added to public class] |


#### Fields

| Status | Modifiers                             | Type                | Name                  | Annotations | Compatibility Changes |
|--------|---------------------------------------|---------------------|-----------------------|-------------|-----------------------|
| Added  | **`public`** **`static`** **`final`** | **[`VariantType`]** | `ARRAY`               |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`VariantType`]** | `BINARY`              |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`VariantType`]** | `BOOLEAN_FALSE`       |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`VariantType`]** | `BOOLEAN_TRUE`        |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`VariantType`]** | `DATE`                |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`VariantType`]** | `DECIMAL16`           |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`VariantType`]** | `DECIMAL4`            |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`VariantType`]** | `DECIMAL8`            |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`VariantType`]** | `DOUBLE`              |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`VariantType`]** | `FLOAT`               |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`VariantType`]** | `INT16`               |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`VariantType`]** | `INT32`               |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`VariantType`]** | `INT64`               |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`VariantType`]** | `INT8`                |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`VariantType`]** | `NULL`                |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`VariantType`]** | `OBJECT`              |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`VariantType`]** | `STRING`              |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`VariantType`]** | `TIMESTAMP`           |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`VariantType`]** | `TIMESTAMP_NANOS`     |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`VariantType`]** | `TIMESTAMP_NTZ`       |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`VariantType`]** | `TIMESTAMP_NTZ_NANOS` |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`VariantType`]** | `TIME_NTZ`            |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`VariantType`]** | `UUID`                |             | ![No changes]         |

___

<a id="user-content-dev.hardwood.row.varianttypeexception"></a>
### `dev.hardwood.row.VariantTypeException`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers    | Type      | Name                       | Extends                  | JDK        | Serialization | Compatibility Changes |
|--------|--------------|-----------|----------------------------|--------------------------|------------|---------------|-----------------------|
| Added  | **`public`** | **Class** | **`VariantTypeException`** | **[`RuntimeException`]** | **JDK 21** | ![Compatible] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface            | Compatibility Changes |
|--------|----------------------|-----------------------|
| Added  | **[`Serializable`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor                            | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|----------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`VariantTypeException`**([`String`]) |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                 | Generics | Type                         | Method                                           | Annotations | Throws | Compatibility Changes |
|--------|---------------------------|----------|------------------------------|--------------------------------------------------|-------------|--------|-----------------------|
| Added  | **`static`** **`public`** |          | **[`VariantTypeException`]** | **`expected`**([`VariantType`], [`VariantType`]) |             |        | ![Method added to public class] |
| Added  | **`static`** **`public`** |          | **[`VariantTypeException`]** | **`expectedOneOf`**([`String`], [`VariantType`]) |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.schema.fileschema"></a>
### `dev.hardwood.schema.FileSchema`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers | Type  | Name         | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|-----------|-------|--------------|------------|--------|---------------------|-----------------------|
| Modified | `public`  | Class | `FileSchema` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |

___

<a id="user-content-dev.hardwood.schema.projectedschema"></a>
### `dev.hardwood.schema.ProjectedSchema`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers        | Type  | Name              | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|------------------|-------|-------------------|------------|--------|---------------------|-----------------------|
| Modified | `final` `public` | Class | `ProjectedSchema` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers    | Generics | Type        | Method                    | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-------------|---------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`int[]`** | **`toOriginalIndices`**() |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.schema.schemanode$groupnode"></a>
### `dev.hardwood.schema.SchemaNode$GroupNode`

- [ ] Binary-compatible
- [ ] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers                 | Type  | Name        | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|---------------------------|-------|-------------|------------|--------|---------------------|-----------------------|
| Modified | `final` `static` `public` | Class | `GroupNode` | [`Record`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Constructors

| Status  | Modifiers    | Generics | Constructor | Annotations | Throws | Compatibility Changes |
|---------|--------------|----------|-------------|-------------|--------|-----------------------|
| Removed | ~~`public`~~ |          | ~~`GroupNode`~~([`String`], [`RepetitionType`], [`ConvertedType`], [`List<SchemaNode>`], `int`, `int`) |  |  | ![Constructor removed] |
| Added   | **`public`** |          | **`GroupNode`**([`String`], [`RepetitionType`], [`ConvertedType`], [`LogicalType`], [`List<SchemaNode>`], `int`, `int`) |  |  | ![No changes] |


#### Methods

| Status | Modifiers    | Generics | Type                | Method              | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|---------------------|---------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`boolean`**       | **`isVariant`**()   |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`LogicalType`]** | **`logicalType`**() |             |        | ![Method added to public class] |


</details>


___

*Generated on: 2026-06-05 09:27:07.040+0000*.

[1]: # "dev.hardwood.row.VariantType[]"
[Class removed]: https://img.shields.io/badge/Class_removed-red "Class removed"
[Compatible]: https://img.shields.io/badge/Compatible-green "Compatible"
[Constructor removed]: https://img.shields.io/badge/Constructor_removed-red "Constructor removed"
[Interface added]: https://img.shields.io/badge/Interface_added-orange "Interface added"
[Interface removed]: https://img.shields.io/badge/Interface_removed-red "Interface removed"
[Method added to interface]: https://img.shields.io/badge/Method_added_to_interface-orange "Method added to interface"
[Method added to public class]: https://img.shields.io/badge/Method_added_to_public_class-yellow "Method added to public class"
[Method new static added to interface]: https://img.shields.io/badge/Method_new_static_added_to_interface-orange "Method new static added to interface"
[Method removed]: https://img.shields.io/badge/Method_removed-red "Method removed"
[Method return type changed]: https://img.shields.io/badge/Method_return_type_changed-red "Method return type changed"
[No changes]: https://img.shields.io/badge/No_changes-green "No changes"
[Not serializable]: https://img.shields.io/badge/Not_serializable-green "Not serializable"
[Superclass removed]: https://img.shields.io/badge/Superclass_removed-red "Superclass removed"
[`AbstractRowReader`]: # "dev.hardwood.reader.AbstractRowReader"
[`AutoCloseable`]: # "java.lang.AutoCloseable"
[`BigDecimal`]: # "java.math.BigDecimal"
[`ColumnProjection`]: # "dev.hardwood.schema.ColumnProjection"
[`ColumnReaderBuilder`]: # "dev.hardwood.reader.ParquetFileReader$ColumnReaderBuilder"
[`ColumnReader`]: # "dev.hardwood.reader.ColumnReader"
[`ColumnReadersBuilder`]: # "dev.hardwood.reader.ParquetFileReader$ColumnReadersBuilder"
[`ColumnReaders`]: # "dev.hardwood.reader.ColumnReaders"
[`Comparable<T>`]: # "java.lang.Comparable<T extends java.lang.Object>"
[`Constable`]: # "java.lang.constant.Constable"
[`ConvertedType`]: # "dev.hardwood.metadata.ConvertedType"
[`Enum<E>`]: # "java.lang.Enum<E extends java.lang.Enum<E>>"
[`FieldAccessor`]: # "dev.hardwood.row.FieldAccessor"
[`FileSchema`]: # "dev.hardwood.schema.FileSchema"
[`FilterPredicate`]: # "dev.hardwood.reader.FilterPredicate"
[`HardwoodContextImpl`]: # "dev.hardwood.internal.reader.HardwoodContextImpl"
[`HardwoodContext`]: # "dev.hardwood.HardwoodContext"
[`IOException`]: # "java.io.IOException"
[`Instant`]: # "java.time.Instant"
[`Iterable<T>`]: # "java.lang.Iterable<T extends java.lang.Object>"
[`Iterator<PqVariant>`]: # "java.util.Iterator<dev.hardwood.row.PqVariant>"
[`List<InputFile>`]: # "java.util.List<dev.hardwood.InputFile>"
[`List<SchemaNode>`]: # "java.util.List<dev.hardwood.schema.SchemaNode>"
[`LocalDate`]: # "java.time.LocalDate"
[`LocalTime`]: # "java.time.LocalTime"
[`LogicalType`]: # "dev.hardwood.metadata.LogicalType"
[`MultiFileColumnReaders`]: # "dev.hardwood.reader.MultiFileColumnReaders"
[`MultiFileParquetReader`]: # "dev.hardwood.reader.MultiFileParquetReader"
[`MultiFileRowReader`]: # "dev.hardwood.reader.MultiFileRowReader"
[`Object`]: # "java.lang.Object"
[`Operator`]: # "dev.hardwood.reader.FilterPredicate$Operator"
[`ParquetFileReader`]: # "dev.hardwood.reader.ParquetFileReader"
[`PqInterval`]: # "dev.hardwood.row.PqInterval"
[`PqVariantArray`]: # "dev.hardwood.row.PqVariantArray"
[`PqVariantObject`]: # "dev.hardwood.row.PqVariantObject"
[`PqVariant`]: # "dev.hardwood.row.PqVariant"
[`ProjectedSchema`]: # "dev.hardwood.schema.ProjectedSchema"
[`Record`]: # "java.lang.Record"
[`RepetitionType`]: # "dev.hardwood.metadata.RepetitionType"
[`ResolvedPredicate`]: # "dev.hardwood.internal.predicate.ResolvedPredicate"
[`RowGroupIterator`]: # "dev.hardwood.internal.reader.RowGroupIterator"
[`RowReaderBuilder`]: # "dev.hardwood.reader.ParquetFileReader$RowReaderBuilder"
[`RowReader`]: # "dev.hardwood.reader.RowReader"
[`RuntimeException`]: # "java.lang.RuntimeException"
[`Serializable`]: # "java.io.Serializable"
[`String`]: # "java.lang.String"
[`StructAccessor`]: # "dev.hardwood.row.StructAccessor"
[`UUID`]: # "java.util.UUID"
[`VariantTypeException`]: # "dev.hardwood.row.VariantTypeException"
[`VariantType`]: # "dev.hardwood.row.VariantType"
[dev.hardwood.Hardwood]: #user-content-dev.hardwood.hardwood
[dev.hardwood.metadata.ColumnChunk]: #user-content-dev.hardwood.metadata.columnchunk
[dev.hardwood.metadata.LogicalType$VariantType]: #user-content-dev.hardwood.metadata.logicaltype$varianttype
[dev.hardwood.reader.ColumnReader]: #user-content-dev.hardwood.reader.columnreader
[dev.hardwood.reader.ColumnReaders]: #user-content-dev.hardwood.reader.columnreaders
[dev.hardwood.reader.FilterPredicate$UUIDColumnPredicate]: #user-content-dev.hardwood.reader.filterpredicate$uuidcolumnpredicate
[dev.hardwood.reader.MultiFileColumnReaders]: #user-content-dev.hardwood.reader.multifilecolumnreaders
[dev.hardwood.reader.MultiFileParquetReader]: #user-content-dev.hardwood.reader.multifileparquetreader
[dev.hardwood.reader.MultiFileRowReader]: #user-content-dev.hardwood.reader.multifilerowreader
[dev.hardwood.reader.ParquetFileReader]: #user-content-dev.hardwood.reader.parquetfilereader
[dev.hardwood.reader.ParquetFileReader$ColumnReaderBuilder]: #user-content-dev.hardwood.reader.parquetfilereader$columnreaderbuilder
[dev.hardwood.reader.ParquetFileReader$ColumnReadersBuilder]: #user-content-dev.hardwood.reader.parquetfilereader$columnreadersbuilder
[dev.hardwood.reader.ParquetFileReader$RowReaderBuilder]: #user-content-dev.hardwood.reader.parquetfilereader$rowreaderbuilder
[dev.hardwood.reader.RowReader]: #user-content-dev.hardwood.reader.rowreader
[dev.hardwood.reader.SchemaIncompatibleException]: #user-content-dev.hardwood.reader.schemaincompatibleexception
[dev.hardwood.row.FieldAccessor]: #user-content-dev.hardwood.row.fieldaccessor
[dev.hardwood.row.PqInterval]: #user-content-dev.hardwood.row.pqinterval
[dev.hardwood.row.PqVariant]: #user-content-dev.hardwood.row.pqvariant
[dev.hardwood.row.PqVariantArray]: #user-content-dev.hardwood.row.pqvariantarray
[dev.hardwood.row.PqVariantObject]: #user-content-dev.hardwood.row.pqvariantobject
[dev.hardwood.row.StructAccessor]: #user-content-dev.hardwood.row.structaccessor
[dev.hardwood.row.VariantType]: #user-content-dev.hardwood.row.varianttype
[dev.hardwood.row.VariantTypeException]: #user-content-dev.hardwood.row.varianttypeexception
[dev.hardwood.schema.FileSchema]: #user-content-dev.hardwood.schema.fileschema
[dev.hardwood.schema.ProjectedSchema]: #user-content-dev.hardwood.schema.projectedschema
[dev.hardwood.schema.SchemaNode$GroupNode]: #user-content-dev.hardwood.schema.schemanode$groupnode
