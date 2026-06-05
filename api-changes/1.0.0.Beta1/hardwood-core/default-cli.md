
# Compatibility Report

![semver MAJOR](https://img.shields.io/badge/semver-MAJOR-red?logo=semver "semver MAJOR")

## Summary

> [!CAUTION]
>
> Incompatible changes found while checking backward compatibility of version `1.0.0.Beta1` with the previous version `1.0.0.Alpha1`.

<details markdown="1">
<summary>Expand to see options used.</summary>

- **Report only summary**: No
- **Report only changes**: Yes
- **Report only binary-incompatible changes**: No
- **Access modifier filter**: `PROTECTED`
- **Old archives**:
  - ![hardwood-core 1.0.0.Alpha1](https://img.shields.io/badge/hardwood_core-1.0.0.Alpha1-blue "hardwood-core 1.0.0.Alpha1")
- **New archives**:
  - ![hardwood-core 1.0.0.Beta1](https://img.shields.io/badge/hardwood_core-1.0.0.Beta1-blue "hardwood-core 1.0.0.Beta1")
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
| Modified | [dev.hardwood.Hardwood]                                      | ![Not serializable] | ![Method removed] ![Method parameter generics changed] ![Method added to public class] |
| Added    | [dev.hardwood.InputFile]                                     | ![Not serializable] | ![Interface added]    |
| Added    | [dev.hardwood.jfr.BatchWaitEvent]                            | ![Not serializable] | ![Annotation added]   |
| Added    | [dev.hardwood.jfr.FileMappingEvent]                          | ![Not serializable] | ![Annotation added]   |
| Added    | [dev.hardwood.jfr.FileOpenedEvent]                           | ![Not serializable] | ![Annotation added]   |
| Added    | [dev.hardwood.jfr.PageDecodedEvent]                          | ![Not serializable] | ![Annotation added]   |
| Added    | [dev.hardwood.jfr.PageFilterEvent]                           | ![Not serializable] | ![Annotation added]   |
| Added    | [dev.hardwood.jfr.PrefetchMissEvent]                         | ![Not serializable] | ![Annotation added]   |
| Added    | [dev.hardwood.jfr.RecordFilterEvent]                         | ![Not serializable] | ![Annotation added]   |
| Added    | [dev.hardwood.jfr.RowGroupFilterEvent]                       | ![Not serializable] | ![Annotation added]   |
| Added    | [dev.hardwood.jfr.RowGroupScannedEvent]                      | ![Not serializable] | ![Annotation added]   |
| Modified | [dev.hardwood.metadata.ColumnChunk]                          | ![Not serializable] | ![Method added to public class] ![Constructor removed] |
| Added    | [dev.hardwood.metadata.ColumnIndex]                          | ![Not serializable] | ![Method added to public class] |
| Added    | [dev.hardwood.metadata.ColumnIndex$BoundaryOrder]            | ![Compatible]       | ![Interface added] ![Method added to public class] |
| Modified | [dev.hardwood.metadata.ColumnMetaData]                       | ![Not serializable] | ![Method return type changed] ![Method return type generics changed] ![Method added to public class] ![Constructor removed] |
| Added    | [dev.hardwood.metadata.FieldPath]                            | ![Not serializable] | ![Method added to public class] |
| Modified | [dev.hardwood.metadata.FileMetaData]                         | ![Not serializable] | ![Method added to public class] ![Constructor removed] |
| Added    | [dev.hardwood.metadata.OffsetIndex]                          | ![Not serializable] | ![Method added to public class] |
| Added    | [dev.hardwood.metadata.PageLocation]                         | ![Not serializable] | ![Method added to public class] |
| Added    | [dev.hardwood.metadata.Statistics]                           | ![Not serializable] | ![Method added to public class] |
| Modified | [dev.hardwood.reader.ColumnReader]                           | ![Not serializable] | ![No changes]         |
| Added    | [dev.hardwood.reader.FilterPredicate]                        | ![Not serializable] | ![No changes]         |
| Added    | [dev.hardwood.reader.FilterPredicate$And]                    | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added    | [dev.hardwood.reader.FilterPredicate$BinaryColumnPredicate]  | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added    | [dev.hardwood.reader.FilterPredicate$BinaryInPredicate]      | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added    | [dev.hardwood.reader.FilterPredicate$BooleanColumnPredicate] | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added    | [dev.hardwood.reader.FilterPredicate$DateColumnPredicate]    | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added    | [dev.hardwood.reader.FilterPredicate$DecimalColumnPredicate] | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added    | [dev.hardwood.reader.FilterPredicate$DoubleColumnPredicate]  | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added    | [dev.hardwood.reader.FilterPredicate$FloatColumnPredicate]   | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added    | [dev.hardwood.reader.FilterPredicate$InstantColumnPredicate] | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added    | [dev.hardwood.reader.FilterPredicate$IntColumnPredicate]     | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added    | [dev.hardwood.reader.FilterPredicate$IntInPredicate]         | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added    | [dev.hardwood.reader.FilterPredicate$IsNotNullPredicate]     | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added    | [dev.hardwood.reader.FilterPredicate$IsNullPredicate]        | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added    | [dev.hardwood.reader.FilterPredicate$LongColumnPredicate]    | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added    | [dev.hardwood.reader.FilterPredicate$LongInPredicate]        | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added    | [dev.hardwood.reader.FilterPredicate$Not]                    | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added    | [dev.hardwood.reader.FilterPredicate$Operator]               | ![Compatible]       | ![Interface added] ![Method added to public class] |
| Added    | [dev.hardwood.reader.FilterPredicate$Or]                     | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added    | [dev.hardwood.reader.FilterPredicate$SignedBinaryColumnPredicate] | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added    | [dev.hardwood.reader.FilterPredicate$TimeColumnPredicate]    | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Modified | [dev.hardwood.reader.MultiFileParquetReader]                 | ![Not serializable] | ![Method parameter generics changed] ![Method added to public class] |
| Modified | [dev.hardwood.reader.MultiFileRowReader]                     | ![Not serializable] | ![No changes]         |
| Modified | [dev.hardwood.reader.ParquetFileReader]                      | ![Not serializable] | ![Method removed] ![Method added to public class] |
| Modified | [dev.hardwood.reader.RowReader]                              | ![Not serializable] | ![Interface added]    |
| Modified | [dev.hardwood.row.PqStruct]                                  | ![Not serializable] | ![Interface added]    |
| Added    | [dev.hardwood.row.StructAccessor]                            | ![Not serializable] | ![No changes]         |
| Modified | [dev.hardwood.schema.ColumnSchema]                           | ![Not serializable] | ![Method added to public class] ![Constructor removed] |
| Modified | [dev.hardwood.schema.FileSchema]                             | ![Not serializable] | ![Method added to public class] |

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

| Status              | Modifiers                 | Generics | Type                           | Method                                                       | Annotations | Throws              | Compatibility Changes |
|---------------------|---------------------------|----------|--------------------------------|--------------------------------------------------------------|-------------|---------------------|-----------------------|
| Removed             | ~~`static`~~ ~~`public`~~ |          | ~~[`Hardwood`]~~               | ~~`create`~~(`int`)                                          |             |                     | ![Method removed]     |
| Removed             | ~~`public`~~              |          | ~~[`ParquetFileReader`]~~      | ~~`open`~~([`Path`])                                         |             | ~~[`IOException`]~~ | ![Method removed]     |
| Added               | **`public`**              |          | **[`ParquetFileReader`]**      | **`open`**([`InputFile`])                                    |             | **[`IOException`]** | ![Method added to public class] |
| Source-incompatible | `public`                  |          | [`MultiFileParquetReader`]     | `openAll`(~~[`List<Path>`]~~ &rarr; **[`List<InputFile>`]**) |             | [`IOException`]     | ![Method parameter generics changed] |
| Removed             | ~~`public`~~              |          | ~~[`MultiFileParquetReader`]~~ | ~~`openAll`~~([`Path`], [`Path...`])                         |             | ~~[`IOException`]~~ | ![Method removed]     |

___

<a id="user-content-dev.hardwood.inputfile"></a>
### `dev.hardwood.InputFile`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                   | Type          | Name            | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|-----------------------------|---------------|-----------------|----------------|------------|---------------------|-----------------------|
| Added  | **`public`** **`abstract`** | **Interface** | **`InputFile`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface             | Compatibility Changes |
|--------|-----------------------|-----------------------|
| Added  | **[`Closeable`]**     | ![No changes]         |
| Added  | **[`AutoCloseable`]** | ![No changes]         |


#### Methods

| Status | Modifiers                   | Generics | Type                    | Method                                             | Annotations | Throws              | Compatibility Changes |
|--------|-----------------------------|----------|-------------------------|----------------------------------------------------|-------------|---------------------|-----------------------|
| Added  | **`public`** **`abstract`** |          | **`long`**              | **`length`**()                                     |             | **[`IOException`]** | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`String`]**          | **`name`**()                                       |             |                     | ![No changes]         |
| Added  | **`static`** **`public`**   |          | **[`InputFile`]**       | **`of`**([`ByteBuffer`])                           |             |                     | ![No changes]         |
| Added  | **`static`** **`public`**   |          | **[`InputFile`]**       | **`of`**([`Path`])                                 |             |                     | ![No changes]         |
| Added  | **`static`** **`public`**   |          | **[`List<InputFile>`]** | **`ofBuffers`**([`List<ByteBuffer>`])              |             |                     | ![No changes]         |
| Added  | **`static`** **`public`**   |          | **[`List<InputFile>`]** | **`ofBuffers`**([`ByteBuffer`], [`ByteBuffer...`]) |             |                     | ![No changes]         |
| Added  | **`static`** **`public`**   |          | **[`List<InputFile>`]** | **`ofPaths`**([`List<Path>`])                      |             |                     | ![No changes]         |
| Added  | **`static`** **`public`**   |          | **[`List<InputFile>`]** | **`ofPaths`**([`Path`], [`Path...`])               |             |                     | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`void`**              | **`open`**()                                       |             | **[`IOException`]** | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`ByteBuffer`]**      | **`readRange`**(`long`, `int`)                     |             | **[`IOException`]** | ![No changes]         |

___

<a id="user-content-dev.hardwood.jfr.batchwaitevent"></a>
### `dev.hardwood.jfr.BatchWaitEvent`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers    | Type      | Name                 | Extends       | JDK        | Serialization       | Compatibility Changes |
|--------|--------------|-----------|----------------------|---------------|------------|---------------------|-----------------------|
| Added  | **`public`** | **Class** | **`BatchWaitEvent`** | **[`Event`]** | **JDK 21** | ![Not serializable] | ![Annotation added]   |


#### Annotations

| Status | Annotation                                                   | Compatibility Changes |
|--------|--------------------------------------------------------------|-----------------------|
| Added  | **[`Category`]**: **`value`**=**`{"Hardwood", "Pipeline"}`** | ![No changes]         |
| Added  | **[`Description`]**: **`value`**=**`"Consumer blocked waiting for the assembly pipeline to produce a batch"`** | ![No changes] |
| Added  | **[`Label`]**: **`value`**=**`"Batch Wait"`**                | ![No changes]         |
| Added  | **[`Name`]**: **`value`**=**`"dev.hardwood.BatchWait"`**     | ![No changes]         |
| Added  | **[`StackTrace`]**: **`value`**=**`false`**                  | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor            | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`BatchWaitEvent`**() |             |        | ![No changes]         |


#### Fields

| Status | Modifiers    | Type           | Name     | Annotations | Compatibility Changes |
|--------|--------------|----------------|----------|-------------|-----------------------|
| Added  | **`public`** | **[`String`]** | `column` | **[`Label`]**: **`value`**=**`"Column"`**<br>**[`Description`]**: **`value`**=**`"Name of the column being waited on"`** | ![Annotation added] |

___

<a id="user-content-dev.hardwood.jfr.filemappingevent"></a>
### `dev.hardwood.jfr.FileMappingEvent`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers    | Type      | Name                   | Extends       | JDK        | Serialization       | Compatibility Changes |
|--------|--------------|-----------|------------------------|---------------|------------|---------------------|-----------------------|
| Added  | **`public`** | **Class** | **`FileMappingEvent`** | **[`Event`]** | **JDK 21** | ![Not serializable] | ![Annotation added]   |


#### Annotations

| Status | Annotation                                                 | Compatibility Changes |
|--------|------------------------------------------------------------|-----------------------|
| Added  | **[`Category`]**: **`value`**=**`{"Hardwood", "I/O"}`**    | ![No changes]         |
| Added  | **[`Description`]**: **`value`**=**`"Memory-mapping of a file region for reading Parquet data"`** | ![No changes] |
| Added  | **[`Label`]**: **`value`**=**`"File Mapping"`**            | ![No changes]         |
| Added  | **[`Name`]**: **`value`**=**`"dev.hardwood.FileMapping"`** | ![No changes]         |
| Added  | **[`StackTrace`]**: **`value`**=**`false`**                | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor              | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|--------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`FileMappingEvent`**() |             |        | ![No changes]         |


#### Fields

| Status | Modifiers    | Type           | Name     | Annotations | Compatibility Changes |
|--------|--------------|----------------|----------|-------------|-----------------------|
| Added  | **`public`** | **[`String`]** | `file`   | **[`Label`]**: **`value`**=**`"File"`**<br>**[`Description`]**: **`value`**=**`"Name of the file being mapped"`** | ![Annotation added] |
| Added  | **`public`** | **`long`**     | `offset` | **[`Label`]**: **`value`**=**`"Offset"`**<br>**[`Description`]**: **`value`**=**`"Starting offset in the file (bytes)"`** | ![Annotation added] |
| Added  | **`public`** | **`long`**     | `size`   | **[`Label`]**: **`value`**=**`"Size"`**<br>**[`Description`]**: **`value`**=**`"Size of the mapped region (bytes)"`**<br>**[`DataAmount`]** | ![Annotation added] |

___

<a id="user-content-dev.hardwood.jfr.fileopenedevent"></a>
### `dev.hardwood.jfr.FileOpenedEvent`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers    | Type      | Name                  | Extends       | JDK        | Serialization       | Compatibility Changes |
|--------|--------------|-----------|-----------------------|---------------|------------|---------------------|-----------------------|
| Added  | **`public`** | **Class** | **`FileOpenedEvent`** | **[`Event`]** | **JDK 21** | ![Not serializable] | ![Annotation added]   |


#### Annotations

| Status | Annotation                                                | Compatibility Changes |
|--------|-----------------------------------------------------------|-----------------------|
| Added  | **[`Category`]**: **`value`**=**`{"Hardwood", "I/O"}`**   | ![No changes]         |
| Added  | **[`Description`]**: **`value`**=**`"Opening a Parquet file and reading its metadata"`** | ![No changes] |
| Added  | **[`Label`]**: **`value`**=**`"File Opened"`**            | ![No changes]         |
| Added  | **[`Name`]**: **`value`**=**`"dev.hardwood.FileOpened"`** | ![No changes]         |
| Added  | **[`StackTrace`]**: **`value`**=**`false`**               | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor             | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`FileOpenedEvent`**() |             |        | ![No changes]         |


#### Fields

| Status | Modifiers    | Type           | Name            | Annotations | Compatibility Changes |
|--------|--------------|----------------|-----------------|-------------|-----------------------|
| Added  | **`public`** | **`int`**      | `columnCount`   | **[`Label`]**: **`value`**=**`"Column Count"`**<br>**[`Description`]**: **`value`**=**`"Number of columns in the file schema"`** | ![Annotation added] |
| Added  | **`public`** | **[`String`]** | `file`          | **[`Label`]**: **`value`**=**`"File"`**<br>**[`Description`]**: **`value`**=**`"Name of the Parquet file"`** | ![Annotation added] |
| Added  | **`public`** | **`long`**     | `fileSize`      | **[`Label`]**: **`value`**=**`"File Size"`**<br>**[`Description`]**: **`value`**=**`"Size of the file (bytes)"`**<br>**[`DataAmount`]** | ![Annotation added] |
| Added  | **`public`** | **`int`**      | `rowGroupCount` | **[`Label`]**: **`value`**=**`"Row Group Count"`**<br>**[`Description`]**: **`value`**=**`"Number of row groups in the file"`** | ![Annotation added] |

___

<a id="user-content-dev.hardwood.jfr.pagedecodedevent"></a>
### `dev.hardwood.jfr.PageDecodedEvent`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers    | Type      | Name                   | Extends       | JDK        | Serialization       | Compatibility Changes |
|--------|--------------|-----------|------------------------|---------------|------------|---------------------|-----------------------|
| Added  | **`public`** | **Class** | **`PageDecodedEvent`** | **[`Event`]** | **JDK 21** | ![Not serializable] | ![Annotation added]   |


#### Annotations

| Status | Annotation                                                 | Compatibility Changes |
|--------|------------------------------------------------------------|-----------------------|
| Added  | **[`Category`]**: **`value`**=**`{"Hardwood", "Decode"}`** | ![No changes]         |
| Added  | **[`Description`]**: **`value`**=**`"Decoding of a single Parquet data page"`** | ![No changes] |
| Added  | **[`Label`]**: **`value`**=**`"Page Decoded"`**            | ![No changes]         |
| Added  | **[`Name`]**: **`value`**=**`"dev.hardwood.PageDecoded"`** | ![No changes]         |
| Added  | **[`StackTrace`]**: **`value`**=**`false`**                | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor              | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|--------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`PageDecodedEvent`**() |             |        | ![No changes]         |


#### Fields

| Status | Modifiers    | Type           | Name               | Annotations | Compatibility Changes |
|--------|--------------|----------------|--------------------|-------------|-----------------------|
| Added  | **`public`** | **[`String`]** | `column`           | **[`Label`]**: **`value`**=**`"Column"`**<br>**[`Description`]**: **`value`**=**`"Name of the column being decoded"`** | ![Annotation added] |
| Added  | **`public`** | **`int`**      | `compressedSize`   | **[`Label`]**: **`value`**=**`"Compressed Size"`**<br>**[`Description`]**: **`value`**=**`"Compressed size of the page data (bytes)"`**<br>**[`DataAmount`]** | ![Annotation added] |
| Added  | **`public`** | **`int`**      | `uncompressedSize` | **[`Label`]**: **`value`**=**`"Uncompressed Size"`**<br>**[`Description`]**: **`value`**=**`"Uncompressed size of the page data (bytes)"`**<br>**[`DataAmount`]** | ![Annotation added] |

___

<a id="user-content-dev.hardwood.jfr.pagefilterevent"></a>
### `dev.hardwood.jfr.PageFilterEvent`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers    | Type      | Name                  | Extends       | JDK        | Serialization       | Compatibility Changes |
|--------|--------------|-----------|-----------------------|---------------|------------|---------------------|-----------------------|
| Added  | **`public`** | **Class** | **`PageFilterEvent`** | **[`Event`]** | **JDK 21** | ![Not serializable] | ![Annotation added]   |


#### Annotations

| Status | Annotation                                                 | Compatibility Changes |
|--------|------------------------------------------------------------|-----------------------|
| Added  | **[`Category`]**: **`value`**=**`{"Hardwood", "Filter"}`** | ![No changes]         |
| Added  | **[`Description`]**: **`value`**=**`"Pages filtered by Column Index predicate push-down"`** | ![No changes] |
| Added  | **[`Label`]**: **`value`**=**`"Page Filter"`**             | ![No changes]         |
| Added  | **[`Name`]**: **`value`**=**`"dev.hardwood.PageFilter"`**  | ![No changes]         |
| Added  | **[`StackTrace`]**: **`value`**=**`false`**                | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor             | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`PageFilterEvent`**() |             |        | ![No changes]         |


#### Fields

| Status | Modifiers    | Type           | Name            | Annotations | Compatibility Changes |
|--------|--------------|----------------|-----------------|-------------|-----------------------|
| Added  | **`public`** | **[`String`]** | `column`        | **[`Label`]**: **`value`**=**`"Column"`**<br>**[`Description`]**: **`value`**=**`"Name of the column being filtered"`** | ![Annotation added] |
| Added  | **`public`** | **[`String`]** | `file`          | **[`Label`]**: **`value`**=**`"File"`**<br>**[`Description`]**: **`value`**=**`"Name of the Parquet file"`** | ![Annotation added] |
| Added  | **`public`** | **`int`**      | `pagesKept`     | **[`Label`]**: **`value`**=**`"Pages Kept"`**<br>**[`Description`]**: **`value`**=**`"Number of pages kept after filtering"`** | ![Annotation added] |
| Added  | **`public`** | **`int`**      | `pagesSkipped`  | **[`Label`]**: **`value`**=**`"Pages Skipped"`**<br>**[`Description`]**: **`value`**=**`"Number of pages skipped by the filter"`** | ![Annotation added] |
| Added  | **`public`** | **`int`**      | `rowGroupIndex` | **[`Label`]**: **`value`**=**`"Row Group Index"`**<br>**[`Description`]**: **`value`**=**`"Index of the row group within the file"`** | ![Annotation added] |
| Added  | **`public`** | **`int`**      | `totalPages`    | **[`Label`]**: **`value`**=**`"Total Pages"`**<br>**[`Description`]**: **`value`**=**`"Total number of data pages before filtering"`** | ![Annotation added] |

___

<a id="user-content-dev.hardwood.jfr.prefetchmissevent"></a>
### `dev.hardwood.jfr.PrefetchMissEvent`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers    | Type      | Name                    | Extends       | JDK        | Serialization       | Compatibility Changes |
|--------|--------------|-----------|-------------------------|---------------|------------|---------------------|-----------------------|
| Added  | **`public`** | **Class** | **`PrefetchMissEvent`** | **[`Event`]** | **JDK 21** | ![Not serializable] | ![Annotation added]   |


#### Annotations

| Status | Annotation                                                   | Compatibility Changes |
|--------|--------------------------------------------------------------|-----------------------|
| Added  | **[`Category`]**: **`value`**=**`{"Hardwood", "Pipeline"}`** | ![No changes]         |
| Added  | **[`Description`]**: **`value`**=**`"Prefetch queue miss requiring synchronous decode or blocking wait"`** | ![No changes] |
| Added  | **[`Label`]**: **`value`**=**`"Prefetch Miss"`**             | ![No changes]         |
| Added  | **[`Name`]**: **`value`**=**`"dev.hardwood.PrefetchMiss"`**  | ![No changes]         |
| Added  | **[`StackTrace`]**: **`value`**=**`false`**                  | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor               | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|---------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`PrefetchMissEvent`**() |             |        | ![No changes]         |


#### Fields

| Status | Modifiers    | Type           | Name         | Annotations | Compatibility Changes |
|--------|--------------|----------------|--------------|-------------|-----------------------|
| Added  | **`public`** | **[`String`]** | `column`     | **[`Label`]**: **`value`**=**`"Column"`**<br>**[`Description`]**: **`value`**=**`"Name of the column experiencing the miss"`** | ![Annotation added] |
| Added  | **`public`** | **[`String`]** | `file`       | **[`Label`]**: **`value`**=**`"File"`**<br>**[`Description`]**: **`value`**=**`"Name of the current file being read"`** | ![Annotation added] |
| Added  | **`public`** | **`int`**      | `newDepth`   | **[`Label`]**: **`value`**=**`"New Depth"`**<br>**[`Description`]**: **`value`**=**`"Updated prefetch depth after the miss"`** | ![Annotation added] |
| Added  | **`public`** | **`boolean`**  | `queueEmpty` | **[`Label`]**: **`value`**=**`"Queue Empty"`**<br>**[`Description`]**: **`value`**=**`"True if the prefetch queue was completely empty"`** | ![Annotation added] |

___

<a id="user-content-dev.hardwood.jfr.recordfilterevent"></a>
### `dev.hardwood.jfr.RecordFilterEvent`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers    | Type      | Name                    | Extends       | JDK        | Serialization       | Compatibility Changes |
|--------|--------------|-----------|-------------------------|---------------|------------|---------------------|-----------------------|
| Added  | **`public`** | **Class** | **`RecordFilterEvent`** | **[`Event`]** | **JDK 21** | ![Not serializable] | ![Annotation added]   |


#### Annotations

| Status | Annotation                                                  | Compatibility Changes |
|--------|-------------------------------------------------------------|-----------------------|
| Added  | **[`Category`]**: **`value`**=**`{"Hardwood", "Filter"}`**  | ![No changes]         |
| Added  | **[`Description`]**: **`value`**=**`"Records filtered by record-level predicate evaluation"`** | ![No changes] |
| Added  | **[`Label`]**: **`value`**=**`"Record Filter"`**            | ![No changes]         |
| Added  | **[`Name`]**: **`value`**=**`"dev.hardwood.RecordFilter"`** | ![No changes]         |
| Added  | **[`StackTrace`]**: **`value`**=**`false`**                 | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor               | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|---------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`RecordFilterEvent`**() |             |        | ![No changes]         |


#### Fields

| Status | Modifiers    | Type       | Name             | Annotations | Compatibility Changes |
|--------|--------------|------------|------------------|-------------|-----------------------|
| Added  | **`public`** | **`long`** | `recordsKept`    | **[`Label`]**: **`value`**=**`"Records Kept"`**<br>**[`Description`]**: **`value`**=**`"Number of records that matched the predicate"`** | ![Annotation added] |
| Added  | **`public`** | **`long`** | `recordsSkipped` | **[`Label`]**: **`value`**=**`"Records Skipped"`**<br>**[`Description`]**: **`value`**=**`"Number of records skipped by the predicate"`** | ![Annotation added] |
| Added  | **`public`** | **`long`** | `totalRecords`   | **[`Label`]**: **`value`**=**`"Total Records"`**<br>**[`Description`]**: **`value`**=**`"Total number of records evaluated against the predicate"`** | ![Annotation added] |

___

<a id="user-content-dev.hardwood.jfr.rowgroupfilterevent"></a>
### `dev.hardwood.jfr.RowGroupFilterEvent`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers    | Type      | Name                      | Extends       | JDK        | Serialization       | Compatibility Changes |
|--------|--------------|-----------|---------------------------|---------------|------------|---------------------|-----------------------|
| Added  | **`public`** | **Class** | **`RowGroupFilterEvent`** | **[`Event`]** | **JDK 21** | ![Not serializable] | ![Annotation added]   |


#### Annotations

| Status | Annotation                                                    | Compatibility Changes |
|--------|---------------------------------------------------------------|-----------------------|
| Added  | **[`Category`]**: **`value`**=**`{"Hardwood", "Filter"}`**    | ![No changes]         |
| Added  | **[`Description`]**: **`value`**=**`"Row groups filtered by predicate push-down"`** | ![No changes] |
| Added  | **[`Label`]**: **`value`**=**`"Row Group Filter"`**           | ![No changes]         |
| Added  | **[`Name`]**: **`value`**=**`"dev.hardwood.RowGroupFilter"`** | ![No changes]         |
| Added  | **[`StackTrace`]**: **`value`**=**`false`**                   | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor                 | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-----------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`RowGroupFilterEvent`**() |             |        | ![No changes]         |


#### Fields

| Status | Modifiers    | Type           | Name               | Annotations | Compatibility Changes |
|--------|--------------|----------------|--------------------|-------------|-----------------------|
| Added  | **`public`** | **[`String`]** | `file`             | **[`Label`]**: **`value`**=**`"File"`**<br>**[`Description`]**: **`value`**=**`"Name of the Parquet file"`** | ![Annotation added] |
| Added  | **`public`** | **`int`**      | `rowGroupsKept`    | **[`Label`]**: **`value`**=**`"Row Groups Kept"`**<br>**[`Description`]**: **`value`**=**`"Number of row groups kept after filtering"`** | ![Annotation added] |
| Added  | **`public`** | **`int`**      | `rowGroupsSkipped` | **[`Label`]**: **`value`**=**`"Row Groups Skipped"`**<br>**[`Description`]**: **`value`**=**`"Number of row groups skipped by the filter"`** | ![Annotation added] |
| Added  | **`public`** | **`int`**      | `totalRowGroups`   | **[`Label`]**: **`value`**=**`"Total Row Groups"`**<br>**[`Description`]**: **`value`**=**`"Total number of row groups in the file before filtering"`** | ![Annotation added] |

___

<a id="user-content-dev.hardwood.jfr.rowgroupscannedevent"></a>
### `dev.hardwood.jfr.RowGroupScannedEvent`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers    | Type      | Name                       | Extends       | JDK        | Serialization       | Compatibility Changes |
|--------|--------------|-----------|----------------------------|---------------|------------|---------------------|-----------------------|
| Added  | **`public`** | **Class** | **`RowGroupScannedEvent`** | **[`Event`]** | **JDK 21** | ![Not serializable] | ![Annotation added]   |


#### Annotations

| Status | Annotation                                                     | Compatibility Changes |
|--------|----------------------------------------------------------------|-----------------------|
| Added  | **[`Category`]**: **`value`**=**`{"Hardwood", "Decode"}`**     | ![No changes]         |
| Added  | **[`Description`]**: **`value`**=**`"Scanning of page boundaries in a row group column chunk"`** | ![No changes] |
| Added  | **[`Label`]**: **`value`**=**`"Row Group Scanned"`**           | ![No changes]         |
| Added  | **[`Name`]**: **`value`**=**`"dev.hardwood.RowGroupScanned"`** | ![No changes]         |
| Added  | **[`StackTrace`]**: **`value`**=**`false`**                    | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor                  | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`RowGroupScannedEvent`**() |             |        | ![No changes]         |


#### Fields

| Status | Modifiers                             | Type           | Name                    | Annotations | Compatibility Changes |
|--------|---------------------------------------|----------------|-------------------------|-------------|-----------------------|
| Added  | **`public`** **`static`** **`final`** | **[`String`]** | `STRATEGY_OFFSET_INDEX` |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`String`]** | `STRATEGY_SEQUENTIAL`   |             | ![No changes]         |
| Added  | **`public`**                          | **[`String`]** | `column`                | **[`Label`]**: **`value`**=**`"Column"`**<br>**[`Description`]**: **`value`**=**`"Name of the column being scanned"`** | ![Annotation added] |
| Added  | **`public`**                          | **[`String`]** | `file`                  | **[`Label`]**: **`value`**=**`"File"`**<br>**[`Description`]**: **`value`**=**`"Path to the Parquet file"`** | ![Annotation added] |
| Added  | **`public`**                          | **`int`**      | `pageCount`             | **[`Label`]**: **`value`**=**`"Page Count"`**<br>**[`Description`]**: **`value`**=**`"Number of data pages found in this row group column chunk"`** | ![Annotation added] |
| Added  | **`public`**                          | **`int`**      | `rowGroupIndex`         | **[`Label`]**: **`value`**=**`"Row Group Index"`**<br>**[`Description`]**: **`value`**=**`"Index of the row group within the file"`** | ![Annotation added] |
| Added  | **`public`**                          | **[`String`]** | `scanStrategy`          | **[`Label`]**: **`value`**=**`"Scan Strategy"`**<br>**[`Description`]**: **`value`**=**`"How pages were located: 'sequential' (header scan) or 'offset-index' (direct lookup)"`** | ![Annotation added] |

