
# Compatibility Report

![semver MAJOR](https://img.shields.io/badge/semver-MAJOR-red?logo=semver "semver MAJOR")

## Summary

> [!CAUTION]
>
> Incompatible changes found while checking backward compatibility of version `1.0.0.CR1` with the previous version `1.0.0.Beta2`.

<details markdown="1">
<summary>Expand to see options used.</summary>

- **Report only summary**: No
- **Report only changes**: Yes
- **Report only binary-incompatible changes**: No
- **Access modifier filter**: `PROTECTED`
- **Old archives**:
  - ![hardwood-core 1.0.0.Beta2](https://img.shields.io/badge/hardwood_core-1.0.0.Beta2-blue "hardwood-core 1.0.0.Beta2")
- **New archives**:
  - ![hardwood-core 1.0.0.CR1](https://img.shields.io/badge/hardwood_core-1.0.0.CR1-blue "hardwood-core 1.0.0.CR1")
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

| Status   | Type                                                           | Serialization       | Compatibility Changes |
|----------|----------------------------------------------------------------|---------------------|-----------------------|
| Added    | [dev.hardwood.Experimental]                                    | ![Not serializable] | ![Annotation added] ![Interface added] |
| Added    | [dev.hardwood.metadata.BoundingBox]                            | ![Not serializable] | ![Method added to public class] |
| Modified | [dev.hardwood.metadata.ColumnIndex]                            | ![Not serializable] | ![Method added to public class] ![Constructor removed] |
| Modified | [dev.hardwood.metadata.ColumnMetaData]                         | ![Not serializable] | ![Method added to public class] ![Constructor removed] |
| Added    | [dev.hardwood.metadata.GeospatialStatistics]                   | ![Not serializable] | ![Method added to public class] |
| Added    | [dev.hardwood.metadata.LogicalType$EdgeInterpolationAlgorithm] | ![Compatible]       | ![Interface added] ![Method added to public class] |
| Added    | [dev.hardwood.metadata.LogicalType$Float16Type]                | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added    | [dev.hardwood.metadata.LogicalType$GeographyType]              | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added    | [dev.hardwood.metadata.LogicalType$GeometryType]               | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added    | [dev.hardwood.metadata.LogicalType$NullType]                   | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Modified | [dev.hardwood.reader.ColumnReader]                             | ![Not serializable] | ![Method removed] ![Method added to public class] |
| Modified | [dev.hardwood.reader.ColumnReaders]                            | ![Not serializable] | ![Method added to public class] |
| Modified | [dev.hardwood.reader.FilterPredicate]                          | ![Not serializable] | ![Method new static added to interface] |
| Added    | [dev.hardwood.reader.FilterPredicate$IntersectsPredicate]      | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added    | [dev.hardwood.reader.LayerKind]                                | ![Compatible]       | ![Interface added] ![Method added to public class] |
| Modified | [dev.hardwood.reader.ParquetFileReader]                        | ![Not serializable] | ![No changes]         |
| Modified | [dev.hardwood.reader.ParquetFileReader$ColumnReaderBuilder]    | ![Not serializable] | ![Method added to public class] |
| Modified | [dev.hardwood.reader.ParquetFileReader$ColumnReadersBuilder]   | ![Not serializable] | ![Method added to public class] |
| Modified | [dev.hardwood.reader.ParquetFileReader$RowReaderBuilder]       | ![Not serializable] | ![Method added to public class] |
| Added    | [dev.hardwood.reader.RowGroupPredicate]                        | ![Not serializable] | ![No changes]         |
| Added    | [dev.hardwood.reader.RowGroupPredicate$And]                    | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added    | [dev.hardwood.reader.RowGroupPredicate$ByteRange]              | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Modified | [dev.hardwood.reader.RowReader]                                | ![Not serializable] | ![Method removed]     |
| Added    | [dev.hardwood.reader.Validity]                                 | ![Not serializable] | ![No changes]         |
| Modified | [dev.hardwood.row.FieldAccessor]                               | ![Not serializable] | ![Method added to interface] |
| Modified | [dev.hardwood.row.PqList]                                      | ![Not serializable] | ![Method removed] ![Method return type changed] ![Method return type generics changed] ![Method added to interface] |
| Modified | [dev.hardwood.row.PqMap]                                       | ![Not serializable] | ![Method added to interface] |
| Modified | [dev.hardwood.row.PqMap$Entry]                                 | ![Not serializable] | ![Method removed] ![Method added to interface] |
| Modified | [dev.hardwood.row.StructAccessor]                              | ![Not serializable] | ![Method removed] ![Method added to interface] |
| Modified | [dev.hardwood.schema.FileSchema]                               | ![Not serializable] | ![No changes]         |
| Modified | [dev.hardwood.schema.SchemaNode$GroupNode]                     | ![Not serializable] | ![Method added to public class] |

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
| Removed | ~~`public`~~ |          | ~~`ColumnIndex`~~([`List<Boolean>`], [`List`], [`List`], [`BoundaryOrder`], [`List<Long>`]) |  |  | ![Constructor removed] |
| Added   | **`public`** |          | **`ColumnIndex`**([`List<Boolean>`], [`List`], [`List`], [`BoundaryOrder`], [`List<Long>`], [`List<GeospatialStatistics>`]) |  |  | ![No changes] |


#### Methods

| Status | Modifiers    | Generics | Type                               | Method                       | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|------------------------------------|------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **[`List<GeospatialStatistics>`]** | **`geospatialStatistics`**() |             |        | ![Method added to public class] |

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
| Removed | ~~`public`~~ |          | ~~`ColumnMetaData`~~([`PhysicalType`], [`List<Encoding>`], [`FieldPath`], [`CompressionCodec`], `long`, `long`, `long`, [`Map<String, String>`], `long`, [`Long`], [`Statistics`]) |  |  | ![Constructor removed] |
| Added   | **`public`** |          | **`ColumnMetaData`**([`PhysicalType`], [`List<Encoding>`], [`FieldPath`], [`CompressionCodec`], `long`, `long`, `long`, [`Map<String, String>`], `long`, [`Long`], [`Statistics`], [`GeospatialStatistics`], [`Long`], [`Integer`]) |  |  | ![No changes] |


#### Methods

| Status | Modifiers    | Generics | Type                         | Method                       | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|------------------------------|------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **[`Integer`]**              | **`bloomFilterLength`**()    |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`Long`]**                 | **`bloomFilterOffset`**()    |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`GeospatialStatistics`]** | **`geospatialStatistics`**() |             |        | ![Method added to public class] |

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
| Added  | **`static`** **`public`** |          | **[`EdgeInterpolationAlgorithm[]`][1]** | **`values`**()            |             |        | ![Method added to public class] |


#### Fields

| Status | Modifiers                             | Type                               | Name        | Annotations | Compatibility Changes |
|--------|---------------------------------------|------------------------------------|-------------|-------------|-----------------------|
| Added  | **`public`** **`static`** **`final`** | **[`EdgeInterpolationAlgorithm`]** | `ANDOYER`   |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`EdgeInterpolationAlgorithm`]** | `KARNEY`    |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`EdgeInterpolationAlgorithm`]** | `SPHERICAL` |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`EdgeInterpolationAlgorithm`]** | `THOMAS`    |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`EdgeInterpolationAlgorithm`]** | `VINCENTY`  |             | ![No changes]         |

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

