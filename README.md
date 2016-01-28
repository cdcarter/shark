# shark

shark is a tool for salesforce consultants

# why we import cumulusci
```
<macrodef name="installPackage" description="Installs the given managed package">
<macrodef name="uninstallPackage" description="Uninstalls the given managed package">
<macrodef name="getPackageVersion" description="Sets the InstalledPackage.NAMESPACE.versionNumber property to the version number of the package">
<macrodef name="updatePackageVersion" description="Installs a specific version of a package.  If the package needs to be downgraded, first uninstalls the package.">
<macrodef name="retrieveUnpackaged" description="Retrieves all unpackaged metadata from the target org into the specified dir">
<macrodef name="retrieveAdminProfile" description="Retrieves the Admin.profile from the target org into the specified dir">
<macrodef name="updateAdminProfileGrantFLS" description="Updates the Admin.profile to grant all FLS">
<macrodef name="deleteWhitelistedMetadata" description="Deletes any metadata files from a given directory which are listed in /build/whitelists/metadata.txt">
<macrodef name="retrievePackaged" description="Retrieves all metadata from a given package into the specified dir">
<macrodef name="buildPackageXmlFromDir" description="Runs through a directory of metadata and builds a package.xml format file from the contents">
<macrodef name="getWhitelistForObjectAndType" description="Given an object and a type, returns the whitelist for the type if set">
<macrodef name="addMetadataSubType" description="Uses an xsl template to parse out metadata subtypes from a parent file and adds to a package.xml file">
<macrodef name="buildPackageXml" description="Construct a complete package.xml file based on the metadata in the src directory">
<macrodef name="buildDestroyStaleMetadata" description="Constructs a destructiveChanges.xml which deletes any metadata from one directory which does not exist in another">
<macrodef name="buildPackagedDestructiveChanges" description="Constructs a destructiveChanges.xml file which deletes all metadata from a package">
<macrodef name="buildUnpackagedDestructiveChanges" description="Construct two packages.  The first package resets standard object ActionOverrides to type Default.  The second uses a custom built destructiveChanges.xml file to delete all unpackaged metadata">
<macrodef name="updateMetaXml" description="Updates all references to a given namespace in *-meta.xml files to a specific version">
<macrodef name="updateMetaXmlApi" description="Updates all apiVersion elements in all *-meta.xml files in target directory">
<macrodef name="deployMetadataBundles" description="Deploys all subfolders of a given dir as individual metadata bundles replacing %%%NAMESPACE%%% with either blank or a namespace prefix in all files">
<macrodef name="zipMetadataBundles" description="Zips all subfolders of a given dir as individual metadata bundles replacing %%%NAMESPACE%%% with either blank or a namespace prefix in all files">
<macrodef name="replaceNamespacePrefix" description="Replaces all instances of the string %%%NAMESPACE%%% with the provided namespace prefix in the target directory">
<macrodef name="stripManagedToken" description="Strips all instances of //cumulusci-managed from all apex code in the target directory">
<macrodef name="prepareSrcForUnm
nagedEE" description="Modifies the src directory to prepare it for deployment as unmanaged code to an EE org">
```
