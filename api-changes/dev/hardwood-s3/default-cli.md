
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

| Status | Type                                             | Serialization       | Compatibility Changes |
|--------|--------------------------------------------------|---------------------|-----------------------|
| Added  | [dev.hardwood.s3.RangeBacking]                   | ![Compatible]       | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.s3.S3Credentials]                  | ![Not serializable] | ![Method added to public class] |
| Added  | [dev.hardwood.s3.S3CredentialsProvider]          | ![Not serializable] | ![Annotation added]   |
| Added  | [dev.hardwood.s3.S3InputFile]                    | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.s3.S3Source]                       | ![Not serializable] | ![Interface added] ![Method added to public class] |
| Added  | [dev.hardwood.s3.S3Source$Builder]               | ![Not serializable] | ![Method added to public class] |
| Added  | [dev.hardwood.s3.internal.Aws4Signer]            | ![Not serializable] | ![Method added to public class] |
| Added  | [dev.hardwood.s3.internal.Aws4Signer$SignResult] | ![Not serializable] | ![Method added to public class] |
| Added  | [dev.hardwood.s3.internal.S3Api]                 | ![Not serializable] | ![Method added to public class] |

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

<a id="user-content-dev.hardwood.s3.s3credentials"></a>
### `dev.hardwood.s3.S3Credentials`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                | Type      | Name                | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|--------------------------|-----------|---------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`public`** | **Class** | **`S3Credentials`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor                                             | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|---------------------------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`S3Credentials`**([`String`], [`String`], [`String`]) |             |        | ![No changes]         |


#### Methods

