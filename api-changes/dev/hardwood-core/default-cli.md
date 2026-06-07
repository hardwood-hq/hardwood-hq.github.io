
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

| Status | Type                                                           | Serialization       | Compatibility Changes |
|--------|----------------------------------------------------------------|---------------------|-----------------------|
| Added  | [dev.hardwood.Experimental]                                    | ![Not serializable] | ![Annotation added] ![Interface added] |
| Added  | [dev.hardwood.Hardwood]                                        | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.HardwoodContext]                                 | ![Not serializable] | ![Interface added]    |
| Added  | [dev.hardwood.InputFile]                                       | ![Not serializable] | ![Interface added]    |
| Added  | [dev.hardwood.jfr.BatchWaitEvent]                              | ![Not serializable] | ![Annotation added]   |
| Added  | [dev.hardwood.jfr.FileMappingEvent]                            | ![Not serializable] | ![Annotation added]   |
| Added  | [dev.hardwood.jfr.FileOpenedEvent]                             | ![Not serializable] | ![Annotation added]   |
| Added  | [dev.hardwood.jfr.PageDecodedEvent]                            | ![Not serializable] | ![Annotation added]   |
| Added  | [dev.hardwood.jfr.PageFilterEvent]                             | ![Not serializable] | ![Annotation added]   |
| Added  | [dev.hardwood.jfr.PrefetchMissEvent]                           | ![Not serializable] | ![Annotation added]   |
| Added  | [dev.hardwood.jfr.RecordFilterEvent]                           | ![Not serializable] | ![Annotation added]   |
| Added  | [dev.hardwood.jfr.RowGroupFilterEvent]                         | ![Not serializable] | ![Annotation added]   |
| Added  | [dev.hardwood.jfr.RowGroupScannedEvent]                        | ![Not serializable] | ![Annotation added]   |
| Added  | [dev.hardwood.metadata.BoundingBox]                            | ![Not serializable] | ![Method added to public class] |
| Added  | [dev.hardwood.metadata.ColumnChunk]                            | ![Not serializable] | ![Method added to public class] |
| Added  | [dev.hardwood.metadata.ColumnIndex]                            | ![Not serializable] | ![Method added to public class] |
| Added  | [dev.hardwood.metadata.ColumnIndex$BoundaryOrder]              | ![Compatible]       | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.metadata.ColumnMetaData]                         | ![Not serializable] | ![Method added to public class] |
| Added  | [dev.hardwood.metadata.CompressionCodec]                       | ![Compatible]       | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.metadata.ConvertedType]                          | ![Compatible]       | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.metadata.Encoding]                               | ![Compatible]       | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.metadata.FieldPath]                              | ![Not serializable] | ![Method added to public class] |
| Added  | [dev.hardwood.metadata.FileMetaData]                           | ![Not serializable] | ![Method added to public class] |
| Added  | [dev.hardwood.metadata.GeospatialStatistics]                   | ![Not serializable] | ![Method added to public class] |
| Added  | [dev.hardwood.metadata.LogicalType]                            | ![Not serializable] | ![No changes]         |
| Added  | [dev.hardwood.metadata.LogicalType$BsonType]                   | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.metadata.LogicalType$DateType]                   | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.metadata.LogicalType$DecimalType]                | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.metadata.LogicalType$EdgeInterpolationAlgorithm] | ![Compatible]       | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.metadata.LogicalType$EnumType]                   | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.metadata.LogicalType$Float16Type]                | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.metadata.LogicalType$GeographyType]              | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.metadata.LogicalType$GeometryType]               | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.metadata.LogicalType$IntType]                    | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.metadata.LogicalType$IntervalType]               | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.metadata.LogicalType$JsonType]                   | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.metadata.LogicalType$ListType]                   | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.metadata.LogicalType$MapType]                    | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.metadata.LogicalType$NullType]                   | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.metadata.LogicalType$StringType]                 | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.metadata.LogicalType$TimeType]                   | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.metadata.LogicalType$TimeUnit]                   | ![Compatible]       | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.metadata.LogicalType$TimestampType]              | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.metadata.LogicalType$UuidType]                   | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.metadata.LogicalType$VariantType]                | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.metadata.OffsetIndex]                            | ![Not serializable] | ![Method added to public class] |
| Added  | [dev.hardwood.metadata.PageLocation]                           | ![Not serializable] | ![Method added to public class] |
| Added  | [dev.hardwood.metadata.PhysicalType]                           | ![Compatible]       | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.metadata.RepetitionType]                         | ![Compatible]       | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.metadata.RowGroup]                               | ![Not serializable] | ![Method added to public class] |
| Added  | [dev.hardwood.metadata.SchemaElement]                          | ![Not serializable] | ![Method added to public class] |
| Added  | [dev.hardwood.metadata.Statistics]                             | ![Not serializable] | ![Method added to public class] |
| Added  | [dev.hardwood.reader.ColumnReader]                             | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.reader.ColumnReaders]                            | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.reader.FilterPredicate]                          | ![Not serializable] | ![No changes]         |
| Added  | [dev.hardwood.reader.FilterPredicate$And]                      | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.reader.FilterPredicate$BinaryColumnPredicate]    | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.reader.FilterPredicate$BinaryInPredicate]        | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.reader.FilterPredicate$BooleanColumnPredicate]   | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.reader.FilterPredicate$DateColumnPredicate]      | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.reader.FilterPredicate$DecimalColumnPredicate]   | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.reader.FilterPredicate$DoubleColumnPredicate]    | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.reader.FilterPredicate$FloatColumnPredicate]     | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.reader.FilterPredicate$InstantColumnPredicate]   | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.reader.FilterPredicate$IntColumnPredicate]       | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.reader.FilterPredicate$IntInPredicate]           | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.reader.FilterPredicate$IntersectsPredicate]      | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.reader.FilterPredicate$IsNotNullPredicate]       | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.reader.FilterPredicate$IsNullPredicate]          | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.reader.FilterPredicate$LongColumnPredicate]      | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.reader.FilterPredicate$LongInPredicate]          | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.reader.FilterPredicate$Not]                      | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.reader.FilterPredicate$Operator]                 | ![Compatible]       | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.reader.FilterPredicate$Or]                       | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.reader.FilterPredicate$SignedBinaryColumnPredicate] | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.reader.FilterPredicate$TimeColumnPredicate]      | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.reader.FilterPredicate$UUIDColumnPredicate]      | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.reader.LayerKind]                                | ![Compatible]       | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.reader.ParquetFileReader]                        | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.reader.ParquetFileReader$ColumnReaderBuilder]    | ![Not serializable] | ![Method added to public class] |
| Added  | [dev.hardwood.reader.ParquetFileReader$ColumnReadersBuilder]   | ![Not serializable] | ![Method added to public class] |
| Added  | [dev.hardwood.reader.ParquetFileReader$RowReaderBuilder]       | ![Not serializable] | ![Method added to public class] |
| Added  | [dev.hardwood.reader.RowGroupPredicate]                        | ![Not serializable] | ![No changes]         |
| Added  | [dev.hardwood.reader.RowGroupPredicate$And]                    | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.reader.RowGroupPredicate$ByteRange]              | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.reader.RowReader]                                | ![Not serializable] | ![Interface added]    |
| Added  | [dev.hardwood.reader.SchemaIncompatibleException]              | ![Compatible]       | ![Interface added]    |
| Added  | [dev.hardwood.reader.Validity]                                 | ![Not serializable] | ![No changes]         |
| Added  | [dev.hardwood.row.FieldAccessor]                               | ![Not serializable] | ![No changes]         |
| Added  | [dev.hardwood.row.PqDoubleList]                                | ![Not serializable] | ![No changes]         |
| Added  | [dev.hardwood.row.PqIntList]                                   | ![Not serializable] | ![No changes]         |
| Added  | [dev.hardwood.row.PqInterval]                                  | ![Not serializable] | ![Method added to public class] |
| Added  | [dev.hardwood.row.PqList]                                      | ![Not serializable] | ![No changes]         |
| Added  | [dev.hardwood.row.PqLongList]                                  | ![Not serializable] | ![No changes]         |
| Added  | [dev.hardwood.row.PqMap]                                       | ![Not serializable] | ![No changes]         |
| Added  | [dev.hardwood.row.PqMap$Entry]                                 | ![Not serializable] | ![No changes]         |
| Added  | [dev.hardwood.row.PqStruct]                                    | ![Not serializable] | ![Interface added]    |
| Added  | [dev.hardwood.row.PqVariant]                                   | ![Not serializable] | ![No changes]         |
| Added  | [dev.hardwood.row.PqVariantArray]                              | ![Not serializable] | ![Interface added]    |
| Added  | [dev.hardwood.row.PqVariantObject]                             | ![Not serializable] | ![Interface added]    |
| Added  | [dev.hardwood.row.StructAccessor]                              | ![Not serializable] | ![Interface added]    |
| Added  | [dev.hardwood.row.VariantType]                                 | ![Compatible]       | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.row.VariantTypeException]                        | ![Compatible]       | ![Interface added]    |
| Added  | [dev.hardwood.schema.ColumnProjection]                         | ![Not serializable] | ![Method added to public class] |
| Added  | [dev.hardwood.schema.ColumnSchema]                             | ![Not serializable] | ![Method added to public class] |
| Added  | [dev.hardwood.schema.FileSchema]                               | ![Not serializable] | ![Method added to public class] |
| Added  | [dev.hardwood.schema.SchemaNode]                               | ![Not serializable] | ![No changes]         |
| Added  | [dev.hardwood.schema.SchemaNode$GroupNode]                     | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.schema.SchemaNode$PrimitiveNode]                 | ![Not serializable] | ![Interface added] ![Method added to public class] |

<details markdown="1">
<summary>Expand for details.</summary>

___

<a id="user-content-dev.hardwood.experimental"></a>
### `dev.hardwood.Experimental`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                   | Type           | Name               | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|-----------------------------|----------------|--------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`public`** **`abstract`** | **Annotation** | **`Experimental`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![Interface added] ![Annotation added] |


#### Implemented Interfaces

| Status | Interface          | Compatibility Changes |
|--------|--------------------|-----------------------|
| Added  | **[`Annotation`]** | ![No changes]         |


#### Annotations

| Status | Annotation                                   | Compatibility Changes |
|--------|----------------------------------------------|-----------------------|
| Added  | **[`Documented`]**                           | ![No changes]         |
| Added  | **[`Retention`]**: **`value`**=**[`CLASS`]** | ![No changes]         |
| Added  | **[`Target`]**: **`value`**=**[`{TYPE, METHOD, CONSTRUCTOR, FIELD}`]** | ![No changes] |

___

<a id="user-content-dev.hardwood.hardwood"></a>
### `dev.hardwood.Hardwood`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers    | Type      | Name           | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|--------------|-----------|----------------|----------------|------------|---------------------|-----------------------|
| Added  | **`public`** | **Class** | **`Hardwood`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface             | Compatibility Changes |
|--------|-----------------------|-----------------------|
| Added  | **[`AutoCloseable`]** | ![No changes]         |


#### Methods

| Status | Modifiers                 | Generics | Type                      | Method                                       | Annotations | Throws              | Compatibility Changes |
|--------|---------------------------|----------|---------------------------|----------------------------------------------|-------------|---------------------|-----------------------|
| Added  | **`public`**              |          | **`void`**                | **`close`**()                                |             |                     | ![Method added to public class] |
| Added  | **`static`** **`public`** |          | **[`Hardwood`]**          | **`create`**()                               |             |                     | ![Method added to public class] |
| Added  | **`public`**              |          | **[`ParquetFileReader`]** | **`open`**([`InputFile`])                    |             | **[`IOException`]** | ![Method added to public class] |
| Added  | **`public`**              |          | **[`ParquetFileReader`]** | **`openAll`**([`List<? extends InputFile>`]) |             | **[`IOException`]** | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.hardwoodcontext"></a>
### `dev.hardwood.HardwoodContext`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                   | Type          | Name                  | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|-----------------------------|---------------|-----------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`public`** **`abstract`** | **Interface** | **`HardwoodContext`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface             | Compatibility Changes |
|--------|-----------------------|-----------------------|
| Added  | **[`AutoCloseable`]** | ![No changes]         |


#### Methods