___

<a id="user-content-dev.hardwood.metadata.columnchunk"></a>
### `dev.hardwood.metadata.ColumnChunk`

- [ ] Binary-compatible
- [ ] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers        | Type  | Name          | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|------------------|-------|---------------|------------|--------|---------------------|-----------------------|
| Modified | `final` `public` | Class | `ColumnChunk` | [`Record`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Constructors

| Status  | Modifiers    | Generics | Constructor                           | Annotations | Throws | Compatibility Changes |
|---------|--------------|----------|---------------------------------------|-------------|--------|-----------------------|
| Removed | ~~`public`~~ |          | ~~`ColumnChunk`~~([`ColumnMetaData`]) |             |        | ![Constructor removed] |
| Added   | **`public`** |          | **`ColumnChunk`**([`ColumnMetaData`], [`Long`], [`Integer`], [`Long`], [`Integer`]) |  |  | ![No changes] |


#### Methods

| Status | Modifiers    | Generics | Type            | Method                    | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-----------------|---------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **[`Integer`]** | **`columnIndexLength`**() |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`Long`]**    | **`columnIndexOffset`**() |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`Integer`]** | **`offsetIndexLength`**() |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`Long`]**    | **`offsetIndexOffset`**() |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.metadata.columnindex"></a>
### `dev.hardwood.metadata.ColumnIndex`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                | Type      | Name              | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|--------------------------|-----------|-------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`public`** | **Class** | **`ColumnIndex`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`ColumnIndex`**([`List<Boolean>`], [`List`], [`List`], [`BoundaryOrder`], [`List<Long>`]) |  |  | ![No changes] |


