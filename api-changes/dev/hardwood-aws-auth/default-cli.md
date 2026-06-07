
# Compatibility Report

![semver PATCH](https://img.shields.io/badge/semver-PATCH-yellow?logo=semver "semver PATCH")

## Summary

> [!IMPORTANT]
>
> Compatible bug fixes found while checking backward compatibility of version `1.0.0-SNAPSHOT` with the previous version `unknown`.

<details markdown="1">
<summary>Expand to see options used.</summary>

- **Report only summary**: No
- **Report only changes**: Yes
- **Report only binary-incompatible changes**: No
- **Access modifier filter**: `PROTECTED`
- **Old archives**:
- **New archives**:
  - ![hardwood-aws-auth 1.0.0-SNAPSHOT](https://img.shields.io/badge/hardwood_aws_auth-1.0.0_SNAPSHOT-blue "hardwood-aws-auth 1.0.0-SNAPSHOT")
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

| Status | Type                                            | Serialization       | Compatibility Changes |
|--------|-------------------------------------------------|---------------------|-----------------------|
| Added  | [dev.hardwood.aws.auth.SdkCredentialsProviders] | ![Not serializable] | ![Method added to public class] |

<details markdown="1">
<summary>Expand for details.</summary>

___

<a id="user-content-dev.hardwood.aws.auth.sdkcredentialsproviders"></a>
### `dev.hardwood.aws.auth.SdkCredentialsProviders`

- [X] Binary-compatible
- [X] Source-compatible
- [X] Serialization-compatible

| Status | Modifiers                | Type      | Name                          | Extends        | JDK        | Serialization       | Compatibility Changes |
|--------|--------------------------|-----------|-------------------------------|----------------|------------|---------------------|-----------------------|
| Added  | **`final`** **`public`** | **Class** | **`SdkCredentialsProviders`** | **[`Object`]** | **JDK 21** | ![Not serializable] | ![No changes]         |


#### Methods

| Status | Modifiers                 | Generics | Type                          | Method                        | Annotations | Throws | Compatibility Changes |
|--------|---------------------------|----------|-------------------------------|-------------------------------|-------------|--------|-----------------------|
| Added  | **`static`** **`public`** |          | **[`S3CredentialsProvider`]** | **`defaultChain`**()          |             |        | ![Method added to public class] |
| Added  | **`static`** **`public`** |          | **[`S3CredentialsProvider`]** | **`fromProfile`**([`String`]) |             |        | ![Method added to public class] |


</details>


___

*Generated on: 2026-06-07 19:06:22.556+0000*.

[Method added to public class]: https://img.shields.io/badge/Method_added_to_public_class-yellow "Method added to public class"
[No changes]: https://img.shields.io/badge/No_changes-green "No changes"
[Not serializable]: https://img.shields.io/badge/Not_serializable-green "Not serializable"
[`Object`]: # "java.lang.Object"
[`S3CredentialsProvider`]: # "dev.hardwood.s3.S3CredentialsProvider"
[`String`]: # "java.lang.String"
[dev.hardwood.aws.auth.SdkCredentialsProviders]: #user-content-dev.hardwood.aws.auth.sdkcredentialsproviders