<a id="user-content-dev.hardwood.reader.columnreader"></a>
### `dev.hardwood.reader.ColumnReader`

- [ ] Binary-compatible
- [ ] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers | Type  | Name           | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|-----------|-------|----------------|------------|--------|---------------------|-----------------------|
| Modified | `public`  | Class | `ColumnReader` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Methods

| Status  | Modifiers    | Generics | Type              | Method                        | Annotations | Throws | Compatibility Changes |
|---------|--------------|----------|-------------------|-------------------------------|-------------|--------|-----------------------|
| Added   | **`public`** |          | **`int[]`**       | **`getBinaryOffsets`**()      |             |        | ![Method added to public class] |
| Added   | **`public`** |          | **`byte[]`**      | **`getBinaryValues`**()       |             |        | ![Method added to public class] |
| Added   | **`public`** |          | **`int[]`**       | **`getDefinitionLevels`**()   |             |        | ![Method added to public class] |
| Removed | ~~`public`~~ |          | ~~[`BitSet`]~~    | ~~`getElementNulls`~~()       |             |        | ![Method removed]     |
| Added   | **`public`** |          | **`int`**         | **`getLayerCount`**()         |             |        | ![Method added to public class] |
| Added   | **`public`** |          | **[`LayerKind`]** | **`getLayerKind`**(`int`)     |             |        | ![Method added to public class] |
| Added   | **`public`** |          | **`int[]`**       | **`getLayerOffsets`**(`int`)  |             |        | ![Method added to public class] |
| Added   | **`public`** |          | **[`Validity`]**  | **`getLayerValidity`**(`int`) |             |        | ![Method added to public class] |
| Added   | **`public`** |          | **[`Validity`]**  | **`getLeafValidity`**()       |             |        | ![Method added to public class] |
| Removed | ~~`public`~~ |          | ~~[`BitSet`]~~    | ~~`getLevelNulls`~~(`int`)    |             |        | ![Method removed]     |
| Removed | ~~`public`~~ |          | ~~`int`~~         | ~~`getNestingDepth`~~()       |             |        | ![Method removed]     |
| Removed | ~~`public`~~ |          | ~~`int[]`~~       | ~~`getOffsets`~~(`int`)       |             |        | ![Method removed]     |
| Added   | **`public`** |          | **`int[]`**       | **`getRepetitionLevels`**()   |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.reader.columnreaders"></a>
### `dev.hardwood.reader.ColumnReaders`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers | Type  | Name            | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|-----------|-------|-----------------|------------|--------|---------------------|-----------------------|
| Modified | `public`  | Class | `ColumnReaders` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers    | Generics | Type          | Method                 | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|---------------|------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`int`**     | **`getRecordCount`**() |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **`boolean`** | **`nextBatch`**()      |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.reader.filterpredicate"></a>
### `dev.hardwood.reader.FilterPredicate`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers           | Type      | Name              | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|---------------------|-----------|-------------------|------------|--------|---------------------|-----------------------|
| Modified | `public` `abstract` | Interface | `FilterPredicate` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers                 | Generics | Type                    | Method | Annotations | Throws | Compatibility Changes |
|--------|---------------------------|----------|-------------------------|--------|-------------|--------|-----------------------|
| Added  | **`static`** **`public`** |          | **[`FilterPredicate`]** | **`intersects`**([`String`], `double`, `double`, `double`, `double`) |  |  | ![Method new static added to interface] |

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