#### Methods

| Status | Modifiers                | Generics | Type                  | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|-----------------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`public`**             |          | **[`BoundaryOrder`]** | **`boundaryOrder`**()    |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`boolean`**         | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`int`**             | **`getPageCount`**()     |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**             | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`List`]**          | **`maxValues`**()        |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`List`]**          | **`minValues`**()        |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`List<Long>`]**    | **`nullCounts`**()       |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`List<Boolean>`]** | **`nullPages`**()        |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]**        | **`toString`**()         |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.metadata.columnindex$boundaryorder"></a>
### `dev.hardwood.metadata.ColumnIndex$BoundaryOrder`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type     | Name                | Extends         | JDK        | Serialization | Compatibility Changes |
|--------|---------------------------------------|----------|---------------------|-----------------|------------|---------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Enum** | **`BoundaryOrder`** | **[`Enum<E>`]** | **JDK 21** | ![Compatible] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface             | Compatibility Changes |
|--------|-----------------------|-----------------------|
| Added  | **[`Serializable`]**  | ![No changes]         |
| Added  | **[`Comparable<T>`]** | ![No changes]         |
| Added  | **[`Constable`]**     | ![No changes]         |


#### Methods

| Status | Modifiers                 | Generics | Type                       | Method                    | Annotations | Throws | Compatibility Changes |
|--------|---------------------------|----------|----------------------------|---------------------------|-------------|--------|-----------------------|
| Added  | **`static`** **`public`** |          | **[`BoundaryOrder`]**      | **`valueOf`**([`String`]) |             |        | ![Method added to public class] |
| Added  | **`static`** **`public`** |          | **[`BoundaryOrder[]`][1]** | **`values`**()            |             |        | ![Method added to public class] |


