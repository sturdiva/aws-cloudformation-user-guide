# Amazon AppStream 2\.0 Fleet DomainJoinInfo<a name="aws-properties-appstream-fleet-domainjoininfo"></a>

<a name="aws-properties-appstream-fleet-domainjoininfo-description"></a>The `DomainJoinInfo` property type specifies the name of the directory and organizational unit \(OU\) to use to join an Amazon AppStream 2\.0 fleet to a Microsoft Active Directory domain\.

<a name="aws-properties-appstream-fleet-domainjoininfo-inheritance"></a> `DomainJoinInfo` is a property of the [AWS::AppStream::Fleet](aws-resource-appstream-fleet.md) resource\.

## Syntax<a name="aws-properties-appstream-fleet-domainjoininfo-syntax"></a>

To declare this entity in your AWS CloudFormation template, use the following syntax:

### JSON<a name="aws-properties-appstream-fleet-domainjoininfo-syntax.json"></a>

```
{
  "[DirectoryName](#cfn-appstream-fleet-domainjoininfo-directoryname)" : String,
  "[OrganizationalUnitDistinguishedName](#cfn-appstream-fleet-domainjoininfo-organizationalunitdistinguishedname)" : String
}
```

### YAML<a name="aws-properties-appstream-fleet-domainjoininfo-syntax.yaml"></a>

```
[DirectoryName](#cfn-appstream-fleet-domainjoininfo-directoryname): String  
[OrganizationalUnitDistinguishedName](#cfn-appstream-fleet-domainjoininfo-organizationalunitdistinguishedname): String
```

## Properties<a name="aws-properties-appstream-fleet-domainjoininfo-properties"></a>

`DirectoryName`  <a name="cfn-appstream-fleet-domainjoininfo-directoryname"></a>
The fully qualified name of the directory \(for example, corp\.example\.com\)\.  
 *Required*: No  
 *Type*: String  
 *Update requires*: [No interruption](using-cfn-updating-stacks-update-behaviors.md#update-no-interrupt) 

`OrganizationalUnitDistinguishedName`  <a name="cfn-appstream-fleet-domainjoininfo-organizationalunitdistinguishedname"></a>
The distinguished name of the organizational unit for computer accounts\.  
 *Required*: No  
 *Type*: String  
 *Update requires*: [No interruption](using-cfn-updating-stacks-update-behaviors.md#update-no-interrupt) 