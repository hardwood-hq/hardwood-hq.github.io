
# Compatibility Report

![semver MAJOR](https://img.shields.io/badge/semver-MAJOR-red?logo=semver "semver MAJOR")

## Summary

> [!CAUTION]
>
> Incompatible changes found while checking backward compatibility of version `1.0.0-SNAPSHOT` with the previous version `1.0.0.CR1`.

<details markdown="1">
<summary>Expand to see options used.</summary>

- **Report only summary**: No
- **Report only changes**: Yes
- **Report only binary-incompatible changes**: No
- **Access modifier filter**: `PROTECTED`
- **Old archives**:
  - ![hardwood-core 1.0.0.CR1](https://img.shields.io/badge/hardwood_core-1.0.0.CR1-blue "hardwood-core 1.0.0.CR1")
- **New archives**:
  - ![hardwood-core 1.0.0-SNAPSHOT](https://img.shields.io/badge/hardwood_core-1.0.0_SNAPSHOT-blue "hardwood-core 1.0.0-SNAPSHOT")
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

| Status              | Type                                                         | Serialization                       | Compatibility Changes |
|---------------------|--------------------------------------------------------------|-------------------------------------|-----------------------|
| Source-incompatible | [dev.hardwood.Hardwood]                                      | ![Not serializable]                 | ![Method parameter generics changed] |
| Modified            | [dev.hardwood.metadata.ColumnIndex]                          | ![Not serializable]                 | ![Method removed] ![Constructor removed] |
| Modified            | [dev.hardwood.reader.ColumnReader]                           | ![Not serializable]                 | ![No changes]         |
| Modified            | [dev.hardwood.reader.ColumnReaders]                          | ![Not serializable]                 | ![No changes]         |
| Modified            | [dev.hardwood.reader.ParquetFileReader]                      | ![Not serializable]                 | ![Method parameter generics changed] |
| Modified            | [dev.hardwood.reader.ParquetFileReader$ColumnReaderBuilder]  | ![Not serializable]                 | ![Method added to public class] |
| Modified            | [dev.hardwood.reader.ParquetFileReader$ColumnReadersBuilder] | ![Not serializable]                 | ![Method added to public class] |
| Modified            | [dev.hardwood.reader.ParquetFileReader$RowReaderBuilder]     | ![Not serializable]                 | ![Method removed] ![Method added to public class] |
| Modified            | [dev.hardwood.reader.RowReader]                              | ![Not serializable]                 | ![Method removed] ![Method new static added to interface] |
| Modified            | [dev.hardwood.row.FieldAccessor]                             | ![Not serializable]                 | ![Method added to interface] |
| Modified            | [dev.hardwood.row.PqList]                                    | ![Not serializable]                 | ![Method added to interface] |
| Modified            | [dev.hardwood.row.PqMap$Entry]                               | ![Not serializable]                 | ![Method added to interface] |
| Modified            | [dev.hardwood.row.PqVariant]                                 | ![Not serializable]                 | ![Method added to interface] |
| Modified            | [dev.hardwood.row.StructAccessor]                            | ![Not serializable]                 | ![Method added to interface] |
| Modified            | [dev.hardwood.row.VariantTypeException]                      | ![Default serialversionuid changed] | ![Method removed]     |
| Removed             | [dev.hardwood.schema.ProjectedSchema]                        | ![Not serializable]                 | ![Class removed] ![Superclass removed] ![Method removed] |

<details markdown="1">
<summary>Expand for details.</summary>

___

<a id="user-content-dev.hardwood.hardwood"></a>
### `dev.hardwood.Hardwood`

- [X] Binary-compatible
- [ ] Source-compatible
- [X] Serialization-compatible

| Status              | Modifiers | Type  | Name       | Extends    | JDK    | Serialization       | Compatibility Changes |
|---------------------|-----------|-------|------------|------------|--------|---------------------|-----------------------|
| Source-incompatible | `public`  | Class | `Hardwood` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Methods

| Status              | Modifiers | Generics | Type                  | Method | Annotations | Throws          | Compatibility Changes |
|---------------------|-----------|----------|-----------------------|--------|-------------|-----------------|-----------------------|
| Source-incompatible | `public`  |          | [`ParquetFileReader`] | `openAll`(~~[`List<InputFile>`]~~ &rarr; **[`List<? extends InputFile>`]**) |  | [`IOException`] | ![Method parameter generics changed] |

___

<a id="user-content-dev.hardwood.metadata.columnindex"></a>
### `dev.hardwood.metadata.ColumnIndex`

- [ ] Binary-compatible
- [ ] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers        | Type  | Name          | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|------------------|-------|---------------|------------|--------|---------------------|-----------------------|
| Modified | `final` `public` | Class | `ColumnIndex` | [`Record`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Constructors

| Status  | Modifiers    | Generics | Constructor | Annotations | Throws | Compatibility Changes |
|---------|--------------|----------|-------------|-------------|--------|-----------------------|
| Removed | ~~`public`~~ |          | ~~`ColumnIndex`~~([`List<Boolean>`], [`List`], [`List`], [`BoundaryOrder`], [`List<Long>`], [`List<GeospatialStatistics>`]) |  |  | ![Constructor removed] |
| Added   | **`public`** |          | **`ColumnIndex`**([`List<Boolean>`], [`List`], [`List`], [`BoundaryOrder`], [`List<Long>`]) |  |  | ![No changes] |


#### Methods

| Status  | Modifiers    | Generics | Type                               | Method                       | Annotations | Throws | Compatibility Changes |
|---------|--------------|----------|------------------------------------|------------------------------|-------------|--------|-----------------------|
| Removed | ~~`public`~~ |          | ~~[`List<GeospatialStatistics>`]~~ | ~~`geospatialStatistics`~~() |             |        | ![Method removed]     |

___

<a id="user-content-dev.hardwood.reader.columnreader"></a>
### `dev.hardwood.reader.ColumnReader`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers | Type  | Name           | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|-----------|-------|----------------|------------|--------|---------------------|-----------------------|
| Modified | `public`  | Class | `ColumnReader` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Fields

| Status   | Modifiers                     | Type  | Name                 | Annotations | Compatibility Changes |
|----------|-------------------------------|-------|----------------------|-------------|-----------------------|
| Modified | **`public`** `static` `final` | `int` | `DEFAULT_BATCH_SIZE` |             | ![No changes]         |

___

<a id="user-content-dev.hardwood.reader.columnreaders"></a>
### `dev.hardwood.reader.ColumnReaders`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers | Type  | Name            | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|-----------|-------|-----------------|------------|--------|---------------------|-----------------------|
| Modified | `public`  | Class | `ColumnReaders` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |

___

<a id="user-content-dev.hardwood.reader.parquetfilereader"></a>
### `dev.hardwood.reader.ParquetFileReader`

- [X] Binary-compatible
- [ ] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers | Type  | Name                | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|-----------|-------|---------------------|------------|--------|---------------------|-----------------------|
| Modified | `public`  | Class | `ParquetFileReader` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Methods

| Status              | Modifiers         | Generics | Type                  | Method | Annotations | Throws          | Compatibility Changes |
|---------------------|-------------------|----------|-----------------------|--------|-------------|-----------------|-----------------------|
| Source-incompatible | `static` `public` |          | [`ParquetFileReader`] | `openAll`(~~[`List<InputFile>`]~~ &rarr; **[`List<? extends InputFile>`]**) |  | [`IOException`] | ![Method parameter generics changed] |
| Source-incompatible | `static` `public` |          | [`ParquetFileReader`] | `openAll`(~~[`List<InputFile>`]~~ &rarr; **[`List<? extends InputFile>`]**, [`HardwoodContext`]) |  | [`IOException`] | ![Method parameter generics changed] |

___

<a id="user-content-dev.hardwood.reader.parquetfilereader$columnreaderbuilder"></a>
### `dev.hardwood.reader.ParquetFileReader$ColumnReaderBuilder`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers                 | Type  | Name                  | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|---------------------------|-------|-----------------------|------------|--------|---------------------|-----------------------|
| Modified | `final` `static` `public` | Class | `ColumnReaderBuilder` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers    | Generics | Type                        | Method                 | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-----------------------------|------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **[`ColumnReaderBuilder`]** | **`batchSize`**(`int`) |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.reader.parquetfilereader$columnreadersbuilder"></a>
### `dev.hardwood.reader.ParquetFileReader$ColumnReadersBuilder`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers                 | Type  | Name                   | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|---------------------------|-------|------------------------|------------|--------|---------------------|-----------------------|
| Modified | `final` `static` `public` | Class | `ColumnReadersBuilder` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers    | Generics | Type                         | Method                 | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|------------------------------|------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **[`ColumnReadersBuilder`]** | **`batchSize`**(`int`) |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.reader.parquetfilereader$rowreaderbuilder"></a>
### `dev.hardwood.reader.ParquetFileReader$RowReaderBuilder`

- [ ] Binary-compatible
- [ ] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers                 | Type  | Name               | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|---------------------------|-------|--------------------|------------|--------|---------------------|-----------------------|
| Modified | `final` `static` `public` | Class | `RowReaderBuilder` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Methods

| Status  | Modifiers    | Generics | Type                     | Method                 | Annotations | Throws | Compatibility Changes |
|---------|--------------|----------|--------------------------|------------------------|-------------|--------|-----------------------|
| Removed | ~~`public`~~ |          | ~~[`RowReaderBuilder`]~~ | ~~`firstRow`~~(`long`) |             |        | ![Method removed]     |
| Added   | **`public`** |          | **[`RowReaderBuilder`]** | **`skip`**(`long`)     |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.reader.rowreader"></a>
### `dev.hardwood.reader.RowReader`

- [ ] Binary-compatible
- [ ] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers           | Type      | Name        | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|---------------------|-----------|-------------|------------|--------|---------------------|-----------------------|
| Modified | `public` `abstract` | Interface | `RowReader` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Implemented Interfaces

| Status              | Interface          | Compatibility Changes |
|---------------------|--------------------|-----------------------|
| Source-incompatible | [`FieldAccessor`]  | ![No changes]         |
| Source-incompatible | [`StructAccessor`] | ![No changes]         |


#### Methods

| Status  | Modifiers                 | Generics | Type              | Method | Annotations | Throws | Compatibility Changes |
|---------|---------------------------|----------|-------------------|--------|-------------|--------|-----------------------|
| Removed | ~~`static`~~ ~~`public`~~ |          | ~~[`RowReader`]~~ | ~~`create`~~([`RowGroupIterator`], [`FileSchema`], [`ProjectedSchema`], [`HardwoodContextImpl`], [`ResolvedPredicate`], `long`) |  |  | ![Method removed] |
| Added   | **`static`** **`public`** |          | **[`RowReader`]** | **`create`**([`RowGroupIterator`], [`FileSchema`], [`ProjectedSchema`][1], [`HardwoodContextImpl`], [`ResolvedPredicate`], `long`) |  |  | ![Method new static added to interface] |

___

<a id="user-content-dev.hardwood.row.fieldaccessor"></a>
### `dev.hardwood.row.FieldAccessor`

- [X] Binary-compatible
- [ ] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers           | Type      | Name            | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|---------------------|-----------|-----------------|------------|--------|---------------------|-----------------------|
| Modified | `public` `abstract` | Interface | `FieldAccessor` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers                   | Generics | Type                  | Method                              | Annotations | Throws | Compatibility Changes |
|--------|-----------------------------|----------|-----------------------|-------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** **`abstract`** |          | **[`LocalDateTime`]** | **`getLocalTimestamp`**([`String`]) |             |        | ![Method added to interface] |

___

<a id="user-content-dev.hardwood.row.pqlist"></a>
### `dev.hardwood.row.PqList`

- [X] Binary-compatible
- [ ] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers           | Type      | Name     | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|---------------------|-----------|----------|------------|--------|---------------------|-----------------------|
| Modified | `public` `abstract` | Interface | `PqList` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers                   | Generics | Type                        | Method                  | Annotations | Throws | Compatibility Changes |
|--------|-----------------------------|----------|-----------------------------|-------------------------|-------------|--------|-----------------------|
| Added  | **`public`** **`abstract`** |          | **[`List<LocalDateTime>`]** | **`localTimestamps`**() |             |        | ![Method added to interface] |

___

<a id="user-content-dev.hardwood.row.pqmap$entry"></a>
### `dev.hardwood.row.PqMap$Entry`

- [X] Binary-compatible
- [ ] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers                    | Type      | Name    | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|------------------------------|-----------|---------|------------|--------|---------------------|-----------------------|
| Modified | `static` `public` `abstract` | Interface | `Entry` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers                   | Generics | Type                  | Method                         | Annotations | Throws | Compatibility Changes |
|--------|-----------------------------|----------|-----------------------|--------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** **`abstract`** |          | **[`LocalDateTime`]** | **`getLocalTimestampValue`**() |             |        | ![Method added to interface] |

___

<a id="user-content-dev.hardwood.row.pqvariant"></a>
### `dev.hardwood.row.PqVariant`

- [X] Binary-compatible
- [ ] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers           | Type      | Name        | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|---------------------|-----------|-------------|------------|--------|---------------------|-----------------------|
| Modified | `public` `abstract` | Interface | `PqVariant` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers                   | Generics | Type                  | Method                   | Annotations | Throws | Compatibility Changes |
|--------|-----------------------------|----------|-----------------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`public`** **`abstract`** |          | **[`LocalDateTime`]** | **`asLocalTimestamp`**() |             |        | ![Method added to interface] |

___

<a id="user-content-dev.hardwood.row.structaccessor"></a>
### `dev.hardwood.row.StructAccessor`

- [X] Binary-compatible
- [ ] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers           | Type      | Name             | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|---------------------|-----------|------------------|------------|--------|---------------------|-----------------------|
| Modified | `public` `abstract` | Interface | `StructAccessor` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Implemented Interfaces

| Status              | Interface         | Compatibility Changes |
|---------------------|-------------------|-----------------------|
| Source-incompatible | [`FieldAccessor`] | ![No changes]         |


#### Methods

| Status | Modifiers                   | Generics | Type                  | Method                         | Annotations | Throws | Compatibility Changes |
|--------|-----------------------------|----------|-----------------------|--------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** **`abstract`** |          | **[`LocalDateTime`]** | **`getLocalTimestamp`**(`int`) |             |        | ![Method added to interface] |

___

<a id="user-content-dev.hardwood.row.varianttypeexception"></a>
### `dev.hardwood.row.VariantTypeException`

- [ ] Binary-compatible
- [ ] Source-compatible
- [ ] Serialization-compatible

| Status   | Modifiers | Type  | Name                   | Extends              | JDK    | Serialization                       | Compatibility Changes |
|----------|-----------|-------|------------------------|----------------------|--------|-------------------------------------|-----------------------|
| Modified | `public`  | Class | `VariantTypeException` | [`RuntimeException`] | JDK 21 | ![Default serialversionuid changed] | ![No changes]         |


#### Methods

| Status  | Modifiers                 | Generics | Type                         | Method                                           | Annotations | Throws | Compatibility Changes |
|---------|---------------------------|----------|------------------------------|--------------------------------------------------|-------------|--------|-----------------------|
| Removed | ~~`static`~~ ~~`public`~~ |          | ~~[`VariantTypeException`]~~ | ~~`expected`~~([`VariantType`], [`VariantType`]) |             |        | ![Method removed]     |
| Removed | ~~`static`~~ ~~`public`~~ |          | ~~[`VariantTypeException`]~~ | ~~`expectedOneOf`~~([`String`], [`VariantType`]) |             |        | ![Method removed]     |

___

<a id="user-content-dev.hardwood.schema.projectedschema"></a>
### `dev.hardwood.schema.ProjectedSchema`

- [ ] Binary-compatible
- [ ] Source-compatible
- [X] Serialization-compatible

| Status  | Modifiers                | Type      | Name                  | Extends        | JDK        | Serialization       | Compatibility Changes |
|---------|--------------------------|-----------|-----------------------|----------------|------------|---------------------|-----------------------|
| Removed | ~~`final`~~ ~~`public`~~ | ~~Class~~ | ~~`ProjectedSchema`~~ | ~~[`Object`]~~ | ~~JDK 21~~ | ![Not serializable] | ![Class removed] ![Superclass removed] |


#### Methods

| Status  | Modifiers                 | Generics | Type                       | Method                                             | Annotations | Throws | Compatibility Changes |
|---------|---------------------------|----------|----------------------------|----------------------------------------------------|-------------|--------|-----------------------|
| Removed | ~~`static`~~ ~~`public`~~ |          | ~~[`ProjectedSchema`]~~    | ~~`create`~~([`FileSchema`], [`ColumnProjection`]) |             |        | ![Method removed]     |
| Removed | ~~`public`~~              |          | ~~[`FileSchema`]~~         | ~~`getOriginalSchema`~~()                          |             |        | ![Method removed]     |
| Removed | ~~`public`~~              |          | ~~[`ColumnSchema`]~~       | ~~`getProjectedColumn`~~(`int`)                    |             |        | ![Method removed]     |
| Removed | ~~`public`~~              |          | ~~`int`~~                  | ~~`getProjectedColumnCount`~~()                    |             |        | ![Method removed]     |
| Removed | ~~`public`~~              |          | ~~[`List<ColumnSchema>`]~~ | ~~`getProjectedColumns`~~()                        |             |        | ![Method removed]     |
| Removed | ~~`public`~~              |          | ~~`int[]`~~                | ~~`getProjectedFieldIndices`~~()                   |             |        | ![Method removed]     |
| Removed | ~~`public`~~              |          | ~~`boolean`~~              | ~~`projectsAll`~~()                                |             |        | ![Method removed]     |
| Removed | ~~`public`~~              |          | ~~`int`~~                  | ~~`toOriginalIndex`~~(`int`)                       |             |        | ![Method removed]     |
| Removed | ~~`public`~~              |          | ~~`int[]`~~                | ~~`toOriginalIndices`~~()                          |             |        | ![Method removed]     |
| Removed | ~~`public`~~              |          | ~~`int`~~                  | ~~`toProjectedIndex`~~(`int`)                      |             |        | ![Method removed]     |


</details>


___

*Generated on: 2026-06-05 09:46:41.744+0000*.

[1]: # "dev.hardwood.internal.schema.ProjectedSchema"
[Class removed]: https://img.shields.io/badge/Class_removed-red "Class removed"
[Constructor removed]: https://img.shields.io/badge/Constructor_removed-red "Constructor removed"
[Default serialversionuid changed]: https://img.shields.io/badge/Incompatible-red "Default serialversionuid changed"
[Method added to interface]: https://img.shields.io/badge/Method_added_to_interface-orange "Method added to interface"
[Method added to public class]: https://img.shields.io/badge/Method_added_to_public_class-yellow "Method added to public class"
[Method new static added to interface]: https://img.shields.io/badge/Method_new_static_added_to_interface-orange "Method new static added to interface"
[Method parameter generics changed]: https://img.shields.io/badge/Method_parameter_generics_changed-orange "Method parameter generics changed"
[Method removed]: https://img.shields.io/badge/Method_removed-red "Method removed"
[No changes]: https://img.shields.io/badge/No_changes-green "No changes"
[Not serializable]: https://img.shields.io/badge/Not_serializable-green "Not serializable"
[Superclass removed]: https://img.shields.io/badge/Superclass_removed-red "Superclass removed"
[`BoundaryOrder`]: # "dev.hardwood.metadata.ColumnIndex$BoundaryOrder"
[`ColumnProjection`]: # "dev.hardwood.schema.ColumnProjection"
[`ColumnReaderBuilder`]: # "dev.hardwood.reader.ParquetFileReader$ColumnReaderBuilder"
[`ColumnReadersBuilder`]: # "dev.hardwood.reader.ParquetFileReader$ColumnReadersBuilder"
[`ColumnSchema`]: # "dev.hardwood.schema.ColumnSchema"
[`FieldAccessor`]: # "dev.hardwood.row.FieldAccessor"
[`FileSchema`]: # "dev.hardwood.schema.FileSchema"
[`HardwoodContextImpl`]: # "dev.hardwood.internal.reader.HardwoodContextImpl"
[`HardwoodContext`]: # "dev.hardwood.HardwoodContext"
[`IOException`]: # "java.io.IOException"
[`List<? extends InputFile>`]: # "java.util.List<? extends dev.hardwood.InputFile>"
[`List<Boolean>`]: # "java.util.List<java.lang.Boolean>"
[`List<ColumnSchema>`]: # "java.util.List<dev.hardwood.schema.ColumnSchema>"
[`List<GeospatialStatistics>`]: # "java.util.List<dev.hardwood.metadata.GeospatialStatistics>"
[`List<InputFile>`]: # "java.util.List<dev.hardwood.InputFile>"
[`List<LocalDateTime>`]: # "java.util.List<java.time.LocalDateTime>"
[`List<Long>`]: # "java.util.List<java.lang.Long>"
[`List`]: # "java.util.List"
[`LocalDateTime`]: # "java.time.LocalDateTime"
[`Object`]: # "java.lang.Object"
[`ParquetFileReader`]: # "dev.hardwood.reader.ParquetFileReader"
[`ProjectedSchema`]: # "dev.hardwood.schema.ProjectedSchema"
[`Record`]: # "java.lang.Record"
[`ResolvedPredicate`]: # "dev.hardwood.internal.predicate.ResolvedPredicate"
[`RowGroupIterator`]: # "dev.hardwood.internal.reader.RowGroupIterator"
[`RowReaderBuilder`]: # "dev.hardwood.reader.ParquetFileReader$RowReaderBuilder"
[`RowReader`]: # "dev.hardwood.reader.RowReader"
[`RuntimeException`]: # "java.lang.RuntimeException"
[`String`]: # "java.lang.String"
[`StructAccessor`]: # "dev.hardwood.row.StructAccessor"
[`VariantTypeException`]: # "dev.hardwood.row.VariantTypeException"
[`VariantType`]: # "dev.hardwood.row.VariantType"
[dev.hardwood.Hardwood]: #user-content-dev.hardwood.hardwood
[dev.hardwood.metadata.ColumnIndex]: #user-content-dev.hardwood.metadata.columnindex
[dev.hardwood.reader.ColumnReader]: #user-content-dev.hardwood.reader.columnreader
[dev.hardwood.reader.ColumnReaders]: #user-content-dev.hardwood.reader.columnreaders
[dev.hardwood.reader.ParquetFileReader]: #user-content-dev.hardwood.reader.parquetfilereader
[dev.hardwood.reader.ParquetFileReader$ColumnReaderBuilder]: #user-content-dev.hardwood.reader.parquetfilereader$columnreaderbuilder
[dev.hardwood.reader.ParquetFileReader$ColumnReadersBuilder]: #user-content-dev.hardwood.reader.parquetfilereader$columnreadersbuilder
[dev.hardwood.reader.ParquetFileReader$RowReaderBuilder]: #user-content-dev.hardwood.reader.parquetfilereader$rowreaderbuilder
[dev.hardwood.reader.RowReader]: #user-content-dev.hardwood.reader.rowreader
[dev.hardwood.row.FieldAccessor]: #user-content-dev.hardwood.row.fieldaccessor
[dev.hardwood.row.PqList]: #user-content-dev.hardwood.row.pqlist
[dev.hardwood.row.PqMap$Entry]: #user-content-dev.hardwood.row.pqmap$entry
[dev.hardwood.row.PqVariant]: #user-content-dev.hardwood.row.pqvariant
[dev.hardwood.row.StructAccessor]: #user-content-dev.hardwood.row.structaccessor
[dev.hardwood.row.VariantTypeException]: #user-content-dev.hardwood.row.varianttypeexception
[dev.hardwood.schema.ProjectedSchema]: #user-content-dev.hardwood.schema.projectedschema
