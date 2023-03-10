# User Story - Key Storage

**Objective:** Keys should **never** be stored in application code. An attacker gaining read access to source code shouldn't gain knowledge of application and environment-specific secrets.


## Guidance

### Overall Guidance
- [Key Management - OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org/cheatsheets/Key_Management_Cheat_Sheet.html)
- [Cryptographic Storage - OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org/cheatsheets/Cryptographic_Storage_Cheat_Sheet.html)

### Platform Guidance
|Platform    |Article|
|----------------|-------------------------------|
|AWS     |[What is AWS Secrets Manager? - AWS Secrets Manager (amazon.com)](https://docs.aws.amazon.com/secretsmanager/latest/userguide/intro.html)            |
|Azure   |[Key and secret management in Azure - Microsoft Azure Well-Architected Framework](https://learn.microsoft.com/en-us/azure/architecture/framework/security/design-storage-keys) |
|ASP.NET|[Safe storage of app secrets in development in ASP.NET Core](https://learn.microsoft.com/en-us/aspnet/core/security/app-secrets?view=aspnetcore-7.0&tabs=windows&viewFallbackFrom=aspnetcore-2.2#access-a-secret)|


## Education

- [OWASP/wrongsecrets: Vulnerable app with examples showing how to not use secrets (github.com)](https://github.com/OWASP/wrongsecrets)

## Related Resources

- [CWE - CWE-321: Use of Hard-coded Cryptographic Key (4.10) (mitre.org)](https://cwe.mitre.org/data/definitions/321.html)
- [CRE - Ensure keys and passwords are replaceable (opencre.org)](https://www.opencre.org/cre/821-832)
- [CRE - Store cryptographic keys securely (opencre.org)](https://www.opencre.org/cre/783-255)