| Status | Modifiers                   | Generics | Type                    | Method              | Annotations | Throws | Compatibility Changes |
|--------|-----------------------------|----------|-------------------------|---------------------|-------------|--------|-----------------------|
| Added  | **`public`** **`abstract`** |          | **`void`**              | **`close`**()       |             |        | ![No changes]         |
| Added  | **`static`** **`public`**   |          | **[`HardwoodContext`]** | **`create`**()      |             |        | ![No changes]         |
| Added  | **`static`** **`public`**   |          | **[`HardwoodContext`]** | **`create`**(`int`) |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`ExecutorService`]** | **`executor`**()    |             |        | ![No changes]         |

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

<a id="user-content-dev.hardwood.metadata.boundingbox"></a>
### `dev.hardwood.metadata.BoundingBox`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                | Type      | Name              | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|--------------------------|-----------|-------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`public`** | **Class** | **`BoundingBox`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`BoundingBox`**(`double`, `double`, `double`, `double`, [`Double`], [`Double`], [`Double`], [`Double`]) |  |  | ![No changes] |


#### Methods

| Status | Modifiers                | Generics | Type           | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|----------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`final`** **`public`** |          | **`boolean`**  | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**      | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`Double`]** | **`mmax`**()             |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`Double`]** | **`mmin`**()             |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]** | **`toString`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`double`**   | **`xmax`**()             |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`double`**   | **`xmin`**()             |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`double`**   | **`ymax`**()             |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`double`**   | **`ymin`**()             |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`Double`]** | **`zmax`**()             |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`Double`]** | **`zmin`**()             |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.metadata.columnchunk"></a>
### `dev.hardwood.metadata.ColumnChunk`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                | Type      | Name              | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|--------------------------|-----------|-------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`public`** | **Class** | **`ColumnChunk`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`ColumnChunk`**([`ColumnMetaData`], [`Long`], [`Integer`], [`Long`], [`Integer`]) |  |  | ![No changes] |


#### Methods

| Status | Modifiers                | Generics | Type                   | Method                    | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|------------------------|---------------------------|-------------|--------|-----------------------|
| Added  | **`public`**             |          | **`long`**             | **`chunkStartOffset`**()  |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`Integer`]**        | **`columnIndexLength`**() |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`Long`]**           | **`columnIndexOffset`**() |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`boolean`**          | **`equals`**([`Object`])  |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**              | **`hashCode`**()          |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`ColumnMetaData`]** | **`metaData`**()          |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`Integer`]**        | **`offsetIndexLength`**() |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`Long`]**           | **`offsetIndexOffset`**() |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]**         | **`toString`**()          |             |        | ![Method added to public class] |

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

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                | Type      | Name                 | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|--------------------------|-----------|----------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`public`** | **Class** | **`ColumnMetaData`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`ColumnMetaData`**([`PhysicalType`], [`List<Encoding>`], [`FieldPath`], [`CompressionCodec`], `long`, `long`, `long`, [`Map<String, String>`], `long`, [`Long`], [`Statistics`], [`GeospatialStatistics`], [`Long`], [`Integer`]) |  |  | ![No changes] |


#### Methods

| Status | Modifiers                | Generics | Type                         | Method                        | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|------------------------------|-------------------------------|-------------|--------|-----------------------|
| Added  | **`public`**             |          | **[`Integer`]**              | **`bloomFilterLength`**()     |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`Long`]**                 | **`bloomFilterOffset`**()     |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`CompressionCodec`]**     | **`codec`**()                 |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`long`**                   | **`dataPageOffset`**()        |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`Long`]**                 | **`dictionaryPageOffset`**()  |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`List<Encoding>`]**       | **`encodings`**()             |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`boolean`**                | **`equals`**([`Object`])      |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`GeospatialStatistics`]** | **`geospatialStatistics`**()  |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**                    | **`hashCode`**()              |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`Map<String, String>`]**  | **`keyValueMetadata`**()      |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`long`**                   | **`numValues`**()             |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`FieldPath`]**            | **`pathInSchema`**()          |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`Statistics`]**           | **`statistics`**()            |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]**               | **`toString`**()              |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`long`**                   | **`totalCompressedSize`**()   |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`long`**                   | **`totalUncompressedSize`**() |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`PhysicalType`]**         | **`type`**()                  |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.metadata.compressioncodec"></a>
### `dev.hardwood.metadata.CompressionCodec`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                | Type     | Name                   | Extends         | JDK        | Serialization | Compatibility Changes |
|--------|--------------------------|----------|------------------------|-----------------|------------|---------------|-----------------------|
| Added  | **`final`** **`public`** | **Enum** | **`CompressionCodec`** | **[`Enum<E>`]** | **JDK 21** | ![Compatible] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface             | Compatibility Changes |
|--------|-----------------------|-----------------------|
| Added  | **[`Serializable`]**  | ![No changes]         |
| Added  | **[`Comparable<T>`]** | ![No changes]         |
| Added  | **[`Constable`]**     | ![No changes]         |


#### Methods

| Status | Modifiers                 | Generics | Type                          | Method                    | Annotations | Throws | Compatibility Changes |
|--------|---------------------------|----------|-------------------------------|---------------------------|-------------|--------|-----------------------|
| Added  | **`static`** **`public`** |          | **[`CompressionCodec`]**      | **`valueOf`**([`String`]) |             |        | ![Method added to public class] |
| Added  | **`static`** **`public`** |          | **[`CompressionCodec[]`][2]** | **`values`**()            |             |        | ![Method added to public class] |


#### Fields

| Status | Modifiers                             | Type                     | Name           | Annotations | Compatibility Changes |
|--------|---------------------------------------|--------------------------|----------------|-------------|-----------------------|
| Added  | **`public`** **`static`** **`final`** | **[`CompressionCodec`]** | `BROTLI`       |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`CompressionCodec`]** | `GZIP`         |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`CompressionCodec`]** | `LZ4`          |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`CompressionCodec`]** | `LZ4_RAW`      |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`CompressionCodec`]** | `LZO`          |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`CompressionCodec`]** | `SNAPPY`       |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`CompressionCodec`]** | `UNCOMPRESSED` |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`CompressionCodec`]** | `ZSTD`         |             | ![No changes]         |

___

<a id="user-content-dev.hardwood.metadata.convertedtype"></a>
### `dev.hardwood.metadata.ConvertedType`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                | Type     | Name                | Extends         | JDK        | Serialization | Compatibility Changes |
|--------|--------------------------|----------|---------------------|-----------------|------------|---------------|-----------------------|
| Added  | **`final`** **`public`** | **Enum** | **`ConvertedType`** | **[`Enum<E>`]** | **JDK 21** | ![Compatible] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface             | Compatibility Changes |
|--------|-----------------------|-----------------------|
| Added  | **[`Serializable`]**  | ![No changes]         |
| Added  | **[`Comparable<T>`]** | ![No changes]         |
| Added  | **[`Constable`]**     | ![No changes]         |


#### Methods

| Status | Modifiers                 | Generics | Type                       | Method                    | Annotations | Throws | Compatibility Changes |
|--------|---------------------------|----------|----------------------------|---------------------------|-------------|--------|-----------------------|
| Added  | **`static`** **`public`** |          | **[`ConvertedType`]**      | **`valueOf`**([`String`]) |             |        | ![Method added to public class] |
| Added  | **`static`** **`public`** |          | **[`ConvertedType[]`][3]** | **`values`**()            |             |        | ![Method added to public class] |


#### Fields

| Status | Modifiers                             | Type                  | Name               | Annotations | Compatibility Changes |
|--------|---------------------------------------|-----------------------|--------------------|-------------|-----------------------|
| Added  | **`public`** **`static`** **`final`** | **[`ConvertedType`]** | `BSON`             |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`ConvertedType`]** | `DATE`             |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`ConvertedType`]** | `DECIMAL`          |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`ConvertedType`]** | `ENUM`             |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`ConvertedType`]** | `INTERVAL`         |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`ConvertedType`]** | `INT_16`           |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`ConvertedType`]** | `INT_32`           |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`ConvertedType`]** | `INT_64`           |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`ConvertedType`]** | `INT_8`            |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`ConvertedType`]** | `JSON`             |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`ConvertedType`]** | `LIST`             |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`ConvertedType`]** | `MAP`              |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`ConvertedType`]** | `MAP_KEY_VALUE`    |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`ConvertedType`]** | `TIMESTAMP_MICROS` |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`ConvertedType`]** | `TIMESTAMP_MILLIS` |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`ConvertedType`]** | `TIME_MICROS`      |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`ConvertedType`]** | `TIME_MILLIS`      |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`ConvertedType`]** | `UINT_16`          |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`ConvertedType`]** | `UINT_32`          |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`ConvertedType`]** | `UINT_64`          |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`ConvertedType`]** | `UINT_8`           |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`ConvertedType`]** | `UTF8`             |             | ![No changes]         |

___

<a id="user-content-dev.hardwood.metadata.encoding"></a>
### `dev.hardwood.metadata.Encoding`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                | Type     | Name           | Extends         | JDK        | Serialization | Compatibility Changes |
|--------|--------------------------|----------|----------------|-----------------|------------|---------------|-----------------------|
| Added  | **`final`** **`public`** | **Enum** | **`Encoding`** | **[`Enum<E>`]** | **JDK 21** | ![Compatible] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface             | Compatibility Changes |
|--------|-----------------------|-----------------------|
| Added  | **[`Serializable`]**  | ![No changes]         |
| Added  | **[`Comparable<T>`]** | ![No changes]         |
| Added  | **[`Constable`]**     | ![No changes]         |


#### Methods

| Status | Modifiers                 | Generics | Type                  | Method                    | Annotations | Throws | Compatibility Changes |
|--------|---------------------------|----------|-----------------------|---------------------------|-------------|--------|-----------------------|
| Added  | **`static`** **`public`** |          | **[`Encoding`]**      | **`valueOf`**([`String`]) |             |        | ![Method added to public class] |
| Added  | **`static`** **`public`** |          | **[`Encoding[]`][4]** | **`values`**()            |             |        | ![Method added to public class] |


#### Fields

| Status | Modifiers                             | Type             | Name                      | Annotations | Compatibility Changes |
|--------|---------------------------------------|------------------|---------------------------|-------------|-----------------------|
| Added  | **`public`** **`static`** **`final`** | **[`Encoding`]** | `BIT_PACKED`              |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`Encoding`]** | `BYTE_STREAM_SPLIT`       |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`Encoding`]** | `DELTA_BINARY_PACKED`     |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`Encoding`]** | `DELTA_BYTE_ARRAY`        |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`Encoding`]** | `DELTA_LENGTH_BYTE_ARRAY` |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`Encoding`]** | `PLAIN`                   |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`Encoding`]** | `PLAIN_DICTIONARY`        |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`Encoding`]** | `RLE`                     |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`Encoding`]** | `RLE_DICTIONARY`          |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`Encoding`]** | `UNKNOWN`                 |             | ![No changes]         |

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

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                | Type      | Name               | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|--------------------------|-----------|--------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`public`** | **Class** | **`FileMetaData`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`FileMetaData`**(`int`, [`List<SchemaElement>`], `long`, [`List<RowGroup>`], [`Map<String, String>`], [`String`]) |  |  | ![No changes] |


#### Methods

| Status | Modifiers                | Generics | Type                        | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|-----------------------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`public`**             |          | **[`String`]**              | **`createdBy`**()        |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`boolean`**               | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**                   | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`Map<String, String>`]** | **`keyValueMetadata`**() |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`long`**                  | **`numRows`**()          |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`List<RowGroup>`]**      | **`rowGroups`**()        |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`List<SchemaElement>`]** | **`schema`**()           |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]**              | **`toString`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`int`**                   | **`version`**()          |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.metadata.geospatialstatistics"></a>
### `dev.hardwood.metadata.GeospatialStatistics`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                | Type      | Name                       | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|--------------------------|-----------|----------------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`public`** | **Class** | **`GeospatialStatistics`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor                                                    | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|----------------------------------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`GeospatialStatistics`**([`BoundingBox`], [`List<Integer>`]) |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type                  | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|-----------------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`public`**             |          | **[`BoundingBox`]**   | **`bbox`**()             |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`boolean`**         | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`List<Integer>`]** | **`geospatialTypes`**()  |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**             | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]**        | **`toString`**()         |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.metadata.logicaltype"></a>
### `dev.hardwood.metadata.LogicalType`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                   | Type          | Name              | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|-----------------------------|---------------|-------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`public`** **`abstract`** | **Interface** | **`LogicalType`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![No changes]         |

___

<a id="user-content-dev.hardwood.metadata.logicaltype$bsontype"></a>
### `dev.hardwood.metadata.LogicalType$BsonType`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name           | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|----------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`BsonType`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface           | Compatibility Changes |
|--------|---------------------|-----------------------|
| Added  | **[`LogicalType`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor      | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`BsonType`**() |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type           | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|----------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`final`** **`public`** |          | **`boolean`**  | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**      | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]** | **`toString`**()         |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.metadata.logicaltype$datetype"></a>
### `dev.hardwood.metadata.LogicalType$DateType`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name           | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|----------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`DateType`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface           | Compatibility Changes |
|--------|---------------------|-----------------------|
| Added  | **[`LogicalType`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor      | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`DateType`**() |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type           | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|----------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`final`** **`public`** |          | **`boolean`**  | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**      | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]** | **`toString`**()         |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.metadata.logicaltype$decimaltype"></a>
### `dev.hardwood.metadata.LogicalType$DecimalType`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name              | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|-------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`DecimalType`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface           | Compatibility Changes |
|--------|---------------------|-----------------------|
| Added  | **[`LogicalType`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor                     | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|---------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`DecimalType`**(`int`, `int`) |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type           | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|----------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`final`** **`public`** |          | **`boolean`**  | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**      | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`int`**      | **`precision`**()        |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`int`**      | **`scale`**()            |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]** | **`toString`**()         |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.metadata.logicaltype$edgeinterpolationalgorithm"></a>
### `dev.hardwood.metadata.LogicalType$EdgeInterpolationAlgorithm`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type     | Name                             | Extends         | JDK        | Serialization | Compatibility Changes |
|--------|---------------------------------------|----------|----------------------------------|-----------------|------------|---------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Enum** | **`EdgeInterpolationAlgorithm`** | **[`Enum<E>`]** | **JDK 21** | ![Compatible] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface             | Compatibility Changes |
|--------|-----------------------|-----------------------|
| Added  | **[`Serializable`]**  | ![No changes]         |
| Added  | **[`Comparable<T>`]** | ![No changes]         |
| Added  | **[`Constable`]**     | ![No changes]         |


#### Methods

| Status | Modifiers                 | Generics | Type                                    | Method                    | Annotations | Throws | Compatibility Changes |
|--------|---------------------------|----------|-----------------------------------------|---------------------------|-------------|--------|-----------------------|
| Added  | **`static`** **`public`** |          | **[`EdgeInterpolationAlgorithm`]**      | **`valueOf`**([`String`]) |             |        | ![Method added to public class] |
| Added  | **`static`** **`public`** |          | **[`EdgeInterpolationAlgorithm[]`][5]** | **`values`**()            |             |        | ![Method added to public class] |


#### Fields

| Status | Modifiers                             | Type                               | Name        | Annotations | Compatibility Changes |
|--------|---------------------------------------|------------------------------------|-------------|-------------|-----------------------|
| Added  | **`public`** **`static`** **`final`** | **[`EdgeInterpolationAlgorithm`]** | `ANDOYER`   |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`EdgeInterpolationAlgorithm`]** | `KARNEY`    |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`EdgeInterpolationAlgorithm`]** | `SPHERICAL` |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`EdgeInterpolationAlgorithm`]** | `THOMAS`    |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`EdgeInterpolationAlgorithm`]** | `VINCENTY`  |             | ![No changes]         |

___

<a id="user-content-dev.hardwood.metadata.logicaltype$enumtype"></a>
### `dev.hardwood.metadata.LogicalType$EnumType`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name           | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|----------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`EnumType`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface           | Compatibility Changes |
|--------|---------------------|-----------------------|
| Added  | **[`LogicalType`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor      | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`EnumType`**() |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type           | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|----------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`final`** **`public`** |          | **`boolean`**  | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**      | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]** | **`toString`**()         |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.metadata.logicaltype$float16type"></a>
### `dev.hardwood.metadata.LogicalType$Float16Type`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name              | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|-------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`Float16Type`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface           | Compatibility Changes |
|--------|---------------------|-----------------------|
| Added  | **[`LogicalType`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor         | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|---------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`Float16Type`**() |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type           | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|----------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`final`** **`public`** |          | **`boolean`**  | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**      | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]** | **`toString`**()         |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.metadata.logicaltype$geographytype"></a>
### `dev.hardwood.metadata.LogicalType$GeographyType`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name                | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|---------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`GeographyType`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface           | Compatibility Changes |
|--------|---------------------|-----------------------|
| Added  | **[`LogicalType`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor                                                     | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-----------------------------------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`GeographyType`**([`String`], [`EdgeInterpolationAlgorithm`]) |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type                               | Method                    | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|------------------------------------|---------------------------|-------------|--------|-----------------------|
| Added  | **`public`**             |          | **[`String`]**                     | **`crs`**()               |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`EdgeInterpolationAlgorithm`]** | **`edgeInterpolation`**() |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`boolean`**                      | **`equals`**([`Object`])  |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**                          | **`hashCode`**()          |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]**                     | **`toString`**()          |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.metadata.logicaltype$geometrytype"></a>
### `dev.hardwood.metadata.LogicalType$GeometryType`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name               | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|--------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`GeometryType`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface           | Compatibility Changes |
|--------|---------------------|-----------------------|
| Added  | **[`LogicalType`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor                    | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|--------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`GeometryType`**([`String`]) |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type           | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|----------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`public`**             |          | **[`String`]** | **`crs`**()              |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`boolean`**  | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**      | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]** | **`toString`**()         |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.metadata.logicaltype$inttype"></a>
### `dev.hardwood.metadata.LogicalType$IntType`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name          | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|---------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`IntType`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface           | Compatibility Changes |
|--------|---------------------|-----------------------|
| Added  | **[`LogicalType`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor                     | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|---------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`IntType`**(`int`, `boolean`) |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type           | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|----------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`public`**             |          | **`int`**      | **`bitWidth`**()         |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`boolean`**  | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**      | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`boolean`**  | **`isSigned`**()         |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]** | **`toString`**()         |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.metadata.logicaltype$intervaltype"></a>
### `dev.hardwood.metadata.LogicalType$IntervalType`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name               | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|--------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`IntervalType`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface           | Compatibility Changes |
|--------|---------------------|-----------------------|
| Added  | **[`LogicalType`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor          | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|----------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`IntervalType`**() |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type           | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|----------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`final`** **`public`** |          | **`boolean`**  | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**      | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]** | **`toString`**()         |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.metadata.logicaltype$jsontype"></a>
### `dev.hardwood.metadata.LogicalType$JsonType`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name           | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|----------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`JsonType`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface           | Compatibility Changes |
|--------|---------------------|-----------------------|
| Added  | **[`LogicalType`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor      | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`JsonType`**() |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type           | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|----------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`final`** **`public`** |          | **`boolean`**  | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**      | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]** | **`toString`**()         |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.metadata.logicaltype$listtype"></a>
### `dev.hardwood.metadata.LogicalType$ListType`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name           | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|----------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`ListType`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface           | Compatibility Changes |
|--------|---------------------|-----------------------|
| Added  | **[`LogicalType`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor      | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`ListType`**() |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type           | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|----------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`final`** **`public`** |          | **`boolean`**  | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**      | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]** | **`toString`**()         |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.metadata.logicaltype$maptype"></a>
### `dev.hardwood.metadata.LogicalType$MapType`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name          | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|---------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`MapType`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface           | Compatibility Changes |
|--------|---------------------|-----------------------|
| Added  | **[`LogicalType`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor     | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-----------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`MapType`**() |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type           | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|----------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`final`** **`public`** |          | **`boolean`**  | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**      | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]** | **`toString`**()         |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.metadata.logicaltype$nulltype"></a>
### `dev.hardwood.metadata.LogicalType$NullType`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name           | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|----------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`NullType`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface           | Compatibility Changes |
|--------|---------------------|-----------------------|
| Added  | **[`LogicalType`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor      | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`NullType`**() |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type           | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|----------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`final`** **`public`** |          | **`boolean`**  | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**      | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]** | **`toString`**()         |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.metadata.logicaltype$stringtype"></a>
### `dev.hardwood.metadata.LogicalType$StringType`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name             | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`StringType`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface           | Compatibility Changes |
|--------|---------------------|-----------------------|
| Added  | **[`LogicalType`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor        | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|--------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`StringType`**() |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type           | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|----------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`final`** **`public`** |          | **`boolean`**  | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**      | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]** | **`toString`**()         |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.metadata.logicaltype$timetype"></a>
### `dev.hardwood.metadata.LogicalType$TimeType`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name           | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|----------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`TimeType`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface           | Compatibility Changes |
|--------|---------------------|-----------------------|
| Added  | **[`LogicalType`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor                             | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-----------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`TimeType`**(`boolean`, [`TimeUnit`]) |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type             | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|------------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`final`** **`public`** |          | **`boolean`**    | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**        | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`boolean`**    | **`isAdjustedToUTC`**()  |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]**   | **`toString`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`TimeUnit`]** | **`unit`**()             |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.metadata.logicaltype$timeunit"></a>
### `dev.hardwood.metadata.LogicalType$TimeUnit`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type     | Name           | Extends         | JDK        | Serialization | Compatibility Changes |
|--------|---------------------------------------|----------|----------------|-----------------|------------|---------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Enum** | **`TimeUnit`** | **[`Enum<E>`]** | **JDK 21** | ![Compatible] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface             | Compatibility Changes |
|--------|-----------------------|-----------------------|
| Added  | **[`Serializable`]**  | ![No changes]         |
| Added  | **[`Comparable<T>`]** | ![No changes]         |
| Added  | **[`Constable`]**     | ![No changes]         |


#### Methods

| Status | Modifiers                 | Generics | Type                  | Method                    | Annotations | Throws | Compatibility Changes |
|--------|---------------------------|----------|-----------------------|---------------------------|-------------|--------|-----------------------|
| Added  | **`static`** **`public`** |          | **[`TimeUnit`]**      | **`valueOf`**([`String`]) |             |        | ![Method added to public class] |
| Added  | **`static`** **`public`** |          | **[`TimeUnit[]`][6]** | **`values`**()            |             |        | ![Method added to public class] |


#### Fields

| Status | Modifiers                             | Type             | Name     | Annotations | Compatibility Changes |
|--------|---------------------------------------|------------------|----------|-------------|-----------------------|
| Added  | **`public`** **`static`** **`final`** | **[`TimeUnit`]** | `MICROS` |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`TimeUnit`]** | `MILLIS` |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`TimeUnit`]** | `NANOS`  |             | ![No changes]         |

___

<a id="user-content-dev.hardwood.metadata.logicaltype$timestamptype"></a>
### `dev.hardwood.metadata.LogicalType$TimestampType`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name                | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|---------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`TimestampType`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface           | Compatibility Changes |
|--------|---------------------|-----------------------|
| Added  | **[`LogicalType`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor                                  | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|----------------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`TimestampType`**(`boolean`, [`TimeUnit`]) |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type             | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|------------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`final`** **`public`** |          | **`boolean`**    | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**        | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`boolean`**    | **`isAdjustedToUTC`**()  |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]**   | **`toString`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`TimeUnit`]** | **`unit`**()             |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.metadata.logicaltype$uuidtype"></a>
### `dev.hardwood.metadata.LogicalType$UuidType`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name           | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|----------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`UuidType`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface           | Compatibility Changes |
|--------|---------------------|-----------------------|
| Added  | **[`LogicalType`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor      | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`UuidType`**() |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type           | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|----------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`final`** **`public`** |          | **`boolean`**  | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**      | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]** | **`toString`**()         |             |        | ![Method added to public class] |

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

<a id="user-content-dev.hardwood.metadata.physicaltype"></a>
### `dev.hardwood.metadata.PhysicalType`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                | Type     | Name               | Extends         | JDK        | Serialization | Compatibility Changes |
|--------|--------------------------|----------|--------------------|-----------------|------------|---------------|-----------------------|
| Added  | **`final`** **`public`** | **Enum** | **`PhysicalType`** | **[`Enum<E>`]** | **JDK 21** | ![Compatible] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface             | Compatibility Changes |
|--------|-----------------------|-----------------------|
| Added  | **[`Serializable`]**  | ![No changes]         |
| Added  | **[`Comparable<T>`]** | ![No changes]         |
| Added  | **[`Constable`]**     | ![No changes]         |


#### Methods

| Status | Modifiers                 | Generics | Type                      | Method                    | Annotations | Throws | Compatibility Changes |
|--------|---------------------------|----------|---------------------------|---------------------------|-------------|--------|-----------------------|
| Added  | **`static`** **`public`** |          | **[`PhysicalType`]**      | **`valueOf`**([`String`]) |             |        | ![Method added to public class] |
| Added  | **`static`** **`public`** |          | **[`PhysicalType[]`][7]** | **`values`**()            |             |        | ![Method added to public class] |


#### Fields

| Status | Modifiers                             | Type                 | Name                   | Annotations | Compatibility Changes |
|--------|---------------------------------------|----------------------|------------------------|-------------|-----------------------|
| Added  | **`public`** **`static`** **`final`** | **[`PhysicalType`]** | `BOOLEAN`              |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`PhysicalType`]** | `BYTE_ARRAY`           |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`PhysicalType`]** | `DOUBLE`               |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`PhysicalType`]** | `FIXED_LEN_BYTE_ARRAY` |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`PhysicalType`]** | `FLOAT`                |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`PhysicalType`]** | `INT32`                |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`PhysicalType`]** | `INT64`                |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`PhysicalType`]** | `INT96`                |             | ![No changes]         |

___

<a id="user-content-dev.hardwood.metadata.repetitiontype"></a>
### `dev.hardwood.metadata.RepetitionType`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                | Type     | Name                 | Extends         | JDK        | Serialization | Compatibility Changes |
|--------|--------------------------|----------|----------------------|-----------------|------------|---------------|-----------------------|
| Added  | **`final`** **`public`** | **Enum** | **`RepetitionType`** | **[`Enum<E>`]** | **JDK 21** | ![Compatible] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface             | Compatibility Changes |
|--------|-----------------------|-----------------------|
| Added  | **[`Serializable`]**  | ![No changes]         |
| Added  | **[`Comparable<T>`]** | ![No changes]         |
| Added  | **[`Constable`]**     | ![No changes]         |


#### Methods

| Status | Modifiers                 | Generics | Type                        | Method                    | Annotations | Throws | Compatibility Changes |
|--------|---------------------------|----------|-----------------------------|---------------------------|-------------|--------|-----------------------|
| Added  | **`static`** **`public`** |          | **[`RepetitionType`]**      | **`valueOf`**([`String`]) |             |        | ![Method added to public class] |
| Added  | **`static`** **`public`** |          | **[`RepetitionType[]`][8]** | **`values`**()            |             |        | ![Method added to public class] |


#### Fields

| Status | Modifiers                             | Type                   | Name       | Annotations | Compatibility Changes |
|--------|---------------------------------------|------------------------|------------|-------------|-----------------------|
| Added  | **`public`** **`static`** **`final`** | **[`RepetitionType`]** | `OPTIONAL` |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`RepetitionType`]** | `REPEATED` |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`RepetitionType`]** | `REQUIRED` |             | ![No changes]         |

___

<a id="user-content-dev.hardwood.metadata.rowgroup"></a>
### `dev.hardwood.metadata.RowGroup`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                | Type      | Name           | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|--------------------------|-----------|----------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`public`** | **Class** | **`RowGroup`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor                                           | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-------------------------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`RowGroup`**([`List<ColumnChunk>`], `long`, `long`) |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type                      | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|---------------------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`public`**             |          | **[`List<ColumnChunk>`]** | **`columns`**()          |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`boolean`**             | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**                 | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`long`**                | **`numRows`**()          |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]**            | **`toString`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`long`**                | **`totalByteSize`**()    |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.metadata.schemaelement"></a>
### `dev.hardwood.metadata.SchemaElement`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                | Type      | Name                | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|--------------------------|-----------|---------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`public`** | **Class** | **`SchemaElement`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`SchemaElement`**([`String`], [`PhysicalType`], [`Integer`], [`RepetitionType`], [`Integer`], [`ConvertedType`], [`Integer`], [`Integer`], [`Integer`], [`LogicalType`]) |  |  | ![No changes] |


#### Methods

| Status | Modifiers                | Generics | Type                   | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|------------------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`public`**             |          | **[`ConvertedType`]**  | **`convertedType`**()    |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`boolean`**          | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`Integer`]**        | **`fieldId`**()          |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**              | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`boolean`**          | **`isGroup`**()          |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`boolean`**          | **`isPrimitive`**()      |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`LogicalType`]**    | **`logicalType`**()      |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`String`]**         | **`name`**()             |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`Integer`]**        | **`numChildren`**()      |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`Integer`]**        | **`precision`**()        |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`RepetitionType`]** | **`repetitionType`**()   |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`Integer`]**        | **`scale`**()            |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]**         | **`toString`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`PhysicalType`]**   | **`type`**()             |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`Integer`]**        | **`typeLength`**()       |             |        | ![Method added to public class] |

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

| Status | Modifiers    | Type      | Name               | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|--------------|-----------|--------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`public`** | **Class** | **`ColumnReader`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface             | Compatibility Changes |
|--------|-----------------------|-----------------------|
| Added  | **[`AutoCloseable`]** | ![No changes]         |


#### Methods

| Status | Modifiers    | Generics | Type                 | Method                        | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|----------------------|-------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`void`**           | **`close`**()                 |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **`byte[][]`**       | **`getBinaries`**()           |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **`int[]`**          | **`getBinaryOffsets`**()      |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **`byte[]`**         | **`getBinaryValues`**()       |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **`boolean[]`**      | **`getBooleans`**()           |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`ColumnSchema`]** | **`getColumnSchema`**()       |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **`int[]`**          | **`getDefinitionLevels`**()   |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **`double[]`**       | **`getDoubles`**()            |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **`float[]`**        | **`getFloats`**()             |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **`int[]`**          | **`getInts`**()               |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **`int`**            | **`getLayerCount`**()         |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`LayerKind`]**    | **`getLayerKind`**(`int`)     |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **`int[]`**          | **`getLayerOffsets`**(`int`)  |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`Validity`]**     | **`getLayerValidity`**(`int`) |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`Validity`]**     | **`getLeafValidity`**()       |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **`long[]`**         | **`getLongs`**()              |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **`int`**            | **`getRecordCount`**()        |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **`int[]`**          | **`getRepetitionLevels`**()   |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`String[]`][9]**  | **`getStrings`**()            |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **`int`**            | **`getValueCount`**()         |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **`boolean`**        | **`nextBatch`**()             |             |        | ![Method added to public class] |

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
| Added  | **`public`** |          | **`int`**            | **`getRecordCount`**()            |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **`boolean`**        | **`nextBatch`**()                 |             |        | ![Method added to public class] |

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
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`intersects`**([`String`], `double`, `double`, `double`, `double`) |  |  | ![No changes]         |
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

<a id="user-content-dev.hardwood.reader.filterpredicate$intersectspredicate"></a>
### `dev.hardwood.reader.FilterPredicate$IntersectsPredicate`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name                      | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|---------------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`IntersectsPredicate`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface               | Compatibility Changes |
|--------|-------------------------|-----------------------|
| Added  | **[`FilterPredicate`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`IntersectsPredicate`**([`String`], `double`, `double`, `double`, `double`) |  |  | ![No changes] |


#### Methods

| Status | Modifiers                | Generics | Type           | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|----------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`public`**             |          | **[`String`]** | **`column`**()           |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`boolean`**  | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**      | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]** | **`toString`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`double`**   | **`xmax`**()             |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`double`**   | **`xmin`**()             |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`double`**   | **`ymax`**()             |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`double`**   | **`ymin`**()             |             |        | ![Method added to public class] |

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

| Status | Modifiers                 | Generics | Type                   | Method                    | Annotations | Throws | Compatibility Changes |
|--------|---------------------------|----------|------------------------|---------------------------|-------------|--------|-----------------------|
| Added  | **`public`**              |          | **[`Operator`]**       | **`invert`**()            |             |        | ![Method added to public class] |
| Added  | **`static`** **`public`** |          | **[`Operator`]**       | **`valueOf`**([`String`]) |             |        | ![Method added to public class] |
| Added  | **`static`** **`public`** |          | **[`Operator[]`][10]** | **`values`**()            |             |        | ![Method added to public class] |


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

<a id="user-content-dev.hardwood.reader.layerkind"></a>
### `dev.hardwood.reader.LayerKind`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                | Type     | Name            | Extends         | JDK        | Serialization | Compatibility Changes |
|--------|--------------------------|----------|-----------------|-----------------|------------|---------------|-----------------------|
| Added  | **`final`** **`public`** | **Enum** | **`LayerKind`** | **[`Enum<E>`]** | **JDK 21** | ![Compatible] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface             | Compatibility Changes |
|--------|-----------------------|-----------------------|
| Added  | **[`Serializable`]**  | ![No changes]         |
| Added  | **[`Comparable<T>`]** | ![No changes]         |
| Added  | **[`Constable`]**     | ![No changes]         |


#### Methods

| Status | Modifiers                 | Generics | Type                    | Method                    | Annotations | Throws | Compatibility Changes |
|--------|---------------------------|----------|-------------------------|---------------------------|-------------|--------|-----------------------|
| Added  | **`static`** **`public`** |          | **[`LayerKind`]**       | **`valueOf`**([`String`]) |             |        | ![Method added to public class] |
| Added  | **`static`** **`public`** |          | **[`LayerKind[]`][11]** | **`values`**()            |             |        | ![Method added to public class] |


#### Fields

| Status | Modifiers                             | Type              | Name       | Annotations | Compatibility Changes |
|--------|---------------------------------------|-------------------|------------|-------------|-----------------------|
| Added  | **`public`** **`static`** **`final`** | **[`LayerKind`]** | `REPEATED` |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`LayerKind`]** | `STRUCT`   |             | ![No changes]         |

___

<a id="user-content-dev.hardwood.reader.parquetfilereader"></a>
### `dev.hardwood.reader.ParquetFileReader`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers    | Type      | Name                    | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|--------------|-----------|-------------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`public`** | **Class** | **`ParquetFileReader`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface             | Compatibility Changes |
|--------|-----------------------|-----------------------|
| Added  | **[`AutoCloseable`]** | ![No changes]         |


#### Methods

| Status | Modifiers                 | Generics | Type                         | Method                                         | Annotations | Throws              | Compatibility Changes |
|--------|---------------------------|----------|------------------------------|------------------------------------------------|-------------|---------------------|-----------------------|
| Added  | **`public`**              |          | **[`ColumnReaderBuilder`]**  | **`buildColumnReader`**([`String`])            |             |                     | ![Method added to public class] |
| Added  | **`public`**              |          | **[`ColumnReaderBuilder`]**  | **`buildColumnReader`**(`int`)                 |             |                     | ![Method added to public class] |
| Added  | **`public`**              |          | **[`ColumnReadersBuilder`]** | **`buildColumnReaders`**([`ColumnProjection`]) |             |                     | ![Method added to public class] |
| Added  | **`public`**              |          | **[`RowReaderBuilder`]**     | **`buildRowReader`**()                         |             |                     | ![Method added to public class] |
| Added  | **`public`**              |          | **`void`**                   | **`close`**()                                  |             | **[`IOException`]** | ![Method added to public class] |
| Added  | **`public`**              |          | **[`ColumnReader`]**         | **`columnReader`**([`String`])                 |             |                     | ![Method added to public class] |
| Added  | **`public`**              |          | **[`ColumnReader`]**         | **`columnReader`**(`int`)                      |             |                     | ![Method added to public class] |
| Added  | **`public`**              |          | **[`ColumnReaders`]**        | **`columnReaders`**([`ColumnProjection`])      |             |                     | ![Method added to public class] |
| Added  | **`public`**              |          | **[`FileMetaData`]**         | **`getFileMetaData`**()                        |             |                     | ![Method added to public class] |
| Added  | **`public`**              |          | **[`FileSchema`]**           | **`getFileSchema`**()                          |             |                     | ![Method added to public class] |
| Added  | **`public`**              |          | **`boolean`**                | **`isMultiFile`**()                            |             |                     | ![Method added to public class] |
| Added  | **`static`** **`public`** |          | **[`ParquetFileReader`]**    | **`open`**([`InputFile`])                      |             | **[`IOException`]** | ![Method added to public class] |
| Added  | **`static`** **`public`** |          | **[`ParquetFileReader`]**    | **`open`**([`InputFile`], [`HardwoodContext`]) |             | **[`IOException`]** | ![Method added to public class] |
| Added  | **`static`** **`public`** |          | **[`ParquetFileReader`]**    | **`openAll`**([`List<? extends InputFile>`])   |             | **[`IOException`]** | ![Method added to public class] |
| Added  | **`static`** **`public`** |          | **[`ParquetFileReader`]**    | **`openAll`**([`List<? extends InputFile>`], [`HardwoodContext`]) |  | **[`IOException`]** | ![Method added to public class] |
| Added  | **`public`**              |          | **[`RowReader`]**            | **`rowReader`**()                              |             |                     | ![Method added to public class] |

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

| Status | Modifiers    | Generics | Type                        | Method                              | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-----------------------------|-------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **[`ColumnReaderBuilder`]** | **`batchSize`**(`int`)              |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`ColumnReader`]**        | **`build`**()                       |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`ColumnReaderBuilder`]** | **`filter`**([`FilterPredicate`])   |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`ColumnReaderBuilder`]** | **`filter`**([`RowGroupPredicate`]) |             |        | ![Method added to public class] |

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

| Status | Modifiers    | Generics | Type                         | Method                              | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|------------------------------|-------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **[`ColumnReadersBuilder`]** | **`batchSize`**(`int`)              |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`ColumnReaders`]**        | **`build`**()                       |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`ColumnReadersBuilder`]** | **`filter`**([`FilterPredicate`])   |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`ColumnReadersBuilder`]** | **`filter`**([`RowGroupPredicate`]) |             |        | ![Method added to public class] |

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
| Added  | **`public`** |          | **[`RowReaderBuilder`]** | **`filter`**([`RowGroupPredicate`])    |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`RowReaderBuilder`]** | **`head`**(`long`)                     |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`RowReaderBuilder`]** | **`projection`**([`ColumnProjection`]) |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`RowReaderBuilder`]** | **`skip`**(`long`)                     |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`RowReaderBuilder`]** | **`tail`**(`long`)                     |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.reader.rowgrouppredicate"></a>
### `dev.hardwood.reader.RowGroupPredicate`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                   | Type          | Name                    | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|-----------------------------|---------------|-------------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`public`** **`abstract`** | **Interface** | **`RowGroupPredicate`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers                 | Generics | Type                      | Method                              | Annotations | Throws | Compatibility Changes |
|--------|---------------------------|----------|---------------------------|-------------------------------------|-------------|--------|-----------------------|
| Added  | **`static`** **`public`** |          | **[`RowGroupPredicate`]** | **`and`**([`RowGroupPredicate...`]) |             |        | ![No changes]         |
| Added  | **`static`** **`public`** |          | **[`RowGroupPredicate`]** | **`byteRange`**(`long`, `long`)     |             |        | ![No changes]         |

___

<a id="user-content-dev.hardwood.reader.rowgrouppredicate$and"></a>
### `dev.hardwood.reader.RowGroupPredicate$And`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name      | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|-----------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`And`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface                 | Compatibility Changes |
|--------|---------------------------|-----------------------|
| Added  | **[`RowGroupPredicate`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor                            | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|----------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`And`**([`List<RowGroupPredicate>`]) |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type                            | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|---------------------------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`public`**             |          | **[`List<RowGroupPredicate>`]** | **`children`**()         |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`boolean`**                   | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**                       | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]**                  | **`toString`**()         |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.reader.rowgrouppredicate$byterange"></a>
### `dev.hardwood.reader.RowGroupPredicate$ByteRange`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name            | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|-----------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`ByteRange`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface                 | Compatibility Changes |
|--------|---------------------------|-----------------------|
| Added  | **[`RowGroupPredicate`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor                     | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|---------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`ByteRange`**(`long`, `long`) |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                | Generics | Type           | Method                   | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|----------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`public`**             |          | **`long`**     | **`endExclusive`**()     |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`boolean`**  | **`equals`**([`Object`]) |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**      | **`hashCode`**()         |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`long`**     | **`startInclusive`**()   |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]** | **`toString`**()         |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.reader.rowreader"></a>
### `dev.hardwood.reader.RowReader`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                   | Type          | Name            | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|-----------------------------|---------------|-----------------|----------------|------------|---------------------|-----------------------|
| Added  | **`public`** **`abstract`** | **Interface** | **`RowReader`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface              | Compatibility Changes |
|--------|------------------------|-----------------------|
| Added  | **[`FieldAccessor`]**  | ![No changes]         |
| Added  | **[`StructAccessor`]** | ![No changes]         |
| Added  | **[`AutoCloseable`]**  | ![No changes]         |


#### Methods

| Status | Modifiers                   | Generics | Type          | Method          | Annotations | Throws | Compatibility Changes |
|--------|-----------------------------|----------|---------------|-----------------|-------------|--------|-----------------------|
| Added  | **`public`** **`abstract`** |          | **`void`**    | **`close`**()   |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`boolean`** | **`hasNext`**() |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`void`**    | **`next`**()    |             |        | ![No changes]         |

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

<a id="user-content-dev.hardwood.reader.validity"></a>
### `dev.hardwood.reader.Validity`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                   | Type          | Name           | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|-----------------------------|---------------|----------------|----------------|------------|---------------------|-----------------------|
| Added  | **`public`** **`abstract`** | **Interface** | **`Validity`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers                   | Generics | Type             | Method                          | Annotations | Throws | Compatibility Changes |
|--------|-----------------------------|----------|------------------|---------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** **`abstract`** |          | **`boolean`**    | **`hasNulls`**()                |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`boolean`**    | **`isNotNull`**(`int`)          |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`boolean`**    | **`isNull`**(`int`)             |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`int`**        | **`nextNotNull`**(`int`, `int`) |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`int`**        | **`nextNull`**(`int`, `int`)    |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`int`**        | **`nullCount`**(`int`)          |             |        | ![No changes]         |
| Added  | **`static`** **`public`**   |          | **[`Validity`]** | **`of`**(`long[]`)              |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`long[]`**     | **`words`**()                   |             |        | ![No changes]         |


#### Fields

| Status | Modifiers                             | Type             | Name       | Annotations | Compatibility Changes |
|--------|---------------------------------------|------------------|------------|-------------|-----------------------|
| Added  | **`public`** **`static`** **`final`** | **[`Validity`]** | `NO_NULLS` |             | ![No changes]         |

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

| Status | Modifiers                   | Generics | Type                  | Method                              | Annotations | Throws | Compatibility Changes |
|--------|-----------------------------|----------|-----------------------|-------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** **`abstract`** |          | **`byte[]`**          | **`getBinary`**([`String`])         |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`boolean`**         | **`getBoolean`**([`String`])        |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`LocalDate`]**     | **`getDate`**([`String`])           |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`BigDecimal`]**    | **`getDecimal`**([`String`])        |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`double`**          | **`getDouble`**([`String`])         |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`int`**             | **`getFieldCount`**()               |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`String`]**        | **`getFieldName`**(`int`)           |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`float`**           | **`getFloat`**([`String`])          |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`int`**             | **`getInt`**([`String`])            |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`PqInterval`]**    | **`getInterval`**([`String`])       |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`LocalDateTime`]** | **`getLocalTimestamp`**([`String`]) |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`long`**            | **`getLong`**([`String`])           |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`Object`]**        | **`getRawValue`**([`String`])       |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`String`]**        | **`getString`**([`String`])         |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`LocalTime`]**     | **`getTime`**([`String`])           |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`Instant`]**       | **`getTimestamp`**([`String`])      |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`UUID`]**          | **`getUuid`**([`String`])           |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`Object`]**        | **`getValue`**([`String`])          |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`PqVariant`]**     | **`getVariant`**([`String`])        |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`boolean`**         | **`isNull`**([`String`])            |             |        | ![No changes]         |

___

<a id="user-content-dev.hardwood.row.pqdoublelist"></a>
### `dev.hardwood.row.PqDoubleList`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                   | Type          | Name               | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|-----------------------------|---------------|--------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`public`** **`abstract`** | **Interface** | **`PqDoubleList`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers                   | Generics | Type             | Method                            | Annotations | Throws | Compatibility Changes |
|--------|-----------------------------|----------|------------------|-----------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** **`abstract`** |          | **`void`**       | **`forEach`**([`DoubleConsumer`]) |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`double`**     | **`get`**(`int`)                  |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`boolean`**    | **`isEmpty`**()                   |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`boolean`**    | **`isNull`**(`int`)               |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`OfDouble`]** | **`iterator`**()                  |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`int`**        | **`size`**()                      |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`double[]`**   | **`toArray`**()                   |             |        | ![No changes]         |

___

<a id="user-content-dev.hardwood.row.pqintlist"></a>
### `dev.hardwood.row.PqIntList`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                   | Type          | Name            | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|-----------------------------|---------------|-----------------|----------------|------------|---------------------|-----------------------|
| Added  | **`public`** **`abstract`** | **Interface** | **`PqIntList`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers                   | Generics | Type          | Method                         | Annotations | Throws | Compatibility Changes |
|--------|-----------------------------|----------|---------------|--------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** **`abstract`** |          | **`void`**    | **`forEach`**([`IntConsumer`]) |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`int`**     | **`get`**(`int`)               |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`boolean`** | **`isEmpty`**()                |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`boolean`** | **`isNull`**(`int`)            |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`OfInt`]** | **`iterator`**()               |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`int`**     | **`size`**()                   |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`int[]`**   | **`toArray`**()                |             |        | ![No changes]         |

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

<a id="user-content-dev.hardwood.row.pqlist"></a>
### `dev.hardwood.row.PqList`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                   | Type          | Name         | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|-----------------------------|---------------|--------------|----------------|------------|---------------------|-----------------------|
| Added  | **`public`** **`abstract`** | **Interface** | **`PqList`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers                   | Generics | Type                        | Method                  | Annotations | Throws | Compatibility Changes |
|--------|-----------------------------|----------|-----------------------------|-------------------------|-------------|--------|-----------------------|
| Added  | **`public`** **`abstract`** |          | **[`List`]**                | **`binaries`**()        |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`List<Boolean>`]**       | **`booleans`**()        |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`List<LocalDate>`]**     | **`dates`**()           |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`List<BigDecimal>`]**    | **`decimals`**()        |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`PqDoubleList`]**        | **`doubles`**()         |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`List<Float>`]**         | **`floats`**()          |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`Object`]**              | **`get`**(`int`)        |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`Object`]**              | **`getRaw`**(`int`)     |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`List<PqInterval>`]**    | **`intervals`**()       |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`PqIntList`]**           | **`ints`**()            |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`boolean`**               | **`isEmpty`**()         |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`boolean`**               | **`isNull`**(`int`)     |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`List<PqList>`]**        | **`lists`**()           |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`List<LocalDateTime>`]** | **`localTimestamps`**() |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`PqLongList`]**          | **`longs`**()           |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`List<PqMap>`]**         | **`maps`**()            |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`List<Object>`]**        | **`rawValues`**()       |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`int`**                   | **`size`**()            |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`List<String>`]**        | **`strings`**()         |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`List<PqStruct>`]**      | **`structs`**()         |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`List<LocalTime>`]**     | **`times`**()           |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`List<Instant>`]**       | **`timestamps`**()      |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`List<UUID>`]**          | **`uuids`**()           |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`List<Object>`]**        | **`values`**()          |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`List<PqVariant>`]**     | **`variants`**()        |             |        | ![No changes]         |

___

<a id="user-content-dev.hardwood.row.pqlonglist"></a>
### `dev.hardwood.row.PqLongList`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                   | Type          | Name             | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|-----------------------------|---------------|------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`public`** **`abstract`** | **Interface** | **`PqLongList`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers                   | Generics | Type           | Method                          | Annotations | Throws | Compatibility Changes |
|--------|-----------------------------|----------|----------------|---------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** **`abstract`** |          | **`void`**     | **`forEach`**([`LongConsumer`]) |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`long`**     | **`get`**(`int`)                |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`boolean`**  | **`isEmpty`**()                 |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`boolean`**  | **`isNull`**(`int`)             |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`OfLong`]** | **`iterator`**()                |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`int`**      | **`size`**()                    |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`long[]`**   | **`toArray`**()                 |             |        | ![No changes]         |

___

