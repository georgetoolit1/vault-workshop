# HashiCorp Vault WorkShop
Hashicorp Vault is a popular open-source tool which is purposely designed for secret management and data protection. The tool provides a secure and centralised way to manage sensitive information (secrets) such as API Keys, passwords, certificates and encryption keys. Vault helps organisation maintain control over their secrets by offering features such as encryption, access control and audit logging.

## Key Vault features include:
1. Secret Management: Hahsicorp Vault allows you to store and manage sensitive data securely. This includes secrets such as passwords, API Kewys and encryption keys.
2. Dynamic Secrets: Vault also allows generation of dynamic secrets on demand. For example, it can create temporary database credentials that automatically expire after a set period (ttl)
3. Encryption as a Service:
4. Access Control: Vault has the capability of granting fine-grained access control to secrets. This allows admins to define policies and roles to control who can access specific secrets or perform certain permmited operations.
5. Audit Logging: Vault logs all access and operations performed, providing a trial for compliance and security purposes.
6. Secret Rotation: One of vault's important feature is automatic rotation of secrets, helping organisations to regularly update sensitive information and improve thier security posture.
7. Integration with Other tools: Vault integrates with various identity management systems, cloud providers and other difrrent tools making it adaptable to different environment and workflows.
8. High Availablilty: Vault can be deployed in a high availability configuration to ensure that it remains accessible and in operation even in the case of hardware or network failures

## Pre-requiste
* Environment
    * macOS, Windows 11 or Linux(Ubuntu)

* Software 
    * Vault
    * Docker
    * Python3
    * jq, wget, curl 

* Cloud
    * AWS