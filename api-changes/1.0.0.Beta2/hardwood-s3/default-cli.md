
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
  - ![hardwood-s3 1.0.0.Beta1](https://img.shields.io/badge/hardwood_s3-1.0.0.Beta1-blue "hardwood-s3 1.0.0.Beta1")
- **New archives**:
  - ![hardwood-s3 1.0.0.Beta2](https://img.shields.io/badge/hardwood_s3-1.0.0.Beta2-blue "hardwood-s3 1.0.0.Beta2")
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

| Status   | Type                               | Serialization       | Compatibility Changes |
|----------|------------------------------------|---------------------|-----------------------|
| Added    | [dev.hardwood.s3.RangeBacking]     | ![Compatible]       | ![Interface added] ![Method added to public class] |
| Modified | [dev.hardwood.s3.S3InputFile]      | ![Not serializable] | ![Method added to public class] |
| Modified | [dev.hardwood.s3.S3Source]         | ![Not serializable] | ![Method return type changed] |
| Modified | [dev.hardwood.s3.S3Source$Builder] | ![Not serializable] | ![Method added to public class] |

<details markdown="1">
<summary>Expand for details.</summary>

___

<a id="user-content-dev.hardwood.s3.rangebacking"></a>
### `dev.hardwood.s3.RangeBacking`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                | Type     | Name               | Extends         | JDK        | Serialization | Compatibility Changes |
|--------|--------------------------|----------|--------------------|-----------------|------------|---------------|-----------------------|
| Added  | **`final`** **`public`** | **Enum** | **`RangeBacking`** | **[`Enum<E>`]** | **JDK 21** | ![Compatible] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface             | Compatibility Changes |
|--------|-----------------------|-----------------------|
| Added  | **[`Serializable`]**  | ![No changes]         |
| Added  | **[`Comparable<T>`]** | ![No changes]         |
| Added  | **[`Constable`]**     | ![No changes]         |


#### Methods

| Status | Modifiers                 | Generics | Type                      | Method                    | Annotations | Throws | Compatibility Changes |
|--------|---------------------------|----------|---------------------------|---------------------------|-------------|--------|-----------------------|
| Added  | **`static`** **`public`** |          | **[`RangeBacking`]**      | **`valueOf`**([`String`]) |             |        | ![Method added to public class] |
| Added  | **`static`** **`public`** |          | **[`RangeBacking[]`][1]** | **`values`**()            |             |        | ![Method added to public class] |


#### Fields

| Status | Modifiers                             | Type                 | Name              | Annotations | Compatibility Changes |
|--------|---------------------------------------|----------------------|-------------------|-------------|-----------------------|
| Added  | **`public`** **`static`** **`final`** | **[`RangeBacking`]** | `NONE`            |             | ![No changes]         |
| Added  | **`public`** **`static`** **`final`** | **[`RangeBacking`]** | `SPARSE_TEMPFILE` |             | ![No changes]         |

___

<a id="user-content-dev.hardwood.s3.s3inputfile"></a>
### `dev.hardwood.s3.S3InputFile`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers | Type  | Name          | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|-----------|-------|---------------|------------|--------|---------------------|-----------------------|
| Modified | `public`  | Class | `S3InputFile` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers    | Generics | Type       | Method                      | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|------------|-----------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`long`** | **`networkBytesFetched`**() |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **`long`** | **`networkRequestCount`**() |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.s3.s3source"></a>
### `dev.hardwood.s3.S3Source`

- [ ] Binary-compatible
- [ ] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers        | Type  | Name       | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|------------------|-------|------------|------------|--------|---------------------|-----------------------|
| Modified | `final` `public` | Class | `S3Source` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Methods

| Status   | Modifiers | Generics | Type                                         | Method                              | Annotations | Throws | Compatibility Changes |
|----------|-----------|----------|----------------------------------------------|-------------------------------------|-------------|--------|-----------------------|
| Modified | `public`  |          | ~~[`S3InputFile`]~~ &rarr; **[`InputFile`]** | `inputFile`([`String`], [`String`]) |             |        | ![Method return type changed] |
| Modified | `public`  |          | ~~[`S3InputFile`]~~ &rarr; **[`InputFile`]** | `inputFile`([`String`])             |             |        | ![Method return type changed] |

___

<a id="user-content-dev.hardwood.s3.s3source$builder"></a>
### `dev.hardwood.s3.S3Source$Builder`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers                 | Type  | Name      | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|---------------------------|-------|-----------|------------|--------|---------------------|-----------------------|
| Modified | `final` `static` `public` | Class | `Builder` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers    | Generics | Type            | Method                               | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-----------------|--------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **[`Builder`]** | **`rangeBacking`**([`RangeBacking`]) |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`Builder`]** | **`tempDir`**([`Path`])              |             |        | ![Method added to public class] |


</details>


___

*Generated on: 2026-06-05 09:27:07.667+0000*.

[1]: # "dev.hardwood.s3.RangeBacking[]"
[Compatible]: https://img.shields.io/badge/Compatible-green "Compatible"
[Interface added]: https://img.shields.io/badge/Interface_added-orange "Interface added"
[Method added to public class]: https://img.shields.io/badge/Method_added_to_public_class-yellow "Method added to public class"
[Method return type changed]: https://img.shields.io/badge/Method_return_type_changed-red "Method return type changed"
[No changes]: https://img.shields.io/badge/No_changes-green "No changes"
[Not serializable]: https://img.shields.io/badge/Not_serializable-green "Not serializable"
[`Builder`]: # "dev.hardwood.s3.S3Source$Builder"
[`Comparable<T>`]: # "java.lang.Comparable<T extends java.lang.Object>"
[`Constable`]: # "java.lang.constant.Constable"
[`Enum<E>`]: # "java.lang.Enum<E extends java.lang.Enum<E>>"
[`InputFile`]: # "dev.hardwood.InputFile"
[`Object`]: # "java.lang.Object"
[`Path`]: # "java.nio.file.Path"
[`RangeBacking`]: # "dev.hardwood.s3.RangeBacking"
[`S3InputFile`]: # "dev.hardwood.s3.S3InputFile"
[`Serializable`]: # "java.io.Serializable"
[`String`]: # "java.lang.String"
[dev.hardwood.s3.RangeBacking]: #user-content-dev.hardwood.s3.rangebacking
[dev.hardwood.s3.S3InputFile]: #user-content-dev.hardwood.s3.s3inputfile
[dev.hardwood.s3.S3Source]: #user-content-dev.hardwood.s3.s3source
[dev.hardwood.s3.S3Source$Builder]: #user-content-dev.hardwood.s3.s3source$builder