| Status | Modifiers                 | Generics | Type                   | Method                    | Annotations | Throws | Compatibility Changes |
|--------|---------------------------|----------|------------------------|---------------------------|-------------|--------|-----------------------|
| Added  | **`static`** **`public`** |          | **[`LayerKind`]**      | **`valueOf`**([`String`]) |             |        | ![Method added to public class] |
| Added  | **`static`** **`public`** |          | **[`LayerKind[]`][2]** | **`values`**()            |             |        | ![Method added to public class] |


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

| Status   | Modifiers | Type  | Name                | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|-----------|-------|---------------------|------------|--------|---------------------|-----------------------|
| Modified | `public`  | Class | `ParquetFileReader` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |

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

| Status | Modifiers    | Generics | Type                        | Method                              | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-----------------------------|-------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **[`ColumnReaderBuilder`]** | **`filter`**([`RowGroupPredicate`]) |             |        | ![Method added to public class] |

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

| Status | Modifiers    | Generics | Type                         | Method                              | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|------------------------------|-------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **[`ColumnReadersBuilder`]** | **`filter`**([`RowGroupPredicate`]) |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.reader.parquetfilereader$rowreaderbuilder"></a>
### `dev.hardwood.reader.ParquetFileReader$RowReaderBuilder`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers                 | Type  | Name               | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|---------------------------|-------|--------------------|------------|--------|---------------------|-----------------------|
| Modified | `final` `static` `public` | Class | `RowReaderBuilder` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers    | Generics | Type                     | Method                              | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|--------------------------|-------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **[`RowReaderBuilder`]** | **`filter`**([`RowGroupPredicate`]) |             |        | ![Method added to public class] |

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
| Incompatible        | [`StructAccessor`] | ![No changes]         |


#### Methods

| Status  | Modifiers                   | Generics | Type                 | Method                        | Annotations | Throws | Compatibility Changes |
|---------|-----------------------------|----------|----------------------|-------------------------------|-------------|--------|-----------------------|
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~`byte[]`~~         | ~~`getBinary`~~(`int`)        |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~`boolean`~~        | ~~`getBoolean`~~(`int`)       |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`LocalDate`]~~    | ~~`getDate`~~(`int`)          |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`BigDecimal`]~~   | ~~`getDecimal`~~(`int`)       |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~`double`~~         | ~~`getDouble`~~(`int`)        |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~`float`~~          | ~~`getFloat`~~(`int`)         |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~`int`~~            | ~~`getInt`~~(`int`)           |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`PqInterval`]~~   | ~~`getInterval`~~(`int`)      |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`PqList`]~~       | ~~`getList`~~(`int`)          |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`PqDoubleList`]~~ | ~~`getListOfDoubles`~~(`int`) |             |        | ![Method removed]     |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`PqIntList`]~~    | ~~`getListOfInts`~~(`int`)    |             |        | ![Method removed]     |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`PqLongList`]~~   | ~~`getListOfLongs`~~(`int`)   |             |        | ![Method removed]     |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~`long`~~           | ~~`getLong`~~(`int`)          |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`PqMap`]~~        | ~~`getMap`~~(`int`)           |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`String`]~~       | ~~`getString`~~(`int`)        |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`PqStruct`]~~     | ~~`getStruct`~~(`int`)        |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`LocalTime`]~~    | ~~`getTime`~~(`int`)          |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`Instant`]~~      | ~~`getTimestamp`~~(`int`)     |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`UUID`]~~         | ~~`getUuid`~~(`int`)          |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`Object`]~~       | ~~`getValue`~~(`int`)         |             |        | ![No changes]         |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~`boolean`~~        | ~~`isNull`~~(`int`)           |             |        | ![No changes]         |

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
- [ ] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers           | Type      | Name            | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|---------------------|-----------|-----------------|------------|--------|---------------------|-----------------------|
| Modified | `public` `abstract` | Interface | `FieldAccessor` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers                   | Generics | Type           | Method                        | Annotations | Throws | Compatibility Changes |
|--------|-----------------------------|----------|----------------|-------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** **`abstract`** |          | **[`Object`]** | **`getRawValue`**([`String`]) |             |        | ![Method added to interface] |

___

<a id="user-content-dev.hardwood.row.pqlist"></a>
### `dev.hardwood.row.PqList`

- [ ] Binary-compatible
- [ ] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers           | Type      | Name     | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|---------------------|-----------|----------|------------|--------|---------------------|-----------------------|
| Modified | `public` `abstract` | Interface | `PqList` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Methods

| Status   | Modifiers                   | Generics | Type                                                         | Method              | Annotations | Throws | Compatibility Changes |
|----------|-----------------------------|----------|--------------------------------------------------------------|---------------------|-------------|--------|-----------------------|
| Modified | `public` `abstract`         |          | ~~[`Iterable`]~~ &rarr; **[`List`]**                         | `binaries`()        |             |        | ![Method return type changed] |
| Modified | `public` `abstract`         |          | ~~[`Iterable<Boolean>`]~~ &rarr; **[`List<Boolean>`]**       | `booleans`()        |             |        | ![Method return type changed] |
| Modified | `public` `abstract`         |          | ~~[`Iterable<LocalDate>`]~~ &rarr; **[`List<LocalDate>`]**   | `dates`()           |             |        | ![Method return type changed] |
| Modified | `public` `abstract`         |          | ~~[`Iterable<BigDecimal>`]~~ &rarr; **[`List<BigDecimal>`]** | `decimals`()        |             |        | ![Method return type changed] |
| Removed  | ~~`public`~~ ~~`abstract`~~ |          | ~~[`Iterable<PqDoubleList>`]~~                               | ~~`doubleLists`~~() |             |        | ![Method removed]     |
| Modified | `public` `abstract`         |          | ~~[`Iterable<Double>`]~~ &rarr; **[`PqDoubleList`]**         | `doubles`()         |             |        | ![Method return type changed] ![Method return type generics changed] |
| Modified | `public` `abstract`         |          | ~~[`Iterable<Float>`]~~ &rarr; **[`List<Float>`]**           | `floats`()          |             |        | ![Method return type changed] |
| Added    | **`public`** **`abstract`** |          | **[`Object`]**                                               | **`getRaw`**(`int`) |             |        | ![Method added to interface] |
| Removed  | ~~`public`~~ ~~`abstract`~~ |          | ~~[`Iterable<PqIntList>`]~~                                  | ~~`intLists`~~()    |             |        | ![Method removed]     |
| Added    | **`public`** **`abstract`** |          | **[`List<PqInterval>`]**                                     | **`intervals`**()   |             |        | ![Method added to interface] |
| Modified | `public` `abstract`         |          | ~~[`Iterable<Integer>`]~~ &rarr; **[`PqIntList`]**           | `ints`()            |             |        | ![Method return type changed] ![Method return type generics changed] |
| Modified | `public` `abstract`         |          | ~~[`Iterable<PqList>`]~~ &rarr; **[`List<PqList>`]**         | `lists`()           |             |        | ![Method return type changed] |
| Removed  | ~~`public`~~ ~~`abstract`~~ |          | ~~[`Iterable<PqLongList>`]~~                                 | ~~`longLists`~~()   |             |        | ![Method removed]     |
| Modified | `public` `abstract`         |          | ~~[`Iterable<Long>`]~~ &rarr; **[`PqLongList`]**             | `longs`()           |             |        | ![Method return type changed] ![Method return type generics changed] |
| Modified | `public` `abstract`         |          | ~~[`Iterable<PqMap>`]~~ &rarr; **[`List<PqMap>`]**           | `maps`()            |             |        | ![Method return type changed] |
| Added    | **`public`** **`abstract`** |          | **[`List<Object>`]**                                         | **`rawValues`**()   |             |        | ![Method added to interface] |
| Modified | `public` `abstract`         |          | ~~[`Iterable<String>`]~~ &rarr; **[`List<String>`]**         | `strings`()         |             |        | ![Method return type changed] |
| Modified | `public` `abstract`         |          | ~~[`Iterable<PqStruct>`]~~ &rarr; **[`List<PqStruct>`]**     | `structs`()         |             |        | ![Method return type changed] |
| Modified | `public` `abstract`         |          | ~~[`Iterable<LocalTime>`]~~ &rarr; **[`List<LocalTime>`]**   | `times`()           |             |        | ![Method return type changed] |
| Modified | `public` `abstract`         |          | ~~[`Iterable<Instant>`]~~ &rarr; **[`List<Instant>`]**       | `timestamps`()      |             |        | ![Method return type changed] |
| Modified | `public` `abstract`         |          | ~~[`Iterable<UUID>`]~~ &rarr; **[`List<UUID>`]**             | `uuids`()           |             |        | ![Method return type changed] |
| Modified | `public` `abstract`         |          | ~~[`Iterable<Object>`]~~ &rarr; **[`List<Object>`]**         | `values`()          |             |        | ![Method return type changed] |
| Added    | **`public`** **`abstract`** |          | **[`List<PqVariant>`]**                                      | **`variants`**()    |             |        | ![Method added to interface] |

___

<a id="user-content-dev.hardwood.row.pqmap"></a>
### `dev.hardwood.row.PqMap`

- [X] Binary-compatible
- [ ] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers           | Type      | Name    | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|---------------------|-----------|---------|------------|--------|---------------------|-----------------------|
| Modified | `public` `abstract` | Interface | `PqMap` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers                   | Generics | Type           | Method                        | Annotations | Throws | Compatibility Changes |
|--------|-----------------------------|----------|----------------|-------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** **`abstract`** |          | **`boolean`**  | **`containsKey`**([`String`]) |             |        | ![Method added to interface] |
| Added  | **`public`** **`abstract`** |          | **`boolean`**  | **`containsKey`**(`int`)      |             |        | ![Method added to interface] |
| Added  | **`public`** **`abstract`** |          | **`boolean`**  | **`containsKey`**(`long`)     |             |        | ![Method added to interface] |
| Added  | **`public`** **`abstract`** |          | **`boolean`**  | **`containsKey`**(`byte[]`)   |             |        | ![Method added to interface] |
| Added  | **`public`** **`abstract`** |          | **[`Object`]** | **`getRawValue`**([`String`]) |             |        | ![Method added to interface] |
| Added  | **`public`** **`abstract`** |          | **[`Object`]** | **`getRawValue`**(`int`)      |             |        | ![Method added to interface] |
| Added  | **`public`** **`abstract`** |          | **[`Object`]** | **`getRawValue`**(`long`)     |             |        | ![Method added to interface] |
| Added  | **`public`** **`abstract`** |          | **[`Object`]** | **`getRawValue`**(`byte[]`)   |             |        | ![Method added to interface] |
| Added  | **`public`** **`abstract`** |          | **[`Object`]** | **`getValue`**([`String`])    |             |        | ![Method added to interface] |
| Added  | **`public`** **`abstract`** |          | **[`Object`]** | **`getValue`**(`int`)         |             |        | ![Method added to interface] |
| Added  | **`public`** **`abstract`** |          | **[`Object`]** | **`getValue`**(`long`)        |             |        | ![Method added to interface] |
| Added  | **`public`** **`abstract`** |          | **[`Object`]** | **`getValue`**(`byte[]`)      |             |        | ![Method added to interface] |

___

<a id="user-content-dev.hardwood.row.pqmap$entry"></a>
### `dev.hardwood.row.PqMap$Entry`

- [ ] Binary-compatible
- [ ] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers                    | Type      | Name    | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|------------------------------|-----------|---------|------------|--------|---------------------|-----------------------|
| Modified | `static` `public` `abstract` | Interface | `Entry` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Methods

| Status  | Modifiers                   | Generics | Type               | Method                   | Annotations | Throws | Compatibility Changes |
|---------|-----------------------------|----------|--------------------|--------------------------|-------------|--------|-----------------------|
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`LocalDate`]~~  | ~~`getDateKey`~~()       |             |        | ![Method removed]     |
| Added   | **`public`** **`abstract`** |          | **[`PqInterval`]** | **`getIntervalValue`**() |             |        | ![Method added to interface] |
| Added   | **`public`** **`abstract`** |          | **[`Object`]**     | **`getRawKey`**()        |             |        | ![Method added to interface] |
| Added   | **`public`** **`abstract`** |          | **[`Object`]**     | **`getRawValue`**()      |             |        | ![Method added to interface] |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`Instant`]~~    | ~~`getTimestampKey`~~()  |             |        | ![Method removed]     |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`UUID`]~~       | ~~`getUuidKey`~~()       |             |        | ![Method removed]     |
| Added   | **`public`** **`abstract`** |          | **[`PqVariant`]**  | **`getVariantValue`**()  |             |        | ![Method added to interface] |

___

<a id="user-content-dev.hardwood.row.structaccessor"></a>
### `dev.hardwood.row.StructAccessor`

- [ ] Binary-compatible
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

| Status  | Modifiers                   | Generics | Type                 | Method                             | Annotations | Throws | Compatibility Changes |
|---------|-----------------------------|----------|----------------------|------------------------------------|-------------|--------|-----------------------|
| Added   | **`public`** **`abstract`** |          | **`byte[]`**         | **`getBinary`**(`int`)             |             |        | ![Method added to interface] |
| Added   | **`public`** **`abstract`** |          | **`boolean`**        | **`getBoolean`**(`int`)            |             |        | ![Method added to interface] |
| Added   | **`public`** **`abstract`** |          | **[`LocalDate`]**    | **`getDate`**(`int`)               |             |        | ![Method added to interface] |
| Added   | **`public`** **`abstract`** |          | **[`BigDecimal`]**   | **`getDecimal`**(`int`)            |             |        | ![Method added to interface] |
| Added   | **`public`** **`abstract`** |          | **`double`**         | **`getDouble`**(`int`)             |             |        | ![Method added to interface] |
| Added   | **`public`** **`abstract`** |          | **`float`**          | **`getFloat`**(`int`)              |             |        | ![Method added to interface] |
| Added   | **`public`** **`abstract`** |          | **`int`**            | **`getInt`**(`int`)                |             |        | ![Method added to interface] |
| Added   | **`public`** **`abstract`** |          | **[`PqInterval`]**   | **`getInterval`**(`int`)           |             |        | ![Method added to interface] |
| Added   | **`public`** **`abstract`** |          | **[`PqList`]**       | **`getList`**(`int`)               |             |        | ![Method added to interface] |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`PqDoubleList`]~~ | ~~`getListOfDoubles`~~([`String`]) |             |        | ![Method removed]     |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`PqIntList`]~~    | ~~`getListOfInts`~~([`String`])    |             |        | ![Method removed]     |
| Removed | ~~`public`~~ ~~`abstract`~~ |          | ~~[`PqLongList`]~~   | ~~`getListOfLongs`~~([`String`])   |             |        | ![Method removed]     |
| Added   | **`public`** **`abstract`** |          | **`long`**           | **`getLong`**(`int`)               |             |        | ![Method added to interface] |
| Added   | **`public`** **`abstract`** |          | **[`PqMap`]**        | **`getMap`**(`int`)                |             |        | ![Method added to interface] |
| Added   | **`public`** **`abstract`** |          | **[`Object`]**       | **`getRawValue`**(`int`)           |             |        | ![Method added to interface] |
| Added   | **`public`** **`abstract`** |          | **[`String`]**       | **`getString`**(`int`)             |             |        | ![Method added to interface] |
| Added   | **`public`** **`abstract`** |          | **[`PqStruct`]**     | **`getStruct`**(`int`)             |             |        | ![Method added to interface] |
| Added   | **`public`** **`abstract`** |          | **[`LocalTime`]**    | **`getTime`**(`int`)               |             |        | ![Method added to interface] |
| Added   | **`public`** **`abstract`** |          | **[`Instant`]**      | **`getTimestamp`**(`int`)          |             |        | ![Method added to interface] |
| Added   | **`public`** **`abstract`** |          | **[`UUID`]**         | **`getUuid`**(`int`)               |             |        | ![Method added to interface] |
| Added   | **`public`** **`abstract`** |          | **[`Object`]**       | **`getValue`**(`int`)              |             |        | ![Method added to interface] |
| Added   | **`public`** **`abstract`** |          | **[`PqVariant`]**    | **`getVariant`**(`int`)            |             |        | ![Method added to interface] |
| Added   | **`public`** **`abstract`** |          | **`boolean`**        | **`isNull`**(`int`)                |             |        | ![Method added to interface] |

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

<a id="user-content-dev.hardwood.schema.schemanode$groupnode"></a>
### `dev.hardwood.schema.SchemaNode$GroupNode`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers                 | Type  | Name        | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|---------------------------|-------|-------------|------------|--------|---------------------|-----------------------|
| Modified | `final` `static` `public` | Class | `GroupNode` | [`Record`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers    | Generics | Type               | Method              | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|--------------------|---------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **[`SchemaNode`]** | **`getMapKey`**()   |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`SchemaNode`]** | **`getMapValue`**() |             |        | ![Method added to public class] |


</details>


___

*Generated on: 2026-06-05 09:27:20.025+0000*.

[1]: # "dev.hardwood.metadata.LogicalType$EdgeInterpolationAlgorithm[]"
[2]: # "dev.hardwood.reader.LayerKind[]"
[Annotation added]: https://img.shields.io/badge/Annotation_added-yellow "Annotation added"
[Compatible]: https://img.shields.io/badge/Compatible-green "Compatible"
[Constructor removed]: https://img.shields.io/badge/Constructor_removed-red "Constructor removed"
[Interface added]: https://img.shields.io/badge/Interface_added-orange "Interface added"
[Method added to interface]: https://img.shields.io/badge/Method_added_to_interface-orange "Method added to interface"
[Method added to public class]: https://img.shields.io/badge/Method_added_to_public_class-yellow "Method added to public class"
[Method new static added to interface]: https://img.shields.io/badge/Method_new_static_added_to_interface-orange "Method new static added to interface"
[Method removed]: https://img.shields.io/badge/Method_removed-red "Method removed"
[Method return type changed]: https://img.shields.io/badge/Method_return_type_changed-red "Method return type changed"
[Method return type generics changed]: https://img.shields.io/badge/Method_return_type_generics_changed-orange "Method return type generics changed"
[No changes]: https://img.shields.io/badge/No_changes-green "No changes"
[Not serializable]: https://img.shields.io/badge/Not_serializable-green "Not serializable"
[`Annotation`]: # "java.lang.annotation.Annotation"
[`BigDecimal`]: # "java.math.BigDecimal"
[`BitSet`]: # "java.util.BitSet"
[`BoundaryOrder`]: # "dev.hardwood.metadata.ColumnIndex$BoundaryOrder"
[`BoundingBox`]: # "dev.hardwood.metadata.BoundingBox"
[`CLASS`]: # "java.lang.annotation.RetentionPolicy.CLASS"
[`ColumnReaderBuilder`]: # "dev.hardwood.reader.ParquetFileReader$ColumnReaderBuilder"
[`ColumnReadersBuilder`]: # "dev.hardwood.reader.ParquetFileReader$ColumnReadersBuilder"
[`Comparable<T>`]: # "java.lang.Comparable<T extends java.lang.Object>"
[`CompressionCodec`]: # "dev.hardwood.metadata.CompressionCodec"
[`Constable`]: # "java.lang.constant.Constable"
[`Documented`]: # "java.lang.annotation.Documented"
[`Double`]: # "java.lang.Double"
[`EdgeInterpolationAlgorithm`]: # "dev.hardwood.metadata.LogicalType$EdgeInterpolationAlgorithm"
[`Enum<E>`]: # "java.lang.Enum<E extends java.lang.Enum<E>>"
[`FieldAccessor`]: # "dev.hardwood.row.FieldAccessor"
[`FieldPath`]: # "dev.hardwood.metadata.FieldPath"
[`FilterPredicate`]: # "dev.hardwood.reader.FilterPredicate"
[`GeospatialStatistics`]: # "dev.hardwood.metadata.GeospatialStatistics"
[`Instant`]: # "java.time.Instant"
[`Integer`]: # "java.lang.Integer"
[`Iterable<BigDecimal>`]: # "java.lang.Iterable<java.math.BigDecimal>"
[`Iterable<Boolean>`]: # "java.lang.Iterable<java.lang.Boolean>"
[`Iterable<Double>`]: # "java.lang.Iterable<java.lang.Double>"
[`Iterable<Float>`]: # "java.lang.Iterable<java.lang.Float>"
[`Iterable<Instant>`]: # "java.lang.Iterable<java.time.Instant>"
[`Iterable<Integer>`]: # "java.lang.Iterable<java.lang.Integer>"
[`Iterable<LocalDate>`]: # "java.lang.Iterable<java.time.LocalDate>"
[`Iterable<LocalTime>`]: # "java.lang.Iterable<java.time.LocalTime>"
[`Iterable<Long>`]: # "java.lang.Iterable<java.lang.Long>"
[`Iterable<Object>`]: # "java.lang.Iterable<java.lang.Object>"
[`Iterable<PqDoubleList>`]: # "java.lang.Iterable<dev.hardwood.row.PqDoubleList>"
[`Iterable<PqIntList>`]: # "java.lang.Iterable<dev.hardwood.row.PqIntList>"
[`Iterable<PqList>`]: # "java.lang.Iterable<dev.hardwood.row.PqList>"
[`Iterable<PqLongList>`]: # "java.lang.Iterable<dev.hardwood.row.PqLongList>"
[`Iterable<PqMap>`]: # "java.lang.Iterable<dev.hardwood.row.PqMap>"
[`Iterable<PqStruct>`]: # "java.lang.Iterable<dev.hardwood.row.PqStruct>"
[`Iterable<String>`]: # "java.lang.Iterable<java.lang.String>"
[`Iterable<UUID>`]: # "java.lang.Iterable<java.util.UUID>"
[`Iterable`]: # "java.lang.Iterable"
[`LayerKind`]: # "dev.hardwood.reader.LayerKind"
[`List<BigDecimal>`]: # "java.util.List<java.math.BigDecimal>"
[`List<Boolean>`]: # "java.util.List<java.lang.Boolean>"
[`List<Encoding>`]: # "java.util.List<dev.hardwood.metadata.Encoding>"
[`List<Float>`]: # "java.util.List<java.lang.Float>"
[`List<GeospatialStatistics>`]: # "java.util.List<dev.hardwood.metadata.GeospatialStatistics>"
[`List<Instant>`]: # "java.util.List<java.time.Instant>"
[`List<Integer>`]: # "java.util.List<java.lang.Integer>"
[`List<LocalDate>`]: # "java.util.List<java.time.LocalDate>"
[`List<LocalTime>`]: # "java.util.List<java.time.LocalTime>"
[`List<Long>`]: # "java.util.List<java.lang.Long>"
[`List<Object>`]: # "java.util.List<java.lang.Object>"
[`List<PqInterval>`]: # "java.util.List<dev.hardwood.row.PqInterval>"
[`List<PqList>`]: # "java.util.List<dev.hardwood.row.PqList>"
[`List<PqMap>`]: # "java.util.List<dev.hardwood.row.PqMap>"
[`List<PqStruct>`]: # "java.util.List<dev.hardwood.row.PqStruct>"
[`List<PqVariant>`]: # "java.util.List<dev.hardwood.row.PqVariant>"
[`List<RowGroupPredicate>`]: # "java.util.List<dev.hardwood.reader.RowGroupPredicate>"
[`List<String>`]: # "java.util.List<java.lang.String>"
[`List<UUID>`]: # "java.util.List<java.util.UUID>"
[`List`]: # "java.util.List"
[`LocalDate`]: # "java.time.LocalDate"
[`LocalTime`]: # "java.time.LocalTime"
[`LogicalType`]: # "dev.hardwood.metadata.LogicalType"
[`Long`]: # "java.lang.Long"
[`Map<String, String>`]: # "java.util.Map<java.lang.String, java.lang.String>"
[`Object`]: # "java.lang.Object"
[`PhysicalType`]: # "dev.hardwood.metadata.PhysicalType"
[`PqDoubleList`]: # "dev.hardwood.row.PqDoubleList"
[`PqIntList`]: # "dev.hardwood.row.PqIntList"
[`PqInterval`]: # "dev.hardwood.row.PqInterval"
[`PqList`]: # "dev.hardwood.row.PqList"
[`PqLongList`]: # "dev.hardwood.row.PqLongList"
[`PqMap`]: # "dev.hardwood.row.PqMap"
[`PqStruct`]: # "dev.hardwood.row.PqStruct"
[`PqVariant`]: # "dev.hardwood.row.PqVariant"
[`Record`]: # "java.lang.Record"
[`Retention`]: # "java.lang.annotation.Retention"
[`RowGroupPredicate...`]: # "dev.hardwood.reader.RowGroupPredicate..."
[`RowGroupPredicate`]: # "dev.hardwood.reader.RowGroupPredicate"
[`RowReaderBuilder`]: # "dev.hardwood.reader.ParquetFileReader$RowReaderBuilder"
[`SchemaNode`]: # "dev.hardwood.schema.SchemaNode"
[`Serializable`]: # "java.io.Serializable"
[`Statistics`]: # "dev.hardwood.metadata.Statistics"
[`String`]: # "java.lang.String"
[`StructAccessor`]: # "dev.hardwood.row.StructAccessor"
[`Target`]: # "java.lang.annotation.Target"
[`UUID`]: # "java.util.UUID"
[`Validity`]: # "dev.hardwood.reader.Validity"
[`{TYPE, METHOD, CONSTRUCTOR, FIELD}`]: # "{java.lang.annotation.ElementType.TYPE, java.lang.annotation.ElementType.METHOD, java.lang.annotation.ElementType.CONSTRUCTOR, java.lang.annotation.ElementType.FIELD}"
[dev.hardwood.Experimental]: #user-content-dev.hardwood.experimental
[dev.hardwood.metadata.BoundingBox]: #user-content-dev.hardwood.metadata.boundingbox
[dev.hardwood.metadata.ColumnIndex]: #user-content-dev.hardwood.metadata.columnindex
[dev.hardwood.metadata.ColumnMetaData]: #user-content-dev.hardwood.metadata.columnmetadata
[dev.hardwood.metadata.GeospatialStatistics]: #user-content-dev.hardwood.metadata.geospatialstatistics
[dev.hardwood.metadata.LogicalType$EdgeInterpolationAlgorithm]: #user-content-dev.hardwood.metadata.logicaltype$edgeinterpolationalgorithm
[dev.hardwood.metadata.LogicalType$Float16Type]: #user-content-dev.hardwood.metadata.logicaltype$float16type
[dev.hardwood.metadata.LogicalType$GeographyType]: #user-content-dev.hardwood.metadata.logicaltype$geographytype
[dev.hardwood.metadata.LogicalType$GeometryType]: #user-content-dev.hardwood.metadata.logicaltype$geometrytype
[dev.hardwood.metadata.LogicalType$NullType]: #user-content-dev.hardwood.metadata.logicaltype$nulltype
[dev.hardwood.reader.ColumnReader]: #user-content-dev.hardwood.reader.columnreader
[dev.hardwood.reader.ColumnReaders]: #user-content-dev.hardwood.reader.columnreaders
[dev.hardwood.reader.FilterPredicate]: #user-content-dev.hardwood.reader.filterpredicate
[dev.hardwood.reader.FilterPredicate$IntersectsPredicate]: #user-content-dev.hardwood.reader.filterpredicate$intersectspredicate
[dev.hardwood.reader.LayerKind]: #user-content-dev.hardwood.reader.layerkind
[dev.hardwood.reader.ParquetFileReader]: #user-content-dev.hardwood.reader.parquetfilereader
[dev.hardwood.reader.ParquetFileReader$ColumnReaderBuilder]: #user-content-dev.hardwood.reader.parquetfilereader$columnreaderbuilder
[dev.hardwood.reader.ParquetFileReader$ColumnReadersBuilder]: #user-content-dev.hardwood.reader.parquetfilereader$columnreadersbuilder
[dev.hardwood.reader.ParquetFileReader$RowReaderBuilder]: #user-content-dev.hardwood.reader.parquetfilereader$rowreaderbuilder
[dev.hardwood.reader.RowGroupPredicate]: #user-content-dev.hardwood.reader.rowgrouppredicate
[dev.hardwood.reader.RowGroupPredicate$And]: #user-content-dev.hardwood.reader.rowgrouppredicate$and
[dev.hardwood.reader.RowGroupPredicate$ByteRange]: #user-content-dev.hardwood.reader.rowgrouppredicate$byterange
[dev.hardwood.reader.RowReader]: #user-content-dev.hardwood.reader.rowreader
[dev.hardwood.reader.Validity]: #user-content-dev.hardwood.reader.validity
[dev.hardwood.row.FieldAccessor]: #user-content-dev.hardwood.row.fieldaccessor
[dev.hardwood.row.PqList]: #user-content-dev.hardwood.row.pqlist
[dev.hardwood.row.PqMap]: #user-content-dev.hardwood.row.pqmap
[dev.hardwood.row.PqMap$Entry]: #user-content-dev.hardwood.row.pqmap$entry
[dev.hardwood.row.StructAccessor]: #user-content-dev.hardwood.row.structaccessor
[dev.hardwood.schema.FileSchema]: #user-content-dev.hardwood.schema.fileschema
[dev.hardwood.schema.SchemaNode$GroupNode]: #user-content-dev.hardwood.schema.schemanode$groupnode