<a id="user-content-dev.hardwood.row.pqmap"></a>
### `dev.hardwood.row.PqMap`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                   | Type          | Name        | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|-----------------------------|---------------|-------------|----------------|------------|---------------------|-----------------------|
| Added  | **`public`** **`abstract`** | **Interface** | **`PqMap`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers                   | Generics | Type                | Method                        | Annotations | Throws | Compatibility Changes |
|--------|-----------------------------|----------|---------------------|-------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** **`abstract`** |          | **`boolean`**       | **`containsKey`**([`String`]) |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`boolean`**       | **`containsKey`**(`int`)      |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`boolean`**       | **`containsKey`**(`long`)     |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`boolean`**       | **`containsKey`**(`byte[]`)   |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`List<Entry>`]** | **`getEntries`**()            |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`Object`]**      | **`getRawValue`**([`String`]) |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`Object`]**      | **`getRawValue`**(`int`)      |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`Object`]**      | **`getRawValue`**(`long`)     |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`Object`]**      | **`getRawValue`**(`byte[]`)   |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`Object`]**      | **`getValue`**([`String`])    |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`Object`]**      | **`getValue`**(`int`)         |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`Object`]**      | **`getValue`**(`long`)        |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`Object`]**      | **`getValue`**(`byte[]`)      |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`boolean`**       | **`isEmpty`**()               |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`int`**           | **`size`**()                  |             |        | ![No changes]         |

___

<a id="user-content-dev.hardwood.row.pqmap$entry"></a>
### `dev.hardwood.row.PqMap$Entry`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                                | Type          | Name        | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|------------------------------------------|---------------|-------------|----------------|------------|---------------------|-----------------------|
| Added  | **`static`** **`public`** **`abstract`** | **Interface** | **`Entry`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers                   | Generics | Type                  | Method                         | Annotations | Throws | Compatibility Changes |
|--------|-----------------------------|----------|-----------------------|--------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** **`abstract`** |          | **`byte[]`**          | **`getBinaryKey`**()           |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`byte[]`**          | **`getBinaryValue`**()         |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`boolean`**         | **`getBooleanValue`**()        |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`LocalDate`]**     | **`getDateValue`**()           |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`BigDecimal`]**    | **`getDecimalValue`**()        |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`double`**          | **`getDoubleValue`**()         |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`float`**           | **`getFloatValue`**()          |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`int`**             | **`getIntKey`**()              |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`int`**             | **`getIntValue`**()            |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`PqInterval`]**    | **`getIntervalValue`**()       |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`Object`]**        | **`getKey`**()                 |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`PqList`]**        | **`getListValue`**()           |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`LocalDateTime`]** | **`getLocalTimestampValue`**() |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`long`**            | **`getLongKey`**()             |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`long`**            | **`getLongValue`**()           |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`PqMap`]**         | **`getMapValue`**()            |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`Object`]**        | **`getRawKey`**()              |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`Object`]**        | **`getRawValue`**()            |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`String`]**        | **`getStringKey`**()           |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`String`]**        | **`getStringValue`**()         |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`PqStruct`]**      | **`getStructValue`**()         |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`LocalTime`]**     | **`getTimeValue`**()           |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`Instant`]**       | **`getTimestampValue`**()      |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`UUID`]**          | **`getUuidValue`**()           |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`Object`]**        | **`getValue`**()               |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`PqVariant`]**     | **`getVariantValue`**()        |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`boolean`**         | **`isValueNull`**()            |             |        | ![No changes]         |

___

<a id="user-content-dev.hardwood.row.pqstruct"></a>
### `dev.hardwood.row.PqStruct`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                   | Type          | Name           | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|-----------------------------|---------------|----------------|----------------|------------|---------------------|-----------------------|
| Added  | **`public`** **`abstract`** | **Interface** | **`PqStruct`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface              | Compatibility Changes |
|--------|------------------------|-----------------------|
| Added  | **[`FieldAccessor`]**  | ![No changes]         |
| Added  | **[`StructAccessor`]** | ![No changes]         |

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

| Status | Modifiers                   | Generics | Type                    | Method                   | Annotations | Throws | Compatibility Changes |
|--------|-----------------------------|----------|-------------------------|--------------------------|-------------|--------|-----------------------|
| Added  | **`public`** **`abstract`** |          | **[`PqVariantArray`]**  | **`asArray`**()          |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`byte[]`**            | **`asBinary`**()         |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`boolean`**           | **`asBoolean`**()        |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`LocalDate`]**       | **`asDate`**()           |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`BigDecimal`]**      | **`asDecimal`**()        |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`double`**            | **`asDouble`**()         |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`float`**             | **`asFloat`**()          |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`int`**               | **`asInt`**()            |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`LocalDateTime`]**   | **`asLocalTimestamp`**() |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`long`**              | **`asLong`**()           |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`PqVariantObject`]** | **`asObject`**()         |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`String`]**          | **`asString`**()         |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`LocalTime`]**       | **`asTime`**()           |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`Instant`]**         | **`asTimestamp`**()      |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`UUID`]**            | **`asUuid`**()           |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`boolean`**           | **`isNull`**()           |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`byte[]`**            | **`metadata`**()         |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`VariantType`]**     | **`type`**()             |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`byte[]`**            | **`value`**()            |             |        | ![No changes]         |

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

| Status | Modifiers                   | Type          | Name                 | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|-----------------------------|---------------|----------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`public`** **`abstract`** | **Interface** | **`StructAccessor`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface             | Compatibility Changes |
|--------|-----------------------|-----------------------|
| Added  | **[`FieldAccessor`]** | ![No changes]         |


#### Methods

| Status | Modifiers                   | Generics | Type                  | Method                         | Annotations | Throws | Compatibility Changes |
|--------|-----------------------------|----------|-----------------------|--------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** **`abstract`** |          | **`byte[]`**          | **`getBinary`**(`int`)         |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`boolean`**         | **`getBoolean`**(`int`)        |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`LocalDate`]**     | **`getDate`**(`int`)           |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`BigDecimal`]**    | **`getDecimal`**(`int`)        |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`double`**          | **`getDouble`**(`int`)         |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`float`**           | **`getFloat`**(`int`)          |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`int`**             | **`getInt`**(`int`)            |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`PqInterval`]**    | **`getInterval`**(`int`)       |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`PqList`]**        | **`getList`**([`String`])      |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`PqList`]**        | **`getList`**(`int`)           |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`LocalDateTime`]** | **`getLocalTimestamp`**(`int`) |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`long`**            | **`getLong`**(`int`)           |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`PqMap`]**         | **`getMap`**([`String`])       |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`PqMap`]**         | **`getMap`**(`int`)            |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`Object`]**        | **`getRawValue`**(`int`)       |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`String`]**        | **`getString`**(`int`)         |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`PqStruct`]**      | **`getStruct`**([`String`])    |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`PqStruct`]**      | **`getStruct`**(`int`)         |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`LocalTime`]**     | **`getTime`**(`int`)           |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`Instant`]**       | **`getTimestamp`**(`int`)      |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`UUID`]**          | **`getUuid`**(`int`)           |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`Object`]**        | **`getValue`**(`int`)          |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`PqVariant`]**     | **`getVariant`**(`int`)        |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`boolean`**         | **`isNull`**(`int`)            |             |        | ![No changes]         |

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

| Status | Modifiers                 | Generics | Type                      | Method                    | Annotations | Throws | Compatibility Changes |
|--------|---------------------------|----------|---------------------------|---------------------------|-------------|--------|-----------------------|
| Added  | **`static`** **`public`** |          | **[`VariantType`]**       | **`valueOf`**([`String`]) |             |        | ![Method added to public class] |
| Added  | **`static`** **`public`** |          | **[`VariantType[]`][12]** | **`values`**()            |             |        | ![Method added to public class] |


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

___

<a id="user-content-dev.hardwood.schema.columnprojection"></a>
### `dev.hardwood.schema.ColumnProjection`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                | Type      | Name                   | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|--------------------------|-----------|------------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`public`** | **Class** | **`ColumnProjection`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers                 | Generics | Type                     | Method                          | Annotations | Throws | Compatibility Changes |
|--------|---------------------------|----------|--------------------------|---------------------------------|-------------|--------|-----------------------|
| Added  | **`static`** **`public`** |          | **[`ColumnProjection`]** | **`all`**()                     |             |        | ![Method added to public class] |
| Added  | **`static`** **`public`** |          | **[`ColumnProjection`]** | **`columns`**([`String...`])    |             |        | ![Method added to public class] |
| Added  | **`public`**              |          | **[`Set<String>`]**      | **`getProjectedColumnNames`**() |             |        | ![Method added to public class] |
| Added  | **`public`**              |          | **`boolean`**            | **`projectsAll`**()             |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.schema.columnschema"></a>
### `dev.hardwood.schema.ColumnSchema`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                | Type      | Name               | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|--------------------------|-----------|--------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`public`** | **Class** | **`ColumnSchema`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`ColumnSchema`**([`FieldPath`], [`PhysicalType`], [`RepetitionType`], [`Integer`], `int`, `int`, `int`, [`LogicalType`]) |  |  | ![No changes] |


#### Methods

| Status | Modifiers                | Generics | Type                   | Method                     | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|------------------------|----------------------------|-------------|--------|-----------------------|
| Added  | **`public`**             |          | **`int`**              | **`columnIndex`**()        |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`boolean`**          | **`equals`**([`Object`])   |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`FieldPath`]**      | **`fieldPath`**()          |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**              | **`hashCode`**()           |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`LogicalType`]**    | **`logicalType`**()        |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`int`**              | **`maxDefinitionLevel`**() |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`int`**              | **`maxRepetitionLevel`**() |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`String`]**         | **`name`**()               |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`RepetitionType`]** | **`repetitionType`**()     |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`String`]**         | **`toString`**()           |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`PhysicalType`]**   | **`type`**()               |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`Integer`]**        | **`typeLength`**()         |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.schema.fileschema"></a>
### `dev.hardwood.schema.FileSchema`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers    | Type      | Name             | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|--------------|-----------|------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`public`** | **Class** | **`FileSchema`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers                 | Generics | Type                       | Method                                            | Annotations | Throws | Compatibility Changes |
|--------|---------------------------|----------|----------------------------|---------------------------------------------------|-------------|--------|-----------------------|
| Added  | **`static`** **`public`** |          | **[`FileSchema`]**         | **`fromSchemaElements`**([`List<SchemaElement>`]) |             |        | ![Method added to public class] |
| Added  | **`public`**              |          | **[`ColumnSchema`]**       | **`getColumn`**(`int`)                            |             |        | ![Method added to public class] |
| Added  | **`public`**              |          | **[`ColumnSchema`]**       | **`getColumn`**([`String`])                       |             |        | ![Method added to public class] |
| Added  | **`public`**              |          | **[`ColumnSchema`]**       | **`getColumn`**([`FieldPath`])                    |             |        | ![Method added to public class] |
| Added  | **`public`**              |          | **`int`**                  | **`getColumnCount`**()                            |             |        | ![Method added to public class] |
| Added  | **`public`**              |          | **[`List<ColumnSchema>`]** | **`getColumns`**()                                |             |        | ![Method added to public class] |
| Added  | **`public`**              |          | **[`SchemaNode`]**         | **`getField`**([`String`])                        |             |        | ![Method added to public class] |
| Added  | **`public`**              |          | **[`String`]**             | **`getName`**()                                   |             |        | ![Method added to public class] |
| Added  | **`public`**              |          | **[`GroupNode`]**          | **`getRootNode`**()                               |             |        | ![Method added to public class] |
| Added  | **`public`**              |          | **`boolean`**              | **`isFlatSchema`**()                              |             |        | ![Method added to public class] |
| Added  | **`public`**              |          | **[`String`]**             | **`toString`**()                                  |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.schema.schemanode"></a>
### `dev.hardwood.schema.SchemaNode`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                   | Type          | Name             | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|-----------------------------|---------------|------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`public`** **`abstract`** | **Interface** | **`SchemaNode`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers                   | Generics | Type                   | Method                     | Annotations | Throws | Compatibility Changes |
|--------|-----------------------------|----------|------------------------|----------------------------|-------------|--------|-----------------------|
| Added  | **`public`** **`abstract`** |          | **`int`**              | **`maxDefinitionLevel`**() |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **`int`**              | **`maxRepetitionLevel`**() |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`String`]**         | **`name`**()               |             |        | ![No changes]         |
| Added  | **`public`** **`abstract`** |          | **[`RepetitionType`]** | **`repetitionType`**()     |             |        | ![No changes]         |

___

