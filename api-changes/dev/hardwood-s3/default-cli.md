
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
  - ![hardwood-s3 1.0.0.CR1](https://img.shields.io/badge/hardwood_s3-1.0.0.CR1-blue "hardwood-s3 1.0.0.CR1")
- **New archives**:
  - ![hardwood-s3 1.0.0-SNAPSHOT](https://img.shields.io/badge/hardwood_s3-1.0.0_SNAPSHOT-blue "hardwood-s3 1.0.0-SNAPSHOT")
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

| Status   | Type                          | Serialization       | Compatibility Changes |
|----------|-------------------------------|---------------------|-----------------------|
| Modified | [dev.hardwood.s3.S3InputFile] | ![Not serializable] | ![Method now throws checked exception] |
| Modified | [dev.hardwood.s3.S3Source]    | ![Not serializable] | ![Method return type changed] ![Method return type generics changed] |

<details markdown="1">
<summary>Expand for details.</summary>

___

<a id="user-content-dev.hardwood.s3.s3inputfile"></a>
### `dev.hardwood.s3.S3InputFile`

- [X] Binary-compatible
- [ ] Source-compatible
- [X] Serialization-compatible

| Status   | Modifiers | Type  | Name          | Extends    | JDK    | Serialization       | Compatibility Changes |
|----------|-----------|-------|---------------|------------|--------|---------------------|-----------------------|
| Modified | `public`  | Class | `S3InputFile` | [`Object`] | JDK 21 | ![Not serializable] | ![No changes]         |


#### Methods

| Status   | Modifiers | Generics | Type   | Method    | Annotations | Throws              | Compatibility Changes |
|----------|-----------|----------|--------|-----------|-------------|---------------------|-----------------------|
| Modified | `public`  |          | `void` | `close`() |             | **[`IOException`]** | ![Method now throws checked exception] |

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

| Status              | Modifiers | Generics | Type                                                     | Method                                          | Annotations | Throws | Compatibility Changes |
|---------------------|-----------|----------|----------------------------------------------------------|-------------------------------------------------|-------------|--------|-----------------------|
| Modified            | `public`  |          | ~~[`InputFile`]~~ &rarr; **[`S3InputFile`]**             | `inputFile`([`String`], [`String`])             |             |        | ![Method return type changed] |
| Modified            | `public`  |          | ~~[`InputFile`]~~ &rarr; **[`S3InputFile`]**             | `inputFile`([`String`])                         |             |        | ![Method return type changed] |
| Source-incompatible | `public`  |          | ~~[`List<InputFile>`]~~ &rarr; **[`List<S3InputFile>`]** | `inputFiles`([`String...`])                     |             |        | ![Method return type generics changed] |
| Source-incompatible | `public`  |          | ~~[`List<InputFile>`]~~ &rarr; **[`List<S3InputFile>`]** | `inputFilesInBucket`([`String`], [`String...`]) |             |        | ![Method return type generics changed] |


</details>


___

*Generated on: 2026-06-07 18:54:53.910+0000*.

[Method now throws checked exception]: https://img.shields.io/badge/Method_now_throws_checked_exception-orange "Method now throws checked exception"
[Method return type changed]: https://img.shields.io/badge/Method_return_type_changed-red "Method return type changed"
[Method return type generics changed]: https://img.shields.io/badge/Method_return_type_generics_changed-orange "Method return type generics changed"
[No changes]: https://img.shields.io/badge/No_changes-green "No changes"
[Not serializable]: https://img.shields.io/badge/Not_serializable-green "Not serializable"
[`IOException`]: # "java.io.IOException"
[`InputFile`]: # "dev.hardwood.InputFile"
[`List<InputFile>`]: # "java.util.List<dev.hardwood.InputFile>"
[`List<S3InputFile>`]: # "java.util.List<dev.hardwood.s3.S3InputFile>"
[`Object`]: # "java.lang.Object"
[`S3InputFile`]: # "dev.hardwood.s3.S3InputFile"
[`String...`]: # "java.lang.String..."
[`String`]: # "java.lang.String"
[dev.hardwood.s3.S3InputFile]: #user-content-dev.hardwood.s3.s3inputfile
[dev.hardwood.s3.S3Source]: #user-content-dev.hardwood.s3.s3source