| Status | Modifiers                 | Generics | Type                  | Method                           | Annotations | Throws | Compatibility Changes |
|--------|---------------------------|----------|-----------------------|----------------------------------|-------------|--------|-----------------------|
| Added  | **`public`**              |          | **[`String`]**        | **`accessKeyId`**()              |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`**  |          | **`boolean`**         | **`equals`**([`Object`])         |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`**  |          | **`int`**             | **`hashCode`**()                 |             |        | ![Method added to public class] |
| Added  | **`static`** **`public`** |          | **[`S3Credentials`]** | **`of`**([`String`], [`String`]) |             |        | ![Method added to public class] |
| Added  | **`public`**              |          | **[`String`]**        | **`secretAccessKey`**()          |             |        | ![Method added to public class] |
| Added  | **`public`**              |          | **[`String`]**        | **`sessionToken`**()             |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`**  |          | **[`String`]**        | **`toString`**()                 |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.s3.s3credentialsprovider"></a>
### `dev.hardwood.s3.S3CredentialsProvider`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                   | Type          | Name                        | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|-----------------------------|---------------|-----------------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`public`** **`abstract`** | **Interface** | **`S3CredentialsProvider`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![Annotation added]   |


#### Annotations

| Status | Annotation                  | Compatibility Changes |
|--------|-----------------------------|-----------------------|
| Added  | **[`FunctionalInterface`]** | ![No changes]         |


#### Methods

| Status | Modifiers                   | Generics | Type                  | Method              | Annotations | Throws | Compatibility Changes |
|--------|-----------------------------|----------|-----------------------|---------------------|-------------|--------|-----------------------|
| Added  | **`public`** **`abstract`** |          | **[`S3Credentials`]** | **`credentials`**() |             |        | ![No changes]         |

___

<a id="user-content-dev.hardwood.s3.s3inputfile"></a>
### `dev.hardwood.s3.S3InputFile`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers    | Type      | Name              | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|--------------|-----------|-------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`public`** | **Class** | **`S3InputFile`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface             | Compatibility Changes |
|--------|-----------------------|-----------------------|
| Added  | **[`InputFile`]**     | ![No changes]         |
| Added  | **[`Closeable`]**     | ![No changes]         |
| Added  | **[`AutoCloseable`]** | ![No changes]         |


#### Methods

| Status | Modifiers    | Generics | Type               | Method                         | Annotations | Throws              | Compatibility Changes |
|--------|--------------|----------|--------------------|--------------------------------|-------------|---------------------|-----------------------|
| Added  | **`public`** |          | **`void`**         | **`close`**()                  |             | **[`IOException`]** | ![Method added to public class] |
| Added  | **`public`** |          | **`long`**         | **`length`**()                 |             |                     | ![Method added to public class] |
| Added  | **`public`** |          | **[`String`]**     | **`name`**()                   |             |                     | ![Method added to public class] |
| Added  | **`public`** |          | **`long`**         | **`networkBytesFetched`**()    |             |                     | ![Method added to public class] |
| Added  | **`public`** |          | **`long`**         | **`networkRequestCount`**()    |             |                     | ![Method added to public class] |
| Added  | **`public`** |          | **`void`**         | **`open`**()                   |             | **[`IOException`]** | ![Method added to public class] |
| Added  | **`public`** |          | **[`ByteBuffer`]** | **`readRange`**(`long`, `int`) |             | **[`IOException`]** | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.s3.s3source"></a>
### `dev.hardwood.s3.S3Source`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                | Type      | Name           | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|--------------------------|-----------|----------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`public`** | **Class** | **`S3Source`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![Interface added]    |


#### Implemented Interfaces

| Status | Interface             | Compatibility Changes |
|--------|-----------------------|-----------------------|
| Added  | **[`Closeable`]**     | ![No changes]         |
| Added  | **[`AutoCloseable`]** | ![No changes]         |


#### Methods

| Status | Modifiers                 | Generics | Type                      | Method                                              | Annotations | Throws | Compatibility Changes |
|--------|---------------------------|----------|---------------------------|-----------------------------------------------------|-------------|--------|-----------------------|
| Added  | **`static`** **`public`** |          | **[`Builder`]**           | **`builder`**()                                     |             |        | ![Method added to public class] |
| Added  | **`public`**              |          | **`void`**                | **`close`**()                                       |             |        | ![Method added to public class] |
| Added  | **`public`**              |          | **[`S3InputFile`]**       | **`inputFile`**([`String`], [`String`])             |             |        | ![Method added to public class] |
| Added  | **`public`**              |          | **[`S3InputFile`]**       | **`inputFile`**([`String`])                         |             |        | ![Method added to public class] |
| Added  | **`public`**              |          | **[`List<S3InputFile>`]** | **`inputFiles`**([`String...`])                     |             |        | ![Method added to public class] |
| Added  | **`public`**              |          | **[`List<S3InputFile>`]** | **`inputFilesInBucket`**([`String`], [`String...`]) |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.s3.s3source$builder"></a>
### `dev.hardwood.s3.S3Source$Builder`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name          | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|---------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`Builder`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers    | Generics | Type             | Method                                       | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|------------------|----------------------------------------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **[`S3Source`]** | **`build`**()                                |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`Builder`]**  | **`connectTimeout`**([`Duration`])           |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`Builder`]**  | **`credentials`**([`S3CredentialsProvider`]) |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`Builder`]**  | **`credentials`**([`S3Credentials`])         |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`Builder`]**  | **`endpoint`**([`String`])                   |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`Builder`]**  | **`httpClient`**([`HttpClient`])             |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`Builder`]**  | **`maxRetries`**(`int`)                      |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`Builder`]**  | **`pathStyle`**(`boolean`)                   |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`Builder`]**  | **`rangeBacking`**([`RangeBacking`])         |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`Builder`]**  | **`region`**([`String`])                     |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`Builder`]**  | **`requestTimeout`**([`Duration`])           |             |        | ![Method added to public class] |
| Added  | **`public`** |          | **[`Builder`]**  | **`tempDir`**([`Path`])                      |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.s3.internal.aws4signer"></a>
### `dev.hardwood.s3.internal.Aws4Signer`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                | Type      | Name             | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|--------------------------|-----------|------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`public`** | **Class** | **`Aws4Signer`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers                 | Generics | Type               | Method | Annotations | Throws | Compatibility Changes |
|--------|---------------------------|----------|--------------------|--------|-------------|--------|-----------------------|
| Added  | **`static`** **`public`** |          | **[`SignResult`]** | **`sign`**([`String`], [`URI`], [`Map<String, String>`], [`String`], [`String`], [`String`], [`String`], [`String`], [`String`], [`ZonedDateTime`]) |  |  | ![Method added to public class] |
| Added  | **`static`** **`public`** |          | **[`SignResult`]** | **`sign`**([`String`], [`URI`], [`Map<String, String>`], [`String`], [`String`], [`String`], [`String`], [`String`], [`String`], [`ZonedDateTime`], `boolean`) |  |  | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.s3.internal.aws4signer$signresult"></a>
### `dev.hardwood.s3.internal.Aws4Signer$SignResult`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                             | Type      | Name             | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|---------------------------------------|-----------|------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`static`** **`public`** | **Class** | **`SignResult`** | **[`Record`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`SignResult`**([`String`], [`String`], [`Map<String, String>`]) |  |  | ![No changes] |


#### Methods

| Status | Modifiers                | Generics | Type                        | Method                      | Annotations | Throws | Compatibility Changes |
|--------|--------------------------|----------|-----------------------------|-----------------------------|-------------|--------|-----------------------|
| Added  | **`public`**             |          | **[`String`]**              | **`authorizationHeader`**() |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`boolean`**               | **`equals`**([`Object`])    |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **`int`**                   | **`hashCode`**()            |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`Map<String, String>`]** | **`headers`**()             |             |        | ![Method added to public class] |
| Added  | **`public`**             |          | **[`String`]**              | **`timestamp`**()           |             |        | ![Method added to public class] |
| Added  | **`final`** **`public`** |          | **[`String`]**              | **`toString`**()            |             |        | ![Method added to public class] |

___

<a id="user-content-dev.hardwood.s3.internal.s3api"></a>
### `dev.hardwood.s3.internal.S3Api`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                | Type      | Name        | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|--------------------------|-----------|-------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`public`** | **Class** | **`S3Api`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Constructors

| Status | Modifiers    | Generics | Constructor | Annotations | Throws | Compatibility Changes |
|--------|--------------|----------|-------------|-------------|--------|-----------------------|
| Added  | **`public`** |          | **`S3Api`**([`HttpClient`], [`S3CredentialsProvider`], [`String`], [`URI`], `boolean`, [`Duration`], `int`) |  |  | ![No changes] |


#### Methods

| Status | Modifiers    | Generics | Type                              | Method                                              | Annotations | Throws              | Compatibility Changes |
|--------|--------------|----------|-----------------------------------|-----------------------------------------------------|-------------|---------------------|-----------------------|
| Added  | **`public`** |          | **`void`**                        | **`createBucket`**([`String`])                      |             | **[`IOException`]** | ![Method added to public class] |
| Added  | **`public`** |          | **[`HttpResponse`]**              | **`getBytes`**([`String`], [`String`], [`String`])  |             | **[`IOException`]** | ![Method added to public class] |
| Added  | **`public`** |          | **[`HttpResponse<InputStream>`]** | **`getStream`**([`String`], [`String`], [`String`]) |             | **[`IOException`]** | ![Method added to public class] |
| Added  | **`public`** |          | **[`URI`]**                       | **`objectUri`**([`String`], [`String`])             |             |                     | ![Method added to public class] |
| Added  | **`public`** |          | **`void`**                        | **`putObject`**([`String`], [`String`], `byte[]`)   |             | **[`IOException`]** | ![Method added to public class] |


</details>


___

*Generated on: 2026-06-07 19:06:22.331+0000*.

[1]: # "dev.hardwood.s3.RangeBacking[]"
[Annotation added]: https://img.shields.io/badge/Annotation_added-yellow "Annotation added"
[Compatible]: https://img.shields.io/badge/Compatible-green "Compatible"
[Interface added]: https://img.shields.io/badge/Interface_added-orange "Interface added"
[Method added to public class]: https://img.shields.io/badge/Method_added_to_public_class-yellow "Method added to public class"
[No changes]: https://img.shields.io/badge/No_changes-green "No changes"
[Not serializable]: https://img.shields.io/badge/Not_serializable-green "Not serializable"
[`AutoCloseable`]: # "java.lang.AutoCloseable"
[`Builder`]: # "dev.hardwood.s3.S3Source$Builder"
[`ByteBuffer`]: # "java.nio.ByteBuffer"
[`Closeable`]: # "java.io.Closeable"
[`Comparable<T>`]: # "java.lang.Comparable<T extends java.lang.Object>"
[`Constable`]: # "java.lang.constant.Constable"
[`Duration`]: # "java.time.Duration"
[`Enum<E>`]: # "java.lang.Enum<E extends java.lang.Enum<E>>"
[`FunctionalInterface`]: # "java.lang.FunctionalInterface"
[`HttpClient`]: # "java.net.http.HttpClient"
[`HttpResponse<InputStream>`]: # "java.net.http.HttpResponse<java.io.InputStream>"
[`HttpResponse`]: # "java.net.http.HttpResponse"
[`IOException`]: # "java.io.IOException"
[`InputFile`]: # "dev.hardwood.InputFile"
[`List<S3InputFile>`]: # "java.util.List<dev.hardwood.s3.S3InputFile>"
[`Map<String, String>`]: # "java.util.Map<java.lang.String, java.lang.String>"
[`Object`]: # "java.lang.Object"
[`Path`]: # "java.nio.file.Path"
[`RangeBacking`]: # "dev.hardwood.s3.RangeBacking"
[`Record`]: # "java.lang.Record"
[`S3CredentialsProvider`]: # "dev.hardwood.s3.S3CredentialsProvider"
[`S3Credentials`]: # "dev.hardwood.s3.S3Credentials"
[`S3InputFile`]: # "dev.hardwood.s3.S3InputFile"
[`S3Source`]: # "dev.hardwood.s3.S3Source"
[`Serializable`]: # "java.io.Serializable"
[`SignResult`]: # "dev.hardwood.s3.internal.Aws4Signer$SignResult"
[`String...`]: # "java.lang.String..."
[`String`]: # "java.lang.String"
[`URI`]: # "java.net.URI"
[`ZonedDateTime`]: # "java.time.ZonedDateTime"
[dev.hardwood.s3.RangeBacking]: #user-content-dev.hardwood.s3.rangebacking
[dev.hardwood.s3.S3Credentials]: #user-content-dev.hardwood.s3.s3credentials
[dev.hardwood.s3.S3CredentialsProvider]: #user-content-dev.hardwood.s3.s3credentialsprovider
[dev.hardwood.s3.S3InputFile]: #user-content-dev.hardwood.s3.s3inputfile
[dev.hardwood.s3.S3Source]: #user-content-dev.hardwood.s3.s3source
[dev.hardwood.s3.S3Source$Builder]: #user-content-dev.hardwood.s3.s3source$builder
[dev.hardwood.s3.internal.Aws4Signer]: #user-content-dev.hardwood.s3.internal.aws4signer
[dev.hardwood.s3.internal.Aws4Signer$SignResult]: #user-content-dev.hardwood.s3.internal.aws4signer$signresult
[dev.hardwood.s3.internal.S3Api]: #user-content-dev.hardwood.s3.internal.s3api