#### Fields

| Status | Modifiers                             | Type                  | Name         | Annotations | Compatibility Changes |
|--------|---------------------------------------|-----------------------|--------------|-------------|-----------------------|
| Added  | **`public`** **`static`** **`final`** | **[`BoundaryOrder`]** | `ASCENDING`  |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`BoundaryOrder`]** | `DESCENDING` |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`BoundaryOrder`]** | `UNORDERED`  |             | ![No changes]         |

___

<a id="user-content-dev.hardwood.metadata.columnmetadata"></a>
### `dev.hardwood.metadata.ColumnMetaData`

- [ ] Binary-compatible
- [ ] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers        | Type  | Name             | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|------------------|-------|------------------|------------|--------|---------------------|-----------------------|
| Modified | `final` `public` | Class | `ColumnMetaData` | [`Record`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Constructors

| Status  | Modifiers    | Generics | Constructor | Annotations | Throws | Compatibility Changes |
|---------|--------------|----------|-------------|-------------|--------|-----------------------|
| Removed | ~~`public`~~ |          | ~~`ColumnMetaData`~~([`PhysicalType`], [`List<Encoding>`], [`List<String>`], [`CompressionCodec`], `long`, `long`, `long`, `long`, [`Long`]) |  |  | ![Constructor removed] |
| Added   | **`public`** |          | **`ColumnMetaData`**([`PhysicalType`], [`List<Encoding>`], [`FieldPath`], [`CompressionCodec`], `long`, `long`, `long`, [`Map<String, String>`], `long`, [`Long`], [`Statistics`]) |  |  | ![No changes] |


#### Methods

| Status   | Modifiers    | Generics | Type                                          | Method                   | Annotations | Throws | Compatibility Changes |
|----------|--------------|----------|-----------------------------------------------|--------------------------|-------------|--------|-----------------------|
| Added    | **`public`** |          | **[`Map<String, String>`]**                   | **`keyValueMetadata`**() |             |        | ![Method added to public class] |
| Modified | `public`     |          | ~~[`List<String>`]~~ &rarr; **[`FieldPath`]** | `pathInSchema`()         |             |        | ![Method return type changed] ![Method return type generics changed] |
| Added    | **`public`** |          | **[`Statistics`]**                            | **`statistics`**()       |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.metadata.fieldpath"></a>
### `dev.hardwood.metadata.FieldPath`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                | Type      | Name            | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|--------------------------|-----------|-----------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`public`** | **Class** | **`FieldPath`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor                       | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-----------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`FieldPath`**([`List<String>`]) |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                 | Generics | Type                 | Method                              | Annotations | Throws | Compatibility Changes |
|--------|---------------------------|----------|----------------------|-------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`**              |          | **[`List<String>`]** | **`elements`**()                    |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`**  |          | **`boolean`**        | **`equals`**([`Object`])            |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`**  |          | **`int`**            | **`hashCode`**()                    |             |        | ![Method added to public class] |
| Added  | **`public`**              |          | **`boolean`**        | **`isEmpty`**()                     |             |        | ![Method added to public class] |
| Added  | **`public`**              |          | **[`String`]**       | **`leafName`**()                    |             |        | ![Method added to public class] |
| Added  | **`public`**              |          | **`boolean`**        | **`matchesDottedName`**([`String`]) |             |        | ![Method added to public class] |
| Added  | **`static`** **`public`** |          | **[`FieldPath`]**    | **`of`**([`String...`])             |             |        | ![Method added to public class] |
| Added  | **`public`**              |          | **[`String`]**       | **`toString`**()                    |             |        | ![Method added to public class] |
| Added  | **`public`**              |          | **[`String`]**       | **`topLevelName`**()                |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.metadata.filemetadata"></a>
### `dev.hardwood.metadata.FileMetaData`

- [ ] Binary-compatible
- [ ] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers        | Type  | Name           | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|------------------|-------|----------------|------------|--------|---------------------|-----------------------|
| Modified | `final` `public` | Class | `FileMetaData` | [`Record`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Constructors

| Status  | Modifiers    | Generics | Constructor | Annotations | Throws | Compatibility Changes |
|---------|--------------|----------|-------------|-------------|--------|-----------------------|
| Removed | ~~`public`~~ |          | ~~`FileMetaData`~~(`int`, [`List<SchemaElement>`], `long`, [`List<RowGroup>`], [`String`]) |  |  | ![Constructor removed] |
| Added   | **`public`** |          | **`FileMetaData`**(`int`, [`List<SchemaElement>`], `long`, [`List<RowGroup>`], [`Map<String, String>`], [`String`]) |  |  | ![No changes] |


#### Methods

| Status | Modifiers    | Generics | Type                        | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-----------------------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **[`Map<String, String>`]** | **`keyValueMetadata`**() |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.metadata.offsetindex"></a>
### `dev.hardwood.metadata.OffsetIndex`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                | Type      | Name              | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|--------------------------|-----------|-------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`public`** | **Class** | **`OffsetIndex`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor                               | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-------------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`OffsetIndex`**([`List<PageLocation>`]) |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type                       | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|----------------------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`final`** **`public`** |          | **`boolean`**              | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**                  | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`List<PageLocation>`]** | **`pageLocations`**()    |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]**             | **`toString`**()         |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.metadata.pagelocation"></a>
### `dev.hardwood.metadata.PageLocation`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                | Type      | Name               | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|--------------------------|-----------|--------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`public`** | **Class** | **`PageLocation`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor                               | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-------------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`PageLocation`**(`long`, `int`, `long`) |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type           | Method                     | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|----------------|----------------------------|-------------|--------|-----------------------|
| Added  | **`public`**             |          | **`int`**      | **`compressedPageSize`**() |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`boolean`**  | **`equals`**([`Object`])   |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`long`**     | **`firstRowIndex`**()      |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**      | **`hashCode`**()           |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`long`**     | **`offset`**()             |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]** | **`toString`**()           |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.metadata.statistics"></a>
### `dev.hardwood.metadata.Statistics`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                | Type      | Name             | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|--------------------------|-----------|------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`public`** | **Class** | **`Statistics`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`Statistics`**(`byte[]`, `byte[]`, [`Long`], [`Long`], `boolean`) |  |  | ![No changes] |


#### Methods

| Status | Modifiers                | Generics | Type           | Method                     | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|----------------|----------------------------|-------------|--------|-----------------------|
| Added  | **`public`**             |          | **[`Long`]**   | **`distinctCount`**()      |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`boolean`**  | **`equals`**([`Object`])   |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**      | **`hashCode`**()           |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`boolean`**  | **`isMinMaxDeprecated`**() |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`byte[]`**   | **`maxValue`**()           |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`byte[]`**   | **`minValue`**()           |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`Long`]**   | **`nullCount`**()          |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]** | **`toString`**()           |             |        | ![Method added to public class] |

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

<a id="user-content-dev.hardwood.reader.filterpredicate"></a>
### `dev.hardwood.reader.FilterPredicate`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                   | Type          | Name                  | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|-----------------------------|---------------|-----------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`public`** **`abstract`** | **Interface** | **`FilterPredicate`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers                 | Generics | Type                    | Method                                              | Annotations | Throws | Compatibility Changes |
|--------|---------------------------|----------|-------------------------|-----------------------------------------------------|-------------|--------|-----------------------|
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`and`**([`FilterPredicate`], [`FilterPredicate`]) |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`and`**([`FilterPredicate...`])                   |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`eq`**([`String`], `int`)                         |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`eq`**([`String`], `long`)                        |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`eq`**([`String`], `float`)                       |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`eq`**([`String`], `double`)                      |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`eq`**([`String`], `boolean`)                     |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`eq`**([`String`], [`String`])                    |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`eq`**([`String`], [`LocalDate`])                 |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`eq`**([`String`], [`Instant`])                   |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`eq`**([`String`], [`LocalTime`])                 |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`eq`**([`String`], [`BigDecimal`])                |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`eq`**([`String`], [`UUID`])                      |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`gt`**([`String`], `int`)                         |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`gt`**([`String`], `long`)                        |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`gt`**([`String`], `float`)                       |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`gt`**([`String`], `double`)                      |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`gt`**([`String`], [`String`])                    |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`gt`**([`String`], [`LocalDate`])                 |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`gt`**([`String`], [`Instant`])                   |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`gt`**([`String`], [`LocalTime`])                 |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`gt`**([`String`], [`BigDecimal`])                |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`gt`**([`String`], [`UUID`])                      |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`gtEq`**([`String`], `int`)                       |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`gtEq`**([`String`], `long`)                      |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`gtEq`**([`String`], `float`)                     |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`gtEq`**([`String`], `double`)                    |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`gtEq`**([`String`], [`String`])                  |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`gtEq`**([`String`], [`LocalDate`])               |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`gtEq`**([`String`], [`Instant`])                 |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`gtEq`**([`String`], [`LocalTime`])               |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`gtEq`**([`String`], [`BigDecimal`])              |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`gtEq`**([`String`], [`UUID`])                    |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`in`**([`String`], `int...`)                      |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`in`**([`String`], `long...`)                     |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`inStrings`**([`String`], [`String...`])          |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`isNotNull`**([`String`])                         |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`isNull`**([`String`])                            |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`lt`**([`String`], `int`)                         |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`lt`**([`String`], `long`)                        |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`lt`**([`String`], `float`)                       |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`lt`**([`String`], `double`)                      |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`lt`**([`String`], [`String`])                    |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`lt`**([`String`], [`LocalDate`])                 |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`lt`**([`String`], [`Instant`])                   |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`lt`**([`String`], [`LocalTime`])                 |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`lt`**([`String`], [`BigDecimal`])                |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`lt`**([`String`], [`UUID`])                      |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`ltEq`**([`String`], `int`)                       |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`ltEq`**([`String`], `long`)                      |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`ltEq`**([`String`], `float`)                     |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`ltEq`**([`String`], `double`)                    |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`ltEq`**([`String`], [`String`])                  |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`ltEq`**([`String`], [`LocalDate`])               |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`ltEq`**([`String`], [`Instant`])                 |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`ltEq`**([`String`], [`LocalTime`])               |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`ltEq`**([`String`], [`BigDecimal`])              |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`ltEq`**([`String`], [`UUID`])                    |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`not`**([`FilterPredicate`])                      |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`notEq`**([`String`], `int`)                      |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`notEq`**([`String`], `long`)                     |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`notEq`**([`String`], `float`)                    |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`notEq`**([`String`], `double`)                   |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`notEq`**([`String`], `boolean`)                  |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`notEq`**([`String`], [`String`])                 |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`notEq`**([`String`], [`LocalDate`])              |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`notEq`**([`String`], [`Instant`])                |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`notEq`**([`String`], [`LocalTime`])              |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`notEq`**([`String`], [`BigDecimal`])             |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`notEq`**([`String`], [`UUID`])                   |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`or`**([`FilterPredicate`], [`FilterPredicate`])  |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`or`**([`FilterPredicate...`])                    |             |        | ![No changes]         |

___

<a id="user-content-dev.hardwood.reader.filterpredicate$and"></a>
### `dev.hardwood.reader.FilterPredicate$And`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name      | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|-----------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`And`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface               | Compatibility Changes |
|--------|-------------------------|-----------------------|
| Added  | **[`FilterPredicate`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor                          | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|--------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`And`**([`List<FilterPredicate>`]) |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type                          | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|-------------------------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`final`** **`public`** |          | **`boolean`**                 | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`List<FilterPredicate>`]** | **`filters`**()          |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**                     | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]**                | **`toString`**()         |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.reader.filterpredicate$binarycolumnpredicate"></a>
### `dev.hardwood.reader.FilterPredicate$BinaryColumnPredicate`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name                        | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|-----------------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`BinaryColumnPredicate`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface               | Compatibility Changes |
|--------|-------------------------|-----------------------|
| Added  | **[`FilterPredicate`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor                                                     | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-----------------------------------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`BinaryColumnPredicate`**([`String`], [`Operator`], `byte[]`) |             |        | ![No changes]         |


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

<a id="user-content-dev.hardwood.reader.filterpredicate$binaryinpredicate"></a>
### `dev.hardwood.reader.FilterPredicate$BinaryInPredicate`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name                    | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|-------------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`BinaryInPredicate`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface               | Compatibility Changes |
|--------|-------------------------|-----------------------|
| Added  | **[`FilterPredicate`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor                                     | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-------------------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`BinaryInPredicate`**([`String`], `byte[][]`) |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type           | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|----------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`public`**             |          | **[`String`]** | **`column`**()           |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`boolean`**  | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`int`**      | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]** | **`toString`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`byte[][]`** | **`values`**()           |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.reader.filterpredicate$booleancolumnpredicate"></a>
### `dev.hardwood.reader.FilterPredicate$BooleanColumnPredicate`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name                         | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|------------------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`BooleanColumnPredicate`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface               | Compatibility Changes |
|--------|-------------------------|-----------------------|
| Added  | **[`FilterPredicate`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`BooleanColumnPredicate`**([`String`], [`Operator`], `boolean`) |  |  | ![No changes] |


#### Methods

| Status | Modifiers                | Generics | Type             | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|------------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`public`**             |          | **[`String`]**   | **`column`**()           |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`boolean`**    | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**        | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`Operator`]** | **`op`**()               |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]**   | **`toString`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`boolean`**    | **`value`**()            |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.reader.filterpredicate$datecolumnpredicate"></a>
### `dev.hardwood.reader.FilterPredicate$DateColumnPredicate`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name                      | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|---------------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`DateColumnPredicate`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface               | Compatibility Changes |
|--------|-------------------------|-----------------------|
| Added  | **[`FilterPredicate`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`DateColumnPredicate`**([`String`], [`Operator`], [`LocalDate`]) |  |  | ![No changes] |


#### Methods

| Status | Modifiers                | Generics | Type              | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|-------------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`public`**             |          | **[`String`]**    | **`column`**()           |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`boolean`**     | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**         | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`Operator`]**  | **`op`**()               |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]**    | **`toString`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`LocalDate`]** | **`value`**()            |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.reader.filterpredicate$decimalcolumnpredicate"></a>
### `dev.hardwood.reader.FilterPredicate$DecimalColumnPredicate`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name                         | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|------------------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`DecimalColumnPredicate`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface               | Compatibility Changes |
|--------|-------------------------|-----------------------|
| Added  | **[`FilterPredicate`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`DecimalColumnPredicate`**([`String`], [`Operator`], [`BigDecimal`]) |  |  | ![No changes] |


#### Methods

| Status | Modifiers                | Generics | Type               | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|--------------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`public`**             |          | **[`String`]**     | **`column`**()           |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`boolean`**      | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**          | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`Operator`]**   | **`op`**()               |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]**     | **`toString`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`BigDecimal`]** | **`value`**()            |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.reader.filterpredicate$doublecolumnpredicate"></a>
### `dev.hardwood.reader.FilterPredicate$DoubleColumnPredicate`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name                        | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|-----------------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`DoubleColumnPredicate`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface               | Compatibility Changes |
|--------|-------------------------|-----------------------|
| Added  | **[`FilterPredicate`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor                                                     | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-----------------------------------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`DoubleColumnPredicate`**([`String`], [`Operator`], `double`) |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type             | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|------------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`public`**             |          | **[`String`]**   | **`column`**()           |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`boolean`**    | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**        | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`Operator`]** | **`op`**()               |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]**   | **`toString`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`double`**     | **`value`**()            |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.reader.filterpredicate$floatcolumnpredicate"></a>
### `dev.hardwood.reader.FilterPredicate$FloatColumnPredicate`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name                       | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|----------------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`FloatColumnPredicate`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface               | Compatibility Changes |
|--------|-------------------------|-----------------------|
| Added  | **[`FilterPredicate`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor                                                   | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|---------------------------------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`FloatColumnPredicate`**([`String`], [`Operator`], `float`) |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type             | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|------------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`public`**             |          | **[`String`]**   | **`column`**()           |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`boolean`**    | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**        | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`Operator`]** | **`op`**()               |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]**   | **`toString`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`float`**      | **`value`**()            |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.reader.filterpredicate$instantcolumnpredicate"></a>
### `dev.hardwood.reader.FilterPredicate$InstantColumnPredicate`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name                         | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|------------------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`InstantColumnPredicate`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface               | Compatibility Changes |
|--------|-------------------------|-----------------------|
| Added  | **[`FilterPredicate`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`InstantColumnPredicate`**([`String`], [`Operator`], [`Instant`]) |  |  | ![No changes] |


#### Methods

| Status | Modifiers                | Generics | Type             | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|------------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`public`**             |          | **[`String`]**   | **`column`**()           |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`boolean`**    | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**        | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`Operator`]** | **`op`**()               |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]**   | **`toString`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`Instant`]**  | **`value`**()            |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.reader.filterpredicate$intcolumnpredicate"></a>
### `dev.hardwood.reader.FilterPredicate$IntColumnPredicate`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name                     | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|--------------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`IntColumnPredicate`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface               | Compatibility Changes |
|--------|-------------------------|-----------------------|
| Added  | **[`FilterPredicate`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor                                               | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-----------------------------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`IntColumnPredicate`**([`String`], [`Operator`], `int`) |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type             | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|------------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`public`**             |          | **[`String`]**   | **`column`**()           |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`boolean`**    | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**        | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`Operator`]** | **`op`**()               |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]**   | **`toString`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`int`**        | **`value`**()            |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.reader.filterpredicate$intinpredicate"></a>
### `dev.hardwood.reader.FilterPredicate$IntInPredicate`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name                 | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|----------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`IntInPredicate`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface               | Compatibility Changes |
|--------|-------------------------|-----------------------|
| Added  | **[`FilterPredicate`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor                               | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-------------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`IntInPredicate`**([`String`], `int[]`) |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type           | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|----------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`public`**             |          | **[`String`]** | **`column`**()           |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`boolean`**  | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`int`**      | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]** | **`toString`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`int[]`**    | **`values`**()           |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.reader.filterpredicate$isnotnullpredicate"></a>
### `dev.hardwood.reader.FilterPredicate$IsNotNullPredicate`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name                     | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|--------------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`IsNotNullPredicate`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface               | Compatibility Changes |
|--------|-------------------------|-----------------------|
| Added  | **[`FilterPredicate`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor                          | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|--------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`IsNotNullPredicate`**([`String`]) |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type           | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|----------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`public`**             |          | **[`String`]** | **`column`**()           |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`boolean`**  | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**      | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]** | **`toString`**()         |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.reader.filterpredicate$isnullpredicate"></a>
### `dev.hardwood.reader.FilterPredicate$IsNullPredicate`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name                  | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|-----------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`IsNullPredicate`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface               | Compatibility Changes |
|--------|-------------------------|-----------------------|
| Added  | **[`FilterPredicate`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor                       | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-----------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`IsNullPredicate`**([`String`]) |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type           | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|----------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`public`**             |          | **[`String`]** | **`column`**()           |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`boolean`**  | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**      | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]** | **`toString`**()         |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.reader.filterpredicate$longcolumnpredicate"></a>
### `dev.hardwood.reader.FilterPredicate$LongColumnPredicate`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name                      | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|---------------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`LongColumnPredicate`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface               | Compatibility Changes |
|--------|-------------------------|-----------------------|
| Added  | **[`FilterPredicate`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor                                                 | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-------------------------------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`LongColumnPredicate`**([`String`], [`Operator`], `long`) |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type             | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|------------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`public`**             |          | **[`String`]**   | **`column`**()           |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`boolean`**    | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**        | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`Operator`]** | **`op`**()               |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]**   | **`toString`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`long`**       | **`value`**()            |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.reader.filterpredicate$longinpredicate"></a>
### `dev.hardwood.reader.FilterPredicate$LongInPredicate`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name                  | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|-----------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`LongInPredicate`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface               | Compatibility Changes |
|--------|-------------------------|-----------------------|
| Added  | **[`FilterPredicate`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor                                 | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|---------------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`LongInPredicate`**([`String`], `long[]`) |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type           | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|----------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`public`**             |          | **[`String`]** | **`column`**()           |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`boolean`**  | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`int`**      | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]** | **`toString`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`long[]`**   | **`values`**()           |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.reader.filterpredicate$not"></a>
### `dev.hardwood.reader.FilterPredicate$Not`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name      | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|-----------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`Not`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface               | Compatibility Changes |
|--------|-------------------------|-----------------------|
| Added  | **[`FilterPredicate`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor                    | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|--------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`Not`**([`FilterPredicate`]) |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type                    | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|-------------------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`public`**             |          | **[`FilterPredicate`]** | **`delegate`**()         |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`boolean`**           | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**               | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]**          | **`toString`**()         |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.reader.filterpredicate$operator"></a>
### `dev.hardwood.reader.FilterPredicate$Operator`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type     | Name           | Extends         | JDK        | Serialization | Compatibility Changes |
|--------|---------------------------------------|----------|----------------|-----------------|------------|---------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Enum** | **`Operator`** | **[`Enum<E>`]** | **JDK 21** | ![Compatible] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface             | Compatibility Changes |
|--------|-----------------------|-----------------------|
| Added  | **[`Serializable`]**  | ![No changes]         |
| Added  | **[`Comparable<T>`]** | ![No changes]         |
| Added  | **[`Constable`]**     | ![No changes]         |


#### Methods

| Status | Modifiers                 | Generics | Type                  | Method                    | Annotations | Throws | Compatibility Changes |
|--------|---------------------------|----------|-----------------------|---------------------------|-------------|--------|-----------------------|
| Added  | **`public`**              |          | **[`Operator`]**      | **`invert`**()            |             |        | ![Method added to public class] |
| Added  | **`static`** **`public`** |          | **[`Operator`]**      | **`valueOf`**([`String`]) |             |        | ![Method added to public class] |
| Added  | **`static`** **`public`** |          | **[`Operator[]`][2]** | **`values`**()            |             |        | ![Method added to public class] |


#### Fields

| Status | Modifiers                             | Type             | Name     | Annotations | Compatibility Changes |
|--------|---------------------------------------|------------------|----------|-------------|-----------------------|
| Added  | **`public`** **`static`** **`final`** | **[`Operator`]** | `EQ`     |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`Operator`]** | `GT`     |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`Operator`]** | `GT_EQ`  |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`Operator`]** | `LT`     |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`Operator`]** | `LT_EQ`  |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`Operator`]** | `NOT_EQ` |             | ![No changes]         |

___

<a id="user-content-dev.hardwood.reader.filterpredicate$or"></a>
### `dev.hardwood.reader.FilterPredicate$Or`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name     | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|----------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`Or`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface               | Compatibility Changes |
|--------|-------------------------|-----------------------|
| Added  | **[`FilterPredicate`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor                         | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`Or`**([`List<FilterPredicate>`]) |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type                          | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|-------------------------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`final`** **`public`** |          | **`boolean`**                 | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`List<FilterPredicate>`]** | **`filters`**()          |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**                     | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]**                | **`toString`**()         |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.reader.filterpredicate$signedbinarycolumnpredicate"></a>
### `dev.hardwood.reader.FilterPredicate$SignedBinaryColumnPredicate`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name                              | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|-----------------------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`SignedBinaryColumnPredicate`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface               | Compatibility Changes |
|--------|-------------------------|-----------------------|
| Added  | **[`FilterPredicate`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`SignedBinaryColumnPredicate`**([`String`], [`Operator`], `byte[]`) |  |  | ![No changes] |


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

<a id="user-content-dev.hardwood.reader.filterpredicate$timecolumnpredicate"></a>
### `dev.hardwood.reader.FilterPredicate$TimeColumnPredicate`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name                      | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|---------------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`TimeColumnPredicate`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface               | Compatibility Changes |
|--------|-------------------------|-----------------------|
| Added  | **[`FilterPredicate`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`TimeColumnPredicate`**([`String`], [`Operator`], [`LocalTime`]) |  |  | ![No changes] |


#### Methods

| Status | Modifiers                | Generics | Type              | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|-------------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`public`**             |          | **[`String`]**    | **`column`**()           |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`boolean`**     | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**         | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`Operator`]**  | **`op`**()               |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]**    | **`toString`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`LocalTime`]** | **`value`**()            |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.reader.multifileparquetreader"></a>
### `dev.hardwood.reader.MultiFileParquetReader`

- [X] Binary-compatible
- [ ] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers | Type  | Name                     | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|-----------|-------|--------------------------|------------|--------|---------------------|-----------------------|
| Modified | `public`  | Class | `MultiFileParquetReader` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Constructors

| Status              | Modifiers | Generics | Constructor | Annotations | Throws          | Compatibility Changes |
|---------------------|-----------|----------|-------------|-------------|-----------------|-----------------------|
| Source-incompatible | `public`  |          | `MultiFileParquetReader`(~~[`List<Path>`]~~ &rarr; **[`List<InputFile>`]**, [`HardwoodContextImpl`]) |  | [`IOException`] | ![Method parameter generics changed] |


#### Methods

| Status | Modifiers    | Generics | Type                           | Method                                                           | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|--------------------------------|------------------------------------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **[`MultiFileColumnReaders`]** | **`createColumnReaders`**([`ColumnProjection`], [`FilterPredicate`]) |         |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`MultiFileRowReader`]**     | **`createRowReader`**([`FilterPredicate`])                       |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`MultiFileRowReader`]**     | **`createRowReader`**([`ColumnProjection`], [`FilterPredicate`]) |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.reader.multifilerowreader"></a>
### `dev.hardwood.reader.MultiFileRowReader`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers | Type  | Name                 | Extends               | JDK    | Serialization       | Compatibility Changes |
|----------|-----------|-------|----------------------|-----------------------|--------|---------------------|-----------------------|
| Modified | `public`  | Class | `MultiFileRowReader` | [`AbstractRowReader`] | JDK 21 | ![Not serializable] | ![No changes]         |

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

| Status  | Modifiers                 | Generics | Type                      | Method                                                           | Annotations | Throws              | Compatibility Changes |
|---------|---------------------------|----------|---------------------------|------------------------------------------------------------------|-------------|---------------------|-----------------------|
| Added   | **`public`**              |          | **[`ColumnReader`]**      | **`createColumnReader`**([`String`], [`FilterPredicate`])        |             |                     | ![Method added to public class] |
| Added   | **`public`**              |          | **[`ColumnReader`]**      | **`createColumnReader`**(`int`, [`FilterPredicate`])             |             |                     | ![Method added to public class] |
| Added   | **`public`**              |          | **[`RowReader`]**         | **`createRowReader`**([`FilterPredicate`])                       |             |                     | ![Method added to public class] |
| Added   | **`public`**              |          | **[`RowReader`]**         | **`createRowReader`**([`ColumnProjection`], [`FilterPredicate`]) |             |                     | ![Method added to public class] |
| Added   | **`public`**              |          | **[`RowReader`]**         | **`createRowReader`**(`long`)                                    |             |                     | ![Method added to public class] |
| Added   | **`public`**              |          | **[`RowReader`]**         | **`createRowReader`**([`ColumnProjection`], `long`)              |             |                     | ![Method added to public class] |
| Added   | **`public`**              |          | **[`RowReader`]**         | **`createRowReader`**([`FilterPredicate`], `long`)               |             |                     | ![Method added to public class] |
| Added   | **`public`**              |          | **[`RowReader`]**         | **`createRowReader`**([`ColumnProjection`], [`FilterPredicate`], `long`) |     |                     | ![Method added to public class] |
| Removed | ~~`static`~~ ~~`public`~~ |          | ~~[`ParquetFileReader`]~~ | ~~`open`~~([`Path`])                                             |             | ~~[`IOException`]~~ | ![Method removed]     |
| Removed | ~~`static`~~ ~~`public`~~ |          | ~~[`ParquetFileReader`]~~ | ~~`open`~~([`Path`], [`HardwoodContext`])                        |             | ~~[`IOException`]~~ | ![Method removed]     |
| Added   | **`static`** **`public`** |          | **[`ParquetFileReader`]** | **`open`**([`InputFile`])                                        |             | **[`IOException`]** | ![Method added to public class] |
| Added   | **`static`** **`public`** |          | **[`ParquetFileReader`]** | **`open`**([`InputFile`], [`HardwoodContext`])                   |             | **[`IOException`]** | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.reader.rowreader"></a>
### `dev.hardwood.reader.RowReader`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers           | Type      | Name        | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|---------------------|-----------|-------------|------------|--------|---------------------|-----------------------|
| Modified | `public` `abstract` | Interface | `RowReader` | [`Object`] | JDK 21 | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface              | Compatibility Changes |
|--------|------------------------|-----------------------|
| Added  | **[`StructAccessor`]** | ![No changes]         |


#### Methods

| Status  | Modifiers                   | Generics | Type                 | Method                             | Annotations | Throws | Compatibility Changes |
|---------|-----------------------------|----------|----------------------|------------------------------------|-------------|--------|-----------------------|
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~`byte[]`~~         | ~~`getBinary`~~([`String`])        |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~`boolean`~~        | ~~`getBoolean`~~([`String`])       |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`LocalDate`]~~    | ~~`getDate`~~([`String`])          |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`BigDecimal`]~~   | ~~`getDecimal`~~([`String`])       |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~`double`~~         | ~~`getDouble`~~([`String`])        |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~`int`~~            | ~~`getFieldCount`~~()              |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`String`]~~       | ~~`getFieldName`~~(`int`)          |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~`float`~~          | ~~`getFloat`~~([`String`])         |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~`int`~~            | ~~`getInt`~~([`String`])           |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`PqList`]~~       | ~~`getList`~~([`String`])          |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`PqDoubleList`]~~ | ~~`getListOfDoubles`~~([`String`]) |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`PqIntList`]~~    | ~~`getListOfInts`~~([`String`])    |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`PqLongList`]~~   | ~~`getListOfLongs`~~([`String`])   |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~`long`~~           | ~~`getLong`~~([`String`])          |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`PqMap`]~~        | ~~`getMap`~~([`String`])           |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`String`]~~       | ~~`getString`~~([`String`])        |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`PqStruct`]~~     | ~~`getStruct`~~([`String`])        |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`LocalTime`]~~    | ~~`getTime`~~([`String`])          |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`Instant`]~~      | ~~`getTimestamp`~~([`String`])     |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`UUID`]~~         | ~~`getUuid`~~([`String`])          |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`Object`]~~       | ~~`getValue`~~([`String`])         |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~`boolean`~~        | ~~`isNull`~~([`String`])           |             |        | ![No changes]         |

___

<a id="user-content-dev.hardwood.row.pqstruct"></a>
### `dev.hardwood.row.PqStruct`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers           | Type      | Name       | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|---------------------|-----------|------------|------------|--------|---------------------|-----------------------|
| Modified | `public` `abstract` | Interface | `PqStruct` | [`Object`] | JDK 21 | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface              | Compatibility Changes |
|--------|------------------------|-----------------------|
| Added  | **[`StructAccessor`]** | ![No changes]         |


#### Methods

| Status  | Modifiers                   | Generics | Type                 | Method                             | Annotations | Throws | Compatibility Changes |
|---------|-----------------------------|----------|----------------------|------------------------------------|-------------|--------|-----------------------|
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~`byte[]`~~         | ~~`getBinary`~~([`String`])        |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~`boolean`~~        | ~~`getBoolean`~~([`String`])       |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`LocalDate`]~~    | ~~`getDate`~~([`String`])          |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`BigDecimal`]~~   | ~~`getDecimal`~~([`String`])       |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~`double`~~         | ~~`getDouble`~~([`String`])        |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~`int`~~            | ~~`getFieldCount`~~()              |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`String`]~~       | ~~`getFieldName`~~(`int`)          |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~`float`~~          | ~~`getFloat`~~([`String`])         |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~`int`~~            | ~~`getInt`~~([`String`])           |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`PqList`]~~       | ~~`getList`~~([`String`])          |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`PqDoubleList`]~~ | ~~`getListOfDoubles`~~([`String`]) |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`PqIntList`]~~    | ~~`getListOfInts`~~([`String`])    |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`PqLongList`]~~   | ~~`getListOfLongs`~~([`String`])   |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~`long`~~           | ~~`getLong`~~([`String`])          |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`PqMap`]~~        | ~~`getMap`~~([`String`])           |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`String`]~~       | ~~`getString`~~([`String`])        |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`PqStruct`]~~     | ~~`getStruct`~~([`String`])        |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`LocalTime`]~~    | ~~`getTime`~~([`String`])          |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`Instant`]~~      | ~~`getTimestamp`~~([`String`])     |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`UUID`]~~         | ~~`getUuid`~~([`String`])          |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`Object`]~~       | ~~`getValue`~~([`String`])         |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~`boolean`~~        | ~~`isNull`~~([`String`])           |             |        | ![No changes]         |

___

<a id="user-content-dev.hardwood.row.structaccessor"></a>
### `dev.hardwood.row.StructAccessor`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                   | Type          | Name                 | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|-----------------------------|---------------|----------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`public`** **`abstract`** | **Interface** | **`StructAccessor`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers                   | Generics | Type                 | Method                             | Annotations | Throws | Compatibility Changes |
|--------|-----------------------------|----------|----------------------|------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** **`abstract`** |          | **`byte[]`**         | **`getBinary`**([`String`])        |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`boolean`**        | **`getBoolean`**([`String`])       |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`LocalDate`]**    | **`getDate`**([`String`])          |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`BigDecimal`]**   | **`getDecimal`**([`String`])       |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`double`**         | **`getDouble`**([`String`])        |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`int`**            | **`getFieldCount`**()              |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`String`]**       | **`getFieldName`**(`int`)          |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`float`**          | **`getFloat`**([`String`])         |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`int`**            | **`getInt`**([`String`])           |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`PqList`]**       | **`getList`**([`String`])          |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`PqDoubleList`]** | **`getListOfDoubles`**([`String`]) |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`PqIntList`]**    | **`getListOfInts`**([`String`])    |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`PqLongList`]**   | **`getListOfLongs`**([`String`])   |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`long`**           | **`getLong`**([`String`])          |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`PqMap`]**        | **`getMap`**([`String`])           |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`String`]**       | **`getString`**([`String`])        |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`PqStruct`]**     | **`getStruct`**([`String`])        |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`LocalTime`]**    | **`getTime`**([`String`])          |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`Instant`]**      | **`getTimestamp`**([`String`])     |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`UUID`]**         | **`getUuid`**([`String`])          |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`Object`]**       | **`getValue`**([`String`])         |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`boolean`**        | **`isNull`**([`String`])           |             |        | ![No changes]         |

___

<a id="user-content-dev.hardwood.schema.columnschema"></a>
### `dev.hardwood.schema.ColumnSchema`

- [ ] Binary-compatible
- [ ] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers        | Type  | Name           | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|------------------|-------|----------------|------------|--------|---------------------|-----------------------|
| Modified | `final` `public` | Class | `ColumnSchema` | [`Record`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Constructors

| Status  | Modifiers    | Generics | Constructor | Annotations | Throws | Compatibility Changes |
|---------|--------------|----------|-------------|-------------|--------|-----------------------|
| Removed | ~~`public`~~ |          | ~~`ColumnSchema`~~([`String`], [`PhysicalType`], [`RepetitionType`], [`Integer`], `int`, `int`, `int`, [`LogicalType`]) |  |  | ![Constructor removed] |
| Added   | **`public`** |          | **`ColumnSchema`**([`FieldPath`], [`PhysicalType`], [`RepetitionType`], [`Integer`], `int`, `int`, `int`, [`LogicalType`]) |  |  | ![No changes] |


#### Methods

| Status | Modifiers    | Generics | Type              | Method            | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-------------------|-------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **[`FieldPath`]** | **`fieldPath`**() |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.schema.fileschema"></a>
### `dev.hardwood.schema.FileSchema`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers | Type  | Name         | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|-----------|-------|--------------|------------|--------|---------------------|-----------------------|
| Modified | `public`  | Class | `FileSchema` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers    | Generics | Type                 | Method                         | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|----------------------|--------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **[`ColumnSchema`]** | **`getColumn`**([`FieldPath`]) |             |        | ![Method added to public class] |


</details>


___

*Generated on: 2026-06-05 09:26:53.415+0000*.

[1]: # "dev.hardwood.metadata.ColumnIndex$BoundaryOrder[]"
[2]: # "dev.hardwood.reader.FilterPredicate$Operator[]"
[Annotation added]: https://img.shields.io/badge/Annotation_added-yellow "Annotation added"
[Compatible]: https://img.shields.io/badge/Compatible-green "Compatible"
[Constructor removed]: https://img.shields.io/badge/Constructor_removed-red "Constructor removed"
[Interface added]: https://img.shields.io/badge/Interface_added-orange "Interface added"
[Method added to public class]: https://img.shields.io/badge/Method_added_to_public_class-yellow "Method added to public class"
[Method parameter generics changed]: https://img.shields.io/badge/Method_parameter_generics_changed-orange "Method parameter generics changed"
[Method removed]: https://img.shields.io/badge/Method_removed-red "Method removed"
[Method return type changed]: https://img.shields.io/badge/Method_return_type_changed-red "Method return type changed"
[Method return type generics changed]: https://img.shields.io/badge/Method_return_type_generics_changed-orange "Method return type generics changed"
[No changes]: https://img.shields.io/badge/No_changes-green "No changes"
[Not serializable]: https://img.shields.io/badge/Not_serializable-green "Not serializable"
[`AbstractRowReader`]: # "dev.hardwood.reader.AbstractRowReader"
[`AutoCloseable`]: # "java.lang.AutoCloseable"
[`BigDecimal`]: # "java.math.BigDecimal"
[`BoundaryOrder`]: # "dev.hardwood.metadata.ColumnIndex$BoundaryOrder"
[`ByteBuffer...`]: # "java.nio.ByteBuffer..."
[`ByteBuffer`]: # "java.nio.ByteBuffer"
[`Category`]: # "jdk.jfr.Category"
[`Closeable`]: # "java.io.Closeable"
[`ColumnMetaData`]: # "dev.hardwood.metadata.ColumnMetaData"
[`ColumnProjection`]: # "dev.hardwood.schema.ColumnProjection"
[`ColumnReader`]: # "dev.hardwood.reader.ColumnReader"
[`ColumnSchema`]: # "dev.hardwood.schema.ColumnSchema"
[`Comparable<T>`]: # "java.lang.Comparable<T extends java.lang.Object>"
[`CompressionCodec`]: # "dev.hardwood.metadata.CompressionCodec"
[`Constable`]: # "java.lang.constant.Constable"
[`DataAmount`]: # "jdk.jfr.DataAmount"
[`Description`]: # "jdk.jfr.Description"
[`Enum<E>`]: # "java.lang.Enum<E extends java.lang.Enum<E>>"
[`Event`]: # "jdk.jfr.Event"
[`FieldPath`]: # "dev.hardwood.metadata.FieldPath"
[`FilterPredicate...`]: # "dev.hardwood.reader.FilterPredicate..."
[`FilterPredicate`]: # "dev.hardwood.reader.FilterPredicate"
[`HardwoodContextImpl`]: # "dev.hardwood.internal.reader.HardwoodContextImpl"
[`HardwoodContext`]: # "dev.hardwood.HardwoodContext"
[`Hardwood`]: # "dev.hardwood.Hardwood"
[`IOException`]: # "java.io.IOException"
[`InputFile`]: # "dev.hardwood.InputFile"
[`Instant`]: # "java.time.Instant"
[`Integer`]: # "java.lang.Integer"
[`Label`]: # "jdk.jfr.Label"
[`List<Boolean>`]: # "java.util.List<java.lang.Boolean>"
[`List<ByteBuffer>`]: # "java.util.List<java.nio.ByteBuffer>"
[`List<Encoding>`]: # "java.util.List<dev.hardwood.metadata.Encoding>"
[`List<FilterPredicate>`]: # "java.util.List<dev.hardwood.reader.FilterPredicate>"
[`List<InputFile>`]: # "java.util.List<dev.hardwood.InputFile>"
[`List<Long>`]: # "java.util.List<java.lang.Long>"
[`List<PageLocation>`]: # "java.util.List<dev.hardwood.metadata.PageLocation>"
[`List<Path>`]: # "java.util.List<java.nio.file.Path>"
[`List<RowGroup>`]: # "java.util.List<dev.hardwood.metadata.RowGroup>"
[`List<SchemaElement>`]: # "java.util.List<dev.hardwood.metadata.SchemaElement>"
[`List<String>`]: # "java.util.List<java.lang.String>"
[`List`]: # "java.util.List"
[`LocalDate`]: # "java.time.LocalDate"
[`LocalTime`]: # "java.time.LocalTime"
[`LogicalType`]: # "dev.hardwood.metadata.LogicalType"
[`Long`]: # "java.lang.Long"
[`Map<String, String>`]: # "java.util.Map<java.lang.String, java.lang.String>"
[`MultiFileColumnReaders`]: # "dev.hardwood.reader.MultiFileColumnReaders"
[`MultiFileParquetReader`]: # "dev.hardwood.reader.MultiFileParquetReader"
[`MultiFileRowReader`]: # "dev.hardwood.reader.MultiFileRowReader"
[`Name`]: # "jdk.jfr.Name"
[`Object`]: # "java.lang.Object"
[`Operator`]: # "dev.hardwood.reader.FilterPredicate$Operator"
[`ParquetFileReader`]: # "dev.hardwood.reader.ParquetFileReader"
[`Path...`]: # "java.nio.file.Path..."
[`Path`]: # "java.nio.file.Path"
[`PhysicalType`]: # "dev.hardwood.metadata.PhysicalType"
[`PqDoubleList`]: # "dev.hardwood.row.PqDoubleList"
[`PqIntList`]: # "dev.hardwood.row.PqIntList"
[`PqList`]: # "dev.hardwood.row.PqList"
[`PqLongList`]: # "dev.hardwood.row.PqLongList"
[`PqMap`]: # "dev.hardwood.row.PqMap"
[`PqStruct`]: # "dev.hardwood.row.PqStruct"
[`Record`]: # "java.lang.Record"
[`RepetitionType`]: # "dev.hardwood.metadata.RepetitionType"
[`RowReader`]: # "dev.hardwood.reader.RowReader"
[`Serializable`]: # "java.io.Serializable"
[`StackTrace`]: # "jdk.jfr.StackTrace"
[`Statistics`]: # "dev.hardwood.metadata.Statistics"
[`String...`]: # "java.lang.String..."
[`String`]: # "java.lang.String"
[`StructAccessor`]: # "dev.hardwood.row.StructAccessor"
[`UUID`]: # "java.util.UUID"
[dev.hardwood.Hardwood]: #user-content-dev.hardwood.hardwood
[dev.hardwood.InputFile]: #user-content-dev.hardwood.inputfile
[dev.hardwood.jfr.BatchWaitEvent]: #user-content-dev.hardwood.jfr.batchwaitevent
[dev.hardwood.jfr.FileMappingEvent]: #user-content-dev.hardwood.jfr.filemappingevent
[dev.hardwood.jfr.FileOpenedEvent]: #user-content-dev.hardwood.jfr.fileopenedevent
[dev.hardwood.jfr.PageDecodedEvent]: #user-content-dev.hardwood.jfr.pagedecodedevent
[dev.hardwood.jfr.PageFilterEvent]: #user-content-dev.hardwood.jfr.pagefilterevent
[dev.hardwood.jfr.PrefetchMissEvent]: #user-content-dev.hardwood.jfr.prefetchmissevent
[dev.hardwood.jfr.RecordFilterEvent]: #user-content-dev.hardwood.jfr.recordfilterevent
[dev.hardwood.jfr.RowGroupFilterEvent]: #user-content-dev.hardwood.jfr.rowgroupfilterevent
[dev.hardwood.jfr.RowGroupScannedEvent]: #user-content-dev.hardwood.jfr.rowgroupscannedevent
[dev.hardwood.metadata.ColumnChunk]: #user-content-dev.hardwood.metadata.columnchunk
[dev.hardwood.metadata.ColumnIndex]: #user-content-dev.hardwood.metadata.columnindex
[dev.hardwood.metadata.ColumnIndex$BoundaryOrder]: #user-content-dev.hardwood.metadata.columnindex$boundaryorder
[dev.hardwood.metadata.ColumnMetaData]: #user-content-dev.hardwood.metadata.columnmetadata
[dev.hardwood.metadata.FieldPath]: #user-content-dev.hardwood.metadata.fieldpath
[dev.hardwood.metadata.FileMetaData]: #user-content-dev.hardwood.metadata.filemetadata
[dev.hardwood.metadata.OffsetIndex]: #user-content-dev.hardwood.metadata.offsetindex
[dev.hardwood.metadata.PageLocation]: #user-content-dev.hardwood.metadata.pagelocation
[dev.hardwood.metadata.Statistics]: #user-content-dev.hardwood.metadata.statistics
[dev.hardwood.reader.ColumnReader]: #user-content-dev.hardwood.reader.columnreader
[dev.hardwood.reader.FilterPredicate]: #user-content-dev.hardwood.reader.filterpredicate
[dev.hardwood.reader.FilterPredicate$And]: #user-content-dev.hardwood.reader.filterpredicate$and
[dev.hardwood.reader.FilterPredicate$BinaryColumnPredicate]: #user-content-dev.hardwood.reader.filterpredicate$binarycolumnpredicate
[dev.hardwood.reader.FilterPredicate$BinaryInPredicate]: #user-content-dev.hardwood.reader.filterpredicate$binaryinpredicate
[dev.hardwood.reader.FilterPredicate$BooleanColumnPredicate]: #user-content-dev.hardwood.reader.filterpredicate$booleancolumnpredicate
[dev.hardwood.reader.FilterPredicate$DateColumnPredicate]: #user-content-dev.hardwood.reader.filterpredicate$datecolumnpredicate
[dev.hardwood.reader.FilterPredicate$DecimalColumnPredicate]: #user-content-dev.hardwood.reader.filterpredicate$decimalcolumnpredicate
[dev.hardwood.reader.FilterPredicate$DoubleColumnPredicate]: #user-content-dev.hardwood.reader.filterpredicate$doublecolumnpredicate
[dev.hardwood.reader.FilterPredicate$FloatColumnPredicate]: #user-content-dev.hardwood.reader.filterpredicate$floatcolumnpredicate
[dev.hardwood.reader.FilterPredicate$InstantColumnPredicate]: #user-content-dev.hardwood.reader.filterpredicate$instantcolumnpredicate
[dev.hardwood.reader.FilterPredicate$IntColumnPredicate]: #user-content-dev.hardwood.reader.filterpredicate$intcolumnpredicate
[dev.hardwood.reader.FilterPredicate$IntInPredicate]: #user-content-dev.hardwood.reader.filterpredicate$intinpredicate
[dev.hardwood.reader.FilterPredicate$IsNotNullPredicate]: #user-content-dev.hardwood.reader.filterpredicate$isnotnullpredicate
[dev.hardwood.reader.FilterPredicate$IsNullPredicate]: #user-content-dev.hardwood.reader.filterpredicate$isnullpredicate
[dev.hardwood.reader.FilterPredicate$LongColumnPredicate]: #user-content-dev.hardwood.reader.filterpredicate$longcolumnpredicate
[dev.hardwood.reader.FilterPredicate$LongInPredicate]: #user-content-dev.hardwood.reader.filterpredicate$longinpredicate
[dev.hardwood.reader.FilterPredicate$Not]: #user-content-dev.hardwood.reader.filterpredicate$not
[dev.hardwood.reader.FilterPredicate$Operator]: #user-content-dev.hardwood.reader.filterpredicate$operator
[dev.hardwood.reader.FilterPredicate$Or]: #user-content-dev.hardwood.reader.filterpredicate$or
[dev.hardwood.reader.FilterPredicate$SignedBinaryColumnPredicate]: #user-content-dev.hardwood.reader.filterpredicate$signedbinarycolumnpredicate
[dev.hardwood.reader.FilterPredicate$TimeColumnPredicate]: #user-content-dev.hardwood.reader.filterpredicate$timecolumnpredicate
[dev.hardwood.reader.MultiFileParquetReader]: #user-content-dev.hardwood.reader.multifileparquetreader
[dev.hardwood.reader.MultiFileRowReader]: #user-content-dev.hardwood.reader.multifilerowreader
[dev.hardwood.reader.ParquetFileReader]: #user-content-dev.hardwood.reader.parquetfilereader
[dev.hardwood.reader.RowReader]: #user-content-dev.hardwood.reader.rowreader
[dev.hardwood.row.PqStruct]: #user-content-dev.hardwood.row.pqstruct
[dev.hardwood.row.StructAccessor]: #user-content-dev.hardwood.row.structaccessor
[dev.hardwood.schema.ColumnSchema]: #user-content-dev.hardwood.schema.columnschema
[dev.hardwood.schema.FileSchema]: #user-content-dev.hardwood.schema.fileschema