<a id="user-content-dev.hardwood.schema.schemanode$groupnode"></a>
### `dev.hardwood.schema.SchemaNode$GroupNode`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name            | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|-----------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`GroupNode`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface          | Compatibility Changes |
|--------|--------------------|-----------------------|
| Added  | **[`SchemaNode`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`GroupNode`**([`String`], [`RepetitionType`], [`ConvertedType`], [`LogicalType`], [`List<SchemaNode>`], `int`, `int`) |  |  | ![No changes] |


#### Methods

| Status | Modifiers                | Generics | Type                     | Method                     | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|--------------------------|----------------------------|-------------|--------|-----------------------|
| Added  | **`public`**             |          | **[`List<SchemaNode>`]** | **`children`**()           |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`ConvertedType`]**    | **`convertedType`**()      |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`boolean`**            | **`equals`**([`Object`])   |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`SchemaNode`]**       | **`getListElement`**()     |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`SchemaNode`]**       | **`getMapKey`**()          |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`SchemaNode`]**       | **`getMapValue`**()        |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**                | **`hashCode`**()           |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`boolean`**            | **`isList`**()             |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`boolean`**            | **`isMap`**()              |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`boolean`**            | **`isStruct`**()           |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`boolean`**            | **`isVariant`**()          |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`LogicalType`]**      | **`logicalType`**()        |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`int`**                | **`maxDefinitionLevel`**() |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`int`**                | **`maxRepetitionLevel`**() |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`String`]**           | **`name`**()               |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`RepetitionType`]**   | **`repetitionType`**()     |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]**           | **`toString`**()           |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.schema.schemanode$primitivenode"></a>
### `dev.hardwood.schema.SchemaNode$PrimitiveNode`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name                | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|---------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`PrimitiveNode`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface          | Compatibility Changes |
|--------|--------------------|-----------------------|
| Added  | **[`SchemaNode`]** | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`PrimitiveNode`**([`String`], [`PhysicalType`], [`RepetitionType`], [`LogicalType`], `int`, `int`, `int`) |  |  | ![No changes] |


#### Methods

| Status | Modifiers                | Generics | Type                   | Method                     | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|------------------------|----------------------------|-------------|--------|-----------------------|
| Added  | **`public`**             |          | **`int`**              | **`columnIndex`**()        |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`boolean`**          | **`equals`**([`Object`])   |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**              | **`hashCode`**()           |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`LogicalType`]**    | **`logicalType`**()        |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`int`**              | **`maxDefinitionLevel`**() |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **`int`**              | **`maxRepetitionLevel`**() |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`String`]**         | **`name`**()               |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`RepetitionType`]** | **`repetitionType`**()     |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]**         | **`toString`**()           |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`PhysicalType`]**   | **`type`**()               |             |        | ![Method added to public class] |


</details>


___

*Generated on: 2026-06-07 19:06:21.614+0000*.

[1]: # "dev.hardwood.metadata.ColumnIndex$BoundaryOrder[]"
[2]: # "dev.hardwood.metadata.CompressionCodec[]"
[3]: # "dev.hardwood.metadata.ConvertedType[]"
[4]: # "dev.hardwood.metadata.Encoding[]"
[5]: # "dev.hardwood.metadata.LogicalType$EdgeInterpolationAlgorithm[]"
[6]: # "dev.hardwood.metadata.LogicalType$TimeUnit[]"
[7]: # "dev.hardwood.metadata.PhysicalType[]"
[8]: # "dev.hardwood.metadata.RepetitionType[]"
[9]: # "java.lang.String[]"
[10]: # "dev.hardwood.reader.FilterPredicate$Operator[]"
[11]: # "dev.hardwood.reader.LayerKind[]"
[12]: # "dev.hardwood.row.VariantType[]"
[Annotation added]: https://img.shields.io/badge/Annotation_added-yellow "Annotation added"
[Compatible]: https://img.shields.io/badge/Compatible-green "Compatible"
[Interface added]: https://img.shields.io/badge/Interface_added-orange "Interface added"
[Method added to public class]: https://img.shields.io/badge/Method_added_to_public_class-yellow "Method added to public class"
[No changes]: https://img.shields.io/badge/No_changes-green "No changes"
[Not serializable]: https://img.shields.io/badge/Not_serializable-green "Not serializable"
[`Annotation`]: # "java.lang.annotation.Annotation"
[`AutoCloseable`]: # "java.lang.AutoCloseable"
[`BigDecimal`]: # "java.math.BigDecimal"
[`BoundaryOrder`]: # "dev.hardwood.metadata.ColumnIndex$BoundaryOrder"
[`BoundingBox`]: # "dev.hardwood.metadata.BoundingBox"
[`ByteBuffer...`]: # "java.nio.ByteBuffer..."
[`ByteBuffer`]: # "java.nio.ByteBuffer"
[`CLASS`]: # "java.lang.annotation.RetentionPolicy.CLASS"
[`Category`]: # "jdk.jfr.Category"
[`Closeable`]: # "java.io.Closeable"
[`ColumnMetaData`]: # "dev.hardwood.metadata.ColumnMetaData"
[`ColumnProjection`]: # "dev.hardwood.schema.ColumnProjection"
[`ColumnReaderBuilder`]: # "dev.hardwood.reader.ParquetFileReader$ColumnReaderBuilder"
[`ColumnReader`]: # "dev.hardwood.reader.ColumnReader"
[`ColumnReadersBuilder`]: # "dev.hardwood.reader.ParquetFileReader$ColumnReadersBuilder"
[`ColumnReaders`]: # "dev.hardwood.reader.ColumnReaders"
[`ColumnSchema`]: # "dev.hardwood.schema.ColumnSchema"
[`Comparable<T>`]: # "java.lang.Comparable<T extends java.lang.Object>"
[`CompressionCodec`]: # "dev.hardwood.metadata.CompressionCodec"
[`Constable`]: # "java.lang.constant.Constable"
[`ConvertedType`]: # "dev.hardwood.metadata.ConvertedType"
[`DataAmount`]: # "jdk.jfr.DataAmount"
[`Description`]: # "jdk.jfr.Description"
[`Documented`]: # "java.lang.annotation.Documented"
[`DoubleConsumer`]: # "java.util.function.DoubleConsumer"
[`Double`]: # "java.lang.Double"
[`EdgeInterpolationAlgorithm`]: # "dev.hardwood.metadata.LogicalType$EdgeInterpolationAlgorithm"
[`Encoding`]: # "dev.hardwood.metadata.Encoding"
[`Enum<E>`]: # "java.lang.Enum<E extends java.lang.Enum<E>>"
[`Event`]: # "jdk.jfr.Event"
[`ExecutorService`]: # "java.util.concurrent.ExecutorService"
[`FieldAccessor`]: # "dev.hardwood.row.FieldAccessor"
[`FieldPath`]: # "dev.hardwood.metadata.FieldPath"
[`FileMetaData`]: # "dev.hardwood.metadata.FileMetaData"
[`FileSchema`]: # "dev.hardwood.schema.FileSchema"
[`FilterPredicate...`]: # "dev.hardwood.reader.FilterPredicate..."
[`FilterPredicate`]: # "dev.hardwood.reader.FilterPredicate"
[`GeospatialStatistics`]: # "dev.hardwood.metadata.GeospatialStatistics"
[`GroupNode`]: # "dev.hardwood.schema.SchemaNode$GroupNode"
[`HardwoodContext`]: # "dev.hardwood.HardwoodContext"
[`Hardwood`]: # "dev.hardwood.Hardwood"
[`IOException`]: # "java.io.IOException"
[`InputFile`]: # "dev.hardwood.InputFile"
[`Instant`]: # "java.time.Instant"
[`IntConsumer`]: # "java.util.function.IntConsumer"
[`Integer`]: # "java.lang.Integer"
[`Iterable<T>`]: # "java.lang.Iterable<T extends java.lang.Object>"
[`Iterator<PqVariant>`]: # "java.util.Iterator<dev.hardwood.row.PqVariant>"
[`Label`]: # "jdk.jfr.Label"
[`LayerKind`]: # "dev.hardwood.reader.LayerKind"
[`List<? extends InputFile>`]: # "java.util.List<? extends dev.hardwood.InputFile>"
[`List<BigDecimal>`]: # "java.util.List<java.math.BigDecimal>"
[`List<Boolean>`]: # "java.util.List<java.lang.Boolean>"
[`List<ByteBuffer>`]: # "java.util.List<java.nio.ByteBuffer>"
[`List<ColumnChunk>`]: # "java.util.List<dev.hardwood.metadata.ColumnChunk>"
[`List<ColumnSchema>`]: # "java.util.List<dev.hardwood.schema.ColumnSchema>"
[`List<Encoding>`]: # "java.util.List<dev.hardwood.metadata.Encoding>"
[`List<Entry>`]: # "java.util.List<dev.hardwood.row.PqMap$Entry>"
[`List<FilterPredicate>`]: # "java.util.List<dev.hardwood.reader.FilterPredicate>"
[`List<Float>`]: # "java.util.List<java.lang.Float>"
[`List<InputFile>`]: # "java.util.List<dev.hardwood.InputFile>"
[`List<Instant>`]: # "java.util.List<java.time.Instant>"
[`List<Integer>`]: # "java.util.List<java.lang.Integer>"
[`List<LocalDate>`]: # "java.util.List<java.time.LocalDate>"
[`List<LocalDateTime>`]: # "java.util.List<java.time.LocalDateTime>"
[`List<LocalTime>`]: # "java.util.List<java.time.LocalTime>"
[`List<Long>`]: # "java.util.List<java.lang.Long>"
[`List<Object>`]: # "java.util.List<java.lang.Object>"
[`List<PageLocation>`]: # "java.util.List<dev.hardwood.metadata.PageLocation>"
[`List<Path>`]: # "java.util.List<java.nio.file.Path>"
[`List<PqInterval>`]: # "java.util.List<dev.hardwood.row.PqInterval>"
[`List<PqList>`]: # "java.util.List<dev.hardwood.row.PqList>"
[`List<PqMap>`]: # "java.util.List<dev.hardwood.row.PqMap>"
[`List<PqStruct>`]: # "java.util.List<dev.hardwood.row.PqStruct>"
[`List<PqVariant>`]: # "java.util.List<dev.hardwood.row.PqVariant>"
[`List<RowGroup>`]: # "java.util.List<dev.hardwood.metadata.RowGroup>"
[`List<RowGroupPredicate>`]: # "java.util.List<dev.hardwood.reader.RowGroupPredicate>"
[`List<SchemaElement>`]: # "java.util.List<dev.hardwood.metadata.SchemaElement>"
[`List<SchemaNode>`]: # "java.util.List<dev.hardwood.schema.SchemaNode>"
[`List<String>`]: # "java.util.List<java.lang.String>"
[`List<UUID>`]: # "java.util.List<java.util.UUID>"
[`List`]: # "java.util.List"
[`LocalDateTime`]: # "java.time.LocalDateTime"
[`LocalDate`]: # "java.time.LocalDate"
[`LocalTime`]: # "java.time.LocalTime"
[`LogicalType`]: # "dev.hardwood.metadata.LogicalType"
[`LongConsumer`]: # "java.util.function.LongConsumer"
[`Long`]: # "java.lang.Long"
[`Map<String, String>`]: # "java.util.Map<java.lang.String, java.lang.String>"
[`Name`]: # "jdk.jfr.Name"
[`Object`]: # "java.lang.Object"
[`OfDouble`]: # "java.util.PrimitiveIterator$OfDouble"
[`OfInt`]: # "java.util.PrimitiveIterator$OfInt"
[`OfLong`]: # "java.util.PrimitiveIterator$OfLong"
[`Operator`]: # "dev.hardwood.reader.FilterPredicate$Operator"
[`ParquetFileReader`]: # "dev.hardwood.reader.ParquetFileReader"
[`Path...`]: # "java.nio.file.Path..."
[`Path`]: # "java.nio.file.Path"
[`PhysicalType`]: # "dev.hardwood.metadata.PhysicalType"
[`PqDoubleList`]: # "dev.hardwood.row.PqDoubleList"
[`PqIntList`]: # "dev.hardwood.row.PqIntList"
[`PqInterval`]: # "dev.hardwood.row.PqInterval"
[`PqList`]: # "dev.hardwood.row.PqList"
[`PqLongList`]: # "dev.hardwood.row.PqLongList"
[`PqMap`]: # "dev.hardwood.row.PqMap"
[`PqStruct`]: # "dev.hardwood.row.PqStruct"
[`PqVariantArray`]: # "dev.hardwood.row.PqVariantArray"
[`PqVariantObject`]: # "dev.hardwood.row.PqVariantObject"
[`PqVariant`]: # "dev.hardwood.row.PqVariant"
[`Record`]: # "java.lang.Record"
[`RepetitionType`]: # "dev.hardwood.metadata.RepetitionType"
[`Retention`]: # "java.lang.annotation.Retention"
[`RowGroupPredicate...`]: # "dev.hardwood.reader.RowGroupPredicate..."
[`RowGroupPredicate`]: # "dev.hardwood.reader.RowGroupPredicate"
[`RowReaderBuilder`]: # "dev.hardwood.reader.ParquetFileReader$RowReaderBuilder"
[`RowReader`]: # "dev.hardwood.reader.RowReader"
[`RuntimeException`]: # "java.lang.RuntimeException"
[`SchemaNode`]: # "dev.hardwood.schema.SchemaNode"
[`Serializable`]: # "java.io.Serializable"
[`Set<String>`]: # "java.util.Set<java.lang.String>"
[`StackTrace`]: # "jdk.jfr.StackTrace"
[`Statistics`]: # "dev.hardwood.metadata.Statistics"
[`String...`]: # "java.lang.String..."
[`String`]: # "java.lang.String"
[`StructAccessor`]: # "dev.hardwood.row.StructAccessor"
[`Target`]: # "java.lang.annotation.Target"
[`TimeUnit`]: # "dev.hardwood.metadata.LogicalType$TimeUnit"
[`UUID`]: # "java.util.UUID"
[`Validity`]: # "dev.hardwood.reader.Validity"
[`VariantType`]: # "dev.hardwood.row.VariantType"
[`{TYPE, METHOD, CONSTRUCTOR, FIELD}`]: # "{java.lang.annotation.ElementType.TYPE, java.lang.annotation.ElementType.METHOD, java.lang.annotation.ElementType.CONSTRUCTOR, java.lang.annotation.ElementType.FIELD}"
[dev.hardwood.Experimental]: #user-content-dev.hardwood.experimental
[dev.hardwood.Hardwood]: #user-content-dev.hardwood.hardwood
[dev.hardwood.HardwoodContext]: #user-content-dev.hardwood.hardwoodcontext
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
[dev.hardwood.metadata.BoundingBox]: #user-content-dev.hardwood.metadata.boundingbox
[dev.hardwood.metadata.ColumnChunk]: #user-content-dev.hardwood.metadata.columnchunk
[dev.hardwood.metadata.ColumnIndex]: #user-content-dev.hardwood.metadata.columnindex
[dev.hardwood.metadata.ColumnIndex$BoundaryOrder]: #user-content-dev.hardwood.metadata.columnindex$boundaryorder
[dev.hardwood.metadata.ColumnMetaData]: #user-content-dev.hardwood.metadata.columnmetadata
[dev.hardwood.metadata.CompressionCodec]: #user-content-dev.hardwood.metadata.compressioncodec
[dev.hardwood.metadata.ConvertedType]: #user-content-dev.hardwood.metadata.convertedtype
[dev.hardwood.metadata.Encoding]: #user-content-dev.hardwood.metadata.encoding
[dev.hardwood.metadata.FieldPath]: #user-content-dev.hardwood.metadata.fieldpath
[dev.hardwood.metadata.FileMetaData]: #user-content-dev.hardwood.metadata.filemetadata
[dev.hardwood.metadata.GeospatialStatistics]: #user-content-dev.hardwood.metadata.geospatialstatistics
[dev.hardwood.metadata.LogicalType]: #user-content-dev.hardwood.metadata.logicaltype
[dev.hardwood.metadata.LogicalType$BsonType]: #user-content-dev.hardwood.metadata.logicaltype$bsontype
[dev.hardwood.metadata.LogicalType$DateType]: #user-content-dev.hardwood.metadata.logicaltype$datetype
[dev.hardwood.metadata.LogicalType$DecimalType]: #user-content-dev.hardwood.metadata.logicaltype$decimaltype
[dev.hardwood.metadata.LogicalType$EdgeInterpolationAlgorithm]: #user-content-dev.hardwood.metadata.logicaltype$edgeinterpolationalgorithm
[dev.hardwood.metadata.LogicalType$EnumType]: #user-content-dev.hardwood.metadata.logicaltype$enumtype
[dev.hardwood.metadata.LogicalType$Float16Type]: #user-content-dev.hardwood.metadata.logicaltype$float16type
[dev.hardwood.metadata.LogicalType$GeographyType]: #user-content-dev.hardwood.metadata.logicaltype$geographytype
[dev.hardwood.metadata.LogicalType$GeometryType]: #user-content-dev.hardwood.metadata.logicaltype$geometrytype
[dev.hardwood.metadata.LogicalType$IntType]: #user-content-dev.hardwood.metadata.logicaltype$inttype
[dev.hardwood.metadata.LogicalType$IntervalType]: #user-content-dev.hardwood.metadata.logicaltype$intervaltype
[dev.hardwood.metadata.LogicalType$JsonType]: #user-content-dev.hardwood.metadata.logicaltype$jsontype
[dev.hardwood.metadata.LogicalType$ListType]: #user-content-dev.hardwood.metadata.logicaltype$listtype
[dev.hardwood.metadata.LogicalType$MapType]: #user-content-dev.hardwood.metadata.logicaltype$maptype
[dev.hardwood.metadata.LogicalType$NullType]: #user-content-dev.hardwood.metadata.logicaltype$nulltype
[dev.hardwood.metadata.LogicalType$StringType]: #user-content-dev.hardwood.metadata.logicaltype$stringtype
[dev.hardwood.metadata.LogicalType$TimeType]: #user-content-dev.hardwood.metadata.logicaltype$timetype
[dev.hardwood.metadata.LogicalType$TimeUnit]: #user-content-dev.hardwood.metadata.logicaltype$timeunit
[dev.hardwood.metadata.LogicalType$TimestampType]: #user-content-dev.hardwood.metadata.logicaltype$timestamptype
[dev.hardwood.metadata.LogicalType$UuidType]: #user-content-dev.hardwood.metadata.logicaltype$uuidtype
[dev.hardwood.metadata.LogicalType$VariantType]: #user-content-dev.hardwood.metadata.logicaltype$varianttype
[dev.hardwood.metadata.OffsetIndex]: #user-content-dev.hardwood.metadata.offsetindex
[dev.hardwood.metadata.PageLocation]: #user-content-dev.hardwood.metadata.pagelocation
[dev.hardwood.metadata.PhysicalType]: #user-content-dev.hardwood.metadata.physicaltype
[dev.hardwood.metadata.RepetitionType]: #user-content-dev.hardwood.metadata.repetitiontype
[dev.hardwood.metadata.RowGroup]: #user-content-dev.hardwood.metadata.rowgroup
[dev.hardwood.metadata.SchemaElement]: #user-content-dev.hardwood.metadata.schemaelement
[dev.hardwood.metadata.Statistics]: #user-content-dev.hardwood.metadata.statistics
[dev.hardwood.reader.ColumnReader]: #user-content-dev.hardwood.reader.columnreader
[dev.hardwood.reader.ColumnReaders]: #user-content-dev.hardwood.reader.columnreaders
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
[dev.hardwood.reader.FilterPredicate$IntersectsPredicate]: #user-content-dev.hardwood.reader.filterpredicate$intersectspredicate
[dev.hardwood.reader.FilterPredicate$IsNotNullPredicate]: #user-content-dev.hardwood.reader.filterpredicate$isnotnullpredicate
[dev.hardwood.reader.FilterPredicate$IsNullPredicate]: #user-content-dev.hardwood.reader.filterpredicate$isnullpredicate
[dev.hardwood.reader.FilterPredicate$LongColumnPredicate]: #user-content-dev.hardwood.reader.filterpredicate$longcolumnpredicate
[dev.hardwood.reader.FilterPredicate$LongInPredicate]: #user-content-dev.hardwood.reader.filterpredicate$longinpredicate
[dev.hardwood.reader.FilterPredicate$Not]: #user-content-dev.hardwood.reader.filterpredicate$not
[dev.hardwood.reader.FilterPredicate$Operator]: #user-content-dev.hardwood.reader.filterpredicate$operator
[dev.hardwood.reader.FilterPredicate$Or]: #user-content-dev.hardwood.reader.filterpredicate$or
[dev.hardwood.reader.FilterPredicate$SignedBinaryColumnPredicate]: #user-content-dev.hardwood.reader.filterpredicate$signedbinarycolumnpredicate
[dev.hardwood.reader.FilterPredicate$TimeColumnPredicate]: #user-content-dev.hardwood.reader.filterpredicate$timecolumnpredicate
[dev.hardwood.reader.FilterPredicate$UUIDColumnPredicate]: #user-content-dev.hardwood.reader.filterpredicate$uuidcolumnpredicate
[dev.hardwood.reader.LayerKind]: #user-content-dev.hardwood.reader.layerkind
[dev.hardwood.reader.ParquetFileReader]: #user-content-dev.hardwood.reader.parquetfilereader
[dev.hardwood.reader.ParquetFileReader$ColumnReaderBuilder]: #user-content-dev.hardwood.reader.parquetfilereader$columnreaderbuilder
[dev.hardwood.reader.ParquetFileReader$ColumnReadersBuilder]: #user-content-dev.hardwood.reader.parquetfilereader$columnreadersbuilder
[dev.hardwood.reader.ParquetFileReader$RowReaderBuilder]: #user-content-dev.hardwood.reader.parquetfilereader$rowreaderbuilder
[dev.hardwood.reader.RowGroupPredicate]: #user-content-dev.hardwood.reader.rowgrouppredicate
[dev.hardwood.reader.RowGroupPredicate$And]: #user-content-dev.hardwood.reader.rowgrouppredicate$and
[dev.hardwood.reader.RowGroupPredicate$ByteRange]: #user-content-dev.hardwood.reader.rowgrouppredicate$byterange
[dev.hardwood.reader.RowReader]: #user-content-dev.hardwood.reader.rowreader
[dev.hardwood.reader.SchemaIncompatibleException]: #user-content-dev.hardwood.reader.schemaincompatibleexception
[dev.hardwood.reader.Validity]: #user-content-dev.hardwood.reader.validity
[dev.hardwood.row.FieldAccessor]: #user-content-dev.hardwood.row.fieldaccessor
[dev.hardwood.row.PqDoubleList]: #user-content-dev.hardwood.row.pqdoublelist
[dev.hardwood.row.PqIntList]: #user-content-dev.hardwood.row.pqintlist
[dev.hardwood.row.PqInterval]: #user-content-dev.hardwood.row.pqinterval
[dev.hardwood.row.PqList]: #user-content-dev.hardwood.row.pqlist
[dev.hardwood.row.PqLongList]: #user-content-dev.hardwood.row.pqlonglist
[dev.hardwood.row.PqMap]: #user-content-dev.hardwood.row.pqmap
[dev.hardwood.row.PqMap$Entry]: #user-content-dev.hardwood.row.pqmap$entry
[dev.hardwood.row.PqStruct]: #user-content-dev.hardwood.row.pqstruct
[dev.hardwood.row.PqVariant]: #user-content-dev.hardwood.row.pqvariant
[dev.hardwood.row.PqVariantArray]: #user-content-dev.hardwood.row.pqvariantarray
[dev.hardwood.row.PqVariantObject]: #user-content-dev.hardwood.row.pqvariantobject
[dev.hardwood.row.StructAccessor]: #user-content-dev.hardwood.row.structaccessor
[dev.hardwood.row.VariantType]: #user-content-dev.hardwood.row.varianttype
[dev.hardwood.row.VariantTypeException]: #user-content-dev.hardwood.row.varianttypeexception
[dev.hardwood.schema.ColumnProjection]: #user-content-dev.hardwood.schema.columnprojection
[dev.hardwood.schema.ColumnSchema]: #user-content-dev.hardwood.schema.columnschema
[dev.hardwood.schema.FileSchema]: #user-content-dev.hardwood.schema.fileschema
[dev.hardwood.schema.SchemaNode]: #user-content-dev.hardwood.schema.schemanode
[dev.hardwood.schema.SchemaNode$GroupNode]: #user-content-dev.hardwood.schema.schemanode$groupnode
[dev.hardwood.schema.SchemaNode$PrimitiveNode]: #user-content-dev.hardwood.schema.schemanode$primitivenode
