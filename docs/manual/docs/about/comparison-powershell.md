# Comparison to SharePoint PowerShell

Following table lists the different Office 365 CLI commands and how they map to SharePoint Online Management Shell and PnP PowerShell cmdlets.

PowerShell Cmdlet|Source|Office 365 CLI command
-----------------|------|----------------------
Add-SPOGeoAdministrator|Microsoft.Online.SharePoint.PowerShell|
Add-SPOSiteCollectionAppCatalog|Microsoft.Online.SharePoint.PowerShell|[spo site appcatalog add](../cmd/spo/site/site-appcatalog-add.md)
Add-SPOSiteDesign|Microsoft.Online.SharePoint.PowerShell|
Add-SPOSiteScript|Microsoft.Online.SharePoint.PowerShell|
Add-SPOTenantCdnOrigin|Microsoft.Online.SharePoint.PowerShell|[spo cdn origin add](../cmd/spo/cdn/cdn-origin-add.md)
Add-SPOTheme|Microsoft.Online.SharePoint.PowerShell|
Add-SPOUser|Microsoft.Online.SharePoint.PowerShell|
Approve-SPOTenantServicePrincipalPermissionRequest|Microsoft.Online.SharePoint.PowerShell|[spo serviceprincipal permissionrequest approve](../cmd/spo/serviceprincipal/serviceprincipal-permissionrequest-approve.md)
Connect-SPOHubSite|Microsoft.Online.SharePoint.PowerShell|
Connect-SPOService|Microsoft.Online.SharePoint.PowerShell|[spo connect](../cmd/spo/connect.md)
ConvertTo-SPOMigrationEncryptedPackage|Microsoft.Online.SharePoint.PowerShell|
ConvertTo-SPOMigrationTargetedPackage|Microsoft.Online.SharePoint.PowerShell|
Deny-SPOTenantServicePrincipalPermissionRequest|Microsoft.Online.SharePoint.PowerShell|[spo serviceprincipal permissionrequest deny](../cmd/spo/serviceprincipal/serviceprincipal-permissionrequest-deny.md)
Disable-SPOTenantServicePrincipal|Microsoft.Online.SharePoint.PowerShell|[spo serviceprincipal set](../cmd/spo/serviceprincipal/serviceprincipal-set.md)
Disconnect-SPOHubSite|Microsoft.Online.SharePoint.PowerShell|
Disconnect-SPOService|Microsoft.Online.SharePoint.PowerShell|[spo disconnect](../cmd/spo/disconnect.md)
Enable-SPOTenantServicePrincipal|Microsoft.Online.SharePoint.PowerShell|[spo serviceprincipal set](../cmd/spo/serviceprincipal/serviceprincipal-set.md)
Get-SPOAppErrors|Microsoft.Online.SharePoint.PowerShell|
Get-SPOAppInfo|Microsoft.Online.SharePoint.PowerShell|
Get-SPOBrowserIdleSignOut|Microsoft.Online.SharePoint.PowerShell|
Get-SPOCrossGeoMovedUsers|Microsoft.Online.SharePoint.PowerShell|
Get-SPOCrossGeoMoveReport|Microsoft.Online.SharePoint.PowerShell|
Get-SPOCrossGeoUsers|Microsoft.Online.SharePoint.PowerShell|
Get-SPODataEncryptionPolicy|Microsoft.Online.SharePoint.PowerShell|
Get-SPODeletedSite|Microsoft.Online.SharePoint.PowerShell|
Get-SPOExternalUser|Microsoft.Online.SharePoint.PowerShell|[spo externaluser list](../cmd/spo/externaluser/externaluser-list.md)
Get-SPOGeoAdministrator|Microsoft.Online.SharePoint.PowerShell|
Get-SPOGeoMoveCompatibilityStatus|Microsoft.Online.SharePoint.PowerShell|
Get-SPOGeoMoveCrossCompatibilityStatus|Microsoft.Online.SharePoint.PowerShell|
Get-SPOGeoStorageQuota|Microsoft.Online.SharePoint.PowerShell|
Get-SPOHideDefaultThemes|Microsoft.Online.SharePoint.PowerShell|
Get-SPOHubSite|Microsoft.Online.SharePoint.PowerShell|
Get-SPOMigrationJobProgress|Microsoft.Online.SharePoint.PowerShell|
Get-SPOMigrationJobStatus|Microsoft.Online.SharePoint.PowerShell|
Get-SPOMultiGeoExperience|Microsoft.Online.SharePoint.PowerShell|
Get-SPOPublicCdnOrigins|Microsoft.Online.SharePoint.PowerShell|
Get-SPOSite|Microsoft.Online.SharePoint.PowerShell|
Get-SPOSiteContentMoveState|Microsoft.Online.SharePoint.PowerShell|
Get-SPOSiteDataEncryptionPolicy|Microsoft.Online.SharePoint.PowerShell|
Get-SPOSiteDesign|Microsoft.Online.SharePoint.PowerShell|
Get-SPOSiteDesignRights|Microsoft.Online.SharePoint.PowerShell|
Get-SPOSiteGroup|Microsoft.Online.SharePoint.PowerShell|
Get-SPOSiteScript|Microsoft.Online.SharePoint.PowerShell|
Get-SPOStorageEntity|Microsoft.Online.SharePoint.PowerShell|[spo storageentity get](../cmd/spo/storageentity/storageentity-get.md), [spo storageentity list](../cmd/spo/storageentity/storageentity-list.md)
Get-SPOTenant|Microsoft.Online.SharePoint.PowerShell|
Get-SPOTenantCdnEnabled|Microsoft.Online.SharePoint.PowerShell|[spo cdn get](../cmd/spo/cdn/cdn-get.md)
Get-SPOTenantCdnOrigins|Microsoft.Online.SharePoint.PowerShell|[spo cdn origin list](../cmd/spo/cdn/cdn-origin-list.md)
Get-SPOTenantCdnPolicies|Microsoft.Online.SharePoint.PowerShell|[spo cdn policy list](../cmd/spo/cdn/cdn-policy-list.md)
Get-SPOTenantContentTypeReplicationParameters|Microsoft.Online.SharePoint.PowerShell|
Get-SPOTenantLogEntry|Microsoft.Online.SharePoint.PowerShell|
Get-SPOTenantLogLastAvailableTimeInUtc|Microsoft.Online.SharePoint.PowerShell|
Get-SPOTenantServicePrincipalPermissionGrants|Microsoft.Online.SharePoint.PowerShell|[spo serviceprincipal grant list](../cmd/spo/serviceprincipal/serviceprincipal-grant-list.md)
Get-SPOTenantServicePrincipalPermissionRequests|Microsoft.Online.SharePoint.PowerShell|[spo serviceprincipal permissionrequest list](../cmd/spo/serviceprincipal/serviceprincipal-permissionrequest-list.md)
Get-SPOTenantSyncClientRestriction|Microsoft.Online.SharePoint.PowerShell|
Get-SPOTenantTaxonomyReplicationParameters|Microsoft.Online.SharePoint.PowerShell|
Get-SPOTheme|Microsoft.Online.SharePoint.PowerShell|
Get-SPOUser|Microsoft.Online.SharePoint.PowerShell|
Get-SPOUserAndContentMoveState|Microsoft.Online.SharePoint.PowerShell|
Get-SPOUserOneDriveLocation|Microsoft.Online.SharePoint.PowerShell|
Get-SPOWebTemplate|Microsoft.Online.SharePoint.PowerShell|
Grant-SPOHubSiteRights|Microsoft.Online.SharePoint.PowerShell|
Grant-SPOSiteDesignRights|Microsoft.Online.SharePoint.PowerShell|
Invoke-SPOMigrationEncryptUploadSubmit|Microsoft.Online.SharePoint.PowerShell|
New-SPOMigrationEncryptionParameters|Microsoft.Online.SharePoint.PowerShell|
New-SPOMigrationPackage|Microsoft.Online.SharePoint.PowerShell|
New-SPOPublicCdnOrigin|Microsoft.Online.SharePoint.PowerShell|
New-SPOSdnProvider|Microsoft.Online.SharePoint.PowerShell|
New-SPOSite|Microsoft.Online.SharePoint.PowerShell|[spo site add](../cmd/spo/site/site-add.md)
New-SPOSiteGroup|Microsoft.Online.SharePoint.PowerShell|
Register-SPODataEncryptionPolicy|Microsoft.Online.SharePoint.PowerShell|
Register-SPOHubSite|Microsoft.Online.SharePoint.PowerShell|
Remove-SPODeletedSite|Microsoft.Online.SharePoint.PowerShell|
Remove-SPOExternalUser|Microsoft.Online.SharePoint.PowerShell|
Remove-SPOGeoAdministrator|Microsoft.Online.SharePoint.PowerShell|
Remove-SPOMigrationJob|Microsoft.Online.SharePoint.PowerShell|
Remove-SPOPublicCdnOrigin|Microsoft.Online.SharePoint.PowerShell|
Remove-SPOSdnProvider|Microsoft.Online.SharePoint.PowerShell|
Remove-SPOSite|Microsoft.Online.SharePoint.PowerShell|
Remove-SPOSiteCollectionAppCatalog|Microsoft.Online.SharePoint.PowerShell|[spo site appcatalog remove](../cmd/spo/site/site-appcatalog-remove.md)
Remove-SPOSiteCollectionAppCatalogById|Microsoft.Online.SharePoint.PowerShell|
Remove-SPOSiteDesign|Microsoft.Online.SharePoint.PowerShell|
Remove-SPOSiteGroup|Microsoft.Online.SharePoint.PowerShell|
Remove-SPOSiteScript|Microsoft.Online.SharePoint.PowerShell|
Remove-SPOStorageEntity|Microsoft.Online.SharePoint.PowerShell|[spo storageentity remove](../cmd/spo/storageentity/storageentity-remove.md)
Remove-SPOTenantCdnOrigin|Microsoft.Online.SharePoint.PowerShell|[spo cdn origin remove](../cmd/spo/cdn/cdn-origin-remove.md)
Remove-SPOTenantSyncClientRestriction|Microsoft.Online.SharePoint.PowerShell|
Remove-SPOTheme|Microsoft.Online.SharePoint.PowerShell|
Remove-SPOUser|Microsoft.Online.SharePoint.PowerShell|
Repair-SPOSite|Microsoft.Online.SharePoint.PowerShell|
Request-SPOPersonalSite|Microsoft.Online.SharePoint.PowerShell|
Request-SPOUpgradeEvaluationSite|Microsoft.Online.SharePoint.PowerShell|
Restore-SPODataEncryptionPolicy|Microsoft.Online.SharePoint.PowerShell|
Restore-SPODeletedSite|Microsoft.Online.SharePoint.PowerShell|
Revoke-SPOHubSiteRights|Microsoft.Online.SharePoint.PowerShell|
Revoke-SPOSiteDesignRights|Microsoft.Online.SharePoint.PowerShell|
Revoke-SPOTenantServicePrincipalPermission|Microsoft.Online.SharePoint.PowerShell|[spo serviceprincipal grant revoke](../cmd/spo/serviceprincipal/serviceprincipal-grant-revoke.md)
Revoke-SPOUserSession|Microsoft.Online.SharePoint.PowerShell|
Set-SPOBrowserIdleSignOut|Microsoft.Online.SharePoint.PowerShell|
Set-SPOGeoStorageQuota|Microsoft.Online.SharePoint.PowerShell|
Set-SPOHideDefaultThemes|Microsoft.Online.SharePoint.PowerShell|
Set-SPOHubSite|Microsoft.Online.SharePoint.PowerShell|
Set-SPOMigrationPackageAzureSource|Microsoft.Online.SharePoint.PowerShell|
Set-SPOMultiGeoExperience|Microsoft.Online.SharePoint.PowerShell|
Set-SPOSite|Microsoft.Online.SharePoint.PowerShell|
Set-SPOSiteGroup|Microsoft.Online.SharePoint.PowerShell|
Set-SPOSiteOffice365Group|Microsoft.Online.SharePoint.PowerShell|
Set-SPOStorageEntity|Microsoft.Online.SharePoint.PowerShell|[spo storageentity set](../cmd/spo/storageentity/storageentity-set.md)
Set-SPOTenant|Microsoft.Online.SharePoint.PowerShell|
Set-SPOTenantCdnEnabled|Microsoft.Online.SharePoint.PowerShell|[spo cdn set](../cmd/spo/cdn/cdn-set.md)
Set-SPOTenantCdnPolicy|Microsoft.Online.SharePoint.PowerShell|[spo cdn policy set](../cmd/spo/cdn/cdn-policy-set.md)
Set-SPOTenantContentTypeReplicationParameters|Microsoft.Online.SharePoint.PowerShell|
Set-SPOTenantSyncClientRestriction|Microsoft.Online.SharePoint.PowerShell|
Set-SPOTenantTaxonomyReplicationParameters|Microsoft.Online.SharePoint.PowerShell|
Set-SPOUser|Microsoft.Online.SharePoint.PowerShell|
Start-SPOSiteContentMove|Microsoft.Online.SharePoint.PowerShell|
Start-SPOUserAndContentMove|Microsoft.Online.SharePoint.PowerShell|
Stop-SPOUserAndContentMove|Microsoft.Online.SharePoint.PowerShell|
Submit-SPOMigrationJob|Microsoft.Online.SharePoint.PowerShell|
Test-SPOSite|Microsoft.Online.SharePoint.PowerShell|
Unregister-SPOHubSite|Microsoft.Online.SharePoint.PowerShell|
Update-SPODataEncryptionPolicy|Microsoft.Online.SharePoint.PowerShell|
Upgrade-SPOSite|Microsoft.Online.SharePoint.PowerShell|
Add-PnPApp|SharePointPnPPowerShellOnline|[spo app add](../cmd/spo/app/app-add.md)
Add-PnPClientSidePage|SharePointPnPPowerShellOnline|
Add-PnPClientSidePageSection|SharePointPnPPowerShellOnline|
Add-PnPClientSideText|SharePointPnPPowerShellOnline|
Add-PnPClientSideWebPart|SharePointPnPPowerShellOnline|
Add-PnPContentType|SharePointPnPPowerShellOnline|
Add-PnPContentTypeToDocumentSet|SharePointPnPPowerShellOnline|
Add-PnPContentTypeToList|SharePointPnPPowerShellOnline|
Add-PnPCustomAction|SharePointPnPPowerShellOnline|[spo customaction add](../cmd/spo/customaction/customaction-add.md)
Add-PnPDataRowsToProvisioningTemplate|SharePointPnPPowerShellOnline|
Add-PnPDocumentSet|SharePointPnPPowerShellOnline|
Add-PnPEventReceiver|SharePointPnPPowerShellOnline|
Add-PnPField|SharePointPnPPowerShellOnline|
Add-PnPFieldFromXml|SharePointPnPPowerShellOnline|
Add-PnPFieldToContentType|SharePointPnPPowerShellOnline|
Add-PnPFile|SharePointPnPPowerShellOnline|
Add-PnPFileToProvisioningTemplate|SharePointPnPPowerShellOnline|
Add-PnPFolder|SharePointPnPPowerShellOnline|
Add-PnPHtmlPublishingPageLayout|SharePointPnPPowerShellOnline|
Add-PnPIndexedProperty|SharePointPnPPowerShellOnline|
Add-PnPJavaScriptBlock|SharePointPnPPowerShellOnline|
Add-PnPJavaScriptLink|SharePointPnPPowerShellOnline|
Add-PnPListFoldersToProvisioningTemplate|SharePointPnPPowerShellOnline|
Add-PnPListItem|SharePointPnPPowerShellOnline|
Add-PnPMasterPage|SharePointPnPPowerShellOnline|
Add-PnPNavigationNode|SharePointPnPPowerShellOnline|
Add-PnPOffice365GroupToSite|SharePointPnPPowerShellOnline|
Add-PnPPublishingImageRendition|SharePointPnPPowerShellOnline|
Add-PnPPublishingPage|SharePointPnPPowerShellOnline|
Add-PnPPublishingPageLayout|SharePointPnPPowerShellOnline|
Add-PnPSiteClassification|SharePointPnPPowerShellOnline|
Add-PnPSiteCollectionAdmin|SharePointPnPPowerShellOnline|
Add-PnPSiteDesign|SharePointPnPPowerShellOnline|
Add-PnPSiteScript|SharePointPnPPowerShellOnline|
Add-PnPTaxonomyField|SharePointPnPPowerShellOnline|
Add-PnPUserToGroup|SharePointPnPPowerShellOnline|
Add-PnPView|SharePointPnPPowerShellOnline|
Add-PnPWebhookSubscription|SharePointPnPPowerShellOnline|
Add-PnPWebPartToWebPartPage|SharePointPnPPowerShellOnline|
Add-PnPWebPartToWikiPage|SharePointPnPPowerShellOnline|
Add-PnPWikiPage|SharePointPnPPowerShellOnline|
Add-PnPWorkflowDefinition|SharePointPnPPowerShellOnline|
Add-PnPWorkflowSubscription|SharePointPnPPowerShellOnline|
Apply-PnPProvisioningTemplate|SharePointPnPPowerShellOnline|
Clear-PnPListItemAsRecord|SharePointPnPPowerShellOnline|
Clear-PnPRecycleBinItem|SharePointPnPPowerShellOnline|
Clear-PnPTenantRecycleBinItem|SharePointPnPPowerShellOnline|
Connect-PnPMicrosoftGraph|SharePointPnPPowerShellOnline|
Connect-PnPOnline|SharePointPnPPowerShellOnline|[spo connect](../cmd/spo/connect.md)
Convert-PnPFolderToProvisioningTemplate|SharePointPnPPowerShellOnline|
Convert-PnPProvisioningTemplate|SharePointPnPPowerShellOnline|
Copy-PnPFile|SharePointPnPPowerShellOnline|
Copy-PnPItemProxy|SharePointPnPPowerShellOnline|
Disable-PnPFeature|SharePointPnPPowerShellOnline|
Disable-PnPInPlaceRecordsManagementForSite|SharePointPnPPowerShellOnline|
Disable-PnPResponsiveUI|SharePointPnPPowerShellOnline|
Disable-PnPSiteClassification|SharePointPnPPowerShellOnline|
Disconnect-PnPOnline|SharePointPnPPowerShellOnline|[spo disconnect](../cmd/spo/disconnect.md)
Enable-PnPFeature|SharePointPnPPowerShellOnline|
Enable-PnPInPlaceRecordsManagementForSite|SharePointPnPPowerShellOnline|
Enable-PnPResponsiveUI|SharePointPnPPowerShellOnline|
Enable-PnPSiteClassification|SharePointPnPPowerShellOnline|
Ensure-PnPFolder|SharePointPnPPowerShellOnline|
Execute-PnPQuery|SharePointPnPPowerShellOnline|
Export-PnPTaxonomy|SharePointPnPPowerShellOnline|
Export-PnPTermGroupToXml|SharePointPnPPowerShellOnline|
Find-PnPFile|SharePointPnPPowerShellOnline|
Get-PnPAccessToken|SharePointPnPPowerShellOnline|
Get-PnPApp|SharePointPnPPowerShellOnline|[spo app get](../cmd/spo/app/app-get.md), [spo app list](../cmd/spo/app/app-list.md)
Get-PnPAppAuthAccessToken|SharePointPnPPowerShellOnline|
Get-PnPAppInstance|SharePointPnPPowerShellOnline|
Get-PnPAuditing|SharePointPnPPowerShellOnline|
Get-PnPAuthenticationRealm|SharePointPnPPowerShellOnline|
Get-PnPAvailableClientSideComponents|SharePointPnPPowerShellOnline|
Get-PnPAzureADManifestKeyCredentials|SharePointPnPPowerShellOnline|
Get-PnPClientSideComponent|SharePointPnPPowerShellOnline|
Get-PnPClientSidePage|SharePointPnPPowerShellOnline|
Get-PnPConnection|SharePointPnPPowerShellOnline|
Get-PnPContentType|SharePointPnPPowerShellOnline|
Get-PnPContentTypePublishingHubUrl|SharePointPnPPowerShellOnline|
Get-PnPContext|SharePointPnPPowerShellOnline|
Get-PnPCustomAction|SharePointPnPPowerShellOnline|[spo customaction get](../cmd/spo/customaction/customaction-get.md), [spo customaction list](../cmd/spo/customaction/customaction-list.md)
Get-PnPDefaultColumnValues|SharePointPnPPowerShellOnline|
Get-PnPDocumentSetTemplate|SharePointPnPPowerShellOnline|
Get-PnPEventReceiver|SharePointPnPPowerShellOnline|
Get-PnPFeature|SharePointPnPPowerShellOnline|
Get-PnPField|SharePointPnPPowerShellOnline|
Get-PnPFile|SharePointPnPPowerShellOnline|
Get-PnPFolder|SharePointPnPPowerShellOnline|
Get-PnPFolderItem|SharePointPnPPowerShellOnline|
Get-PnPGroup|SharePointPnPPowerShellOnline|
Get-PnPGroupMembers|SharePointPnPPowerShellOnline|
Get-PnPGroupPermissions|SharePointPnPPowerShellOnline|
Get-PnPHealthScore|SharePointPnPPowerShellOnline|
Get-PnPHomePage|SharePointPnPPowerShellOnline|
Get-PnPIndexedPropertyKeys|SharePointPnPPowerShellOnline|
Get-PnPJavaScriptLink|SharePointPnPPowerShellOnline|
Get-PnPList|SharePointPnPPowerShellOnline|
Get-PnPListItem|SharePointPnPPowerShellOnline|
Get-PnPMasterPage|SharePointPnPPowerShellOnline|
Get-PnPProperty|SharePointPnPPowerShellOnline|
Get-PnPPropertyBag|SharePointPnPPowerShellOnline|
Get-PnPProvisioningTemplate|SharePointPnPPowerShellOnline|
Get-PnPProvisioningTemplateFromGallery|SharePointPnPPowerShellOnline|
Get-PnPPublishingImageRendition|SharePointPnPPowerShellOnline|
Get-PnPRecycleBinItem|SharePointPnPPowerShellOnline|
Get-PnPRequestAccessEmails|SharePointPnPPowerShellOnline|
Get-PnPSearchConfiguration|SharePointPnPPowerShellOnline|
Get-PnPSite|SharePointPnPPowerShellOnline|[spo site get](../cmd/spo/site/site-get.md), [spo site list](../cmd/spo/site/site-list.md)
Get-PnPSiteClassification|SharePointPnPPowerShellOnline|
Get-PnPSiteClosure|SharePointPnPPowerShellOnline|
Get-PnPSiteCollectionAdmin|SharePointPnPPowerShellOnline|
Get-PnPSiteCollectionTermStore|SharePointPnPPowerShellOnline|
Get-PnPSiteDesign|SharePointPnPPowerShellOnline|
Get-PnPSiteDesignRights|SharePointPnPPowerShellOnline|
Get-PnPSitePolicy|SharePointPnPPowerShellOnline|
Get-PnPSiteScript|SharePointPnPPowerShellOnline|
Get-PnPSiteSearchQueryResults|SharePointPnPPowerShellOnline|
Get-PnPStorageEntity|SharePointPnPPowerShellOnline|[spo storageentity get](../cmd/spo/storageentity/storageentity-get.md), [spo storageentity list](../cmd/spo/storageentity/storageentity-list.md)
Get-PnPStoredCredential|SharePointPnPPowerShellOnline|
Get-PnPSubWebs|SharePointPnPPowerShellOnline|
Get-PnPTaxonomyItem|SharePointPnPPowerShellOnline|
Get-PnPTaxonomySession|SharePointPnPPowerShellOnline|
Get-PnPTenantRecycleBinItem|SharePointPnPPowerShellOnline|
Get-PnPTenantSite|SharePointPnPPowerShellOnline|
Get-PnPTerm|SharePointPnPPowerShellOnline|
Get-PnPTermGroup|SharePointPnPPowerShellOnline|
Get-PnPTermSet|SharePointPnPPowerShellOnline|
Get-PnPTheme|SharePointPnPPowerShellOnline|
Get-PnPTimeZoneId|SharePointPnPPowerShellOnline|
Get-PnPUnifiedGroup|SharePointPnPPowerShellOnline|
Get-PnPUser|SharePointPnPPowerShellOnline|
Get-PnPUserProfileProperty|SharePointPnPPowerShellOnline|
Get-PnPView|SharePointPnPPowerShellOnline|
Get-PnPWeb|SharePointPnPPowerShellOnline|
Get-PnPWebhookSubscriptions|SharePointPnPPowerShellOnline|
Get-PnPWebPart|SharePointPnPPowerShellOnline|
Get-PnPWebPartProperty|SharePointPnPPowerShellOnline|
Get-PnPWebPartXml|SharePointPnPPowerShellOnline|
Get-PnPWebTemplates|SharePointPnPPowerShellOnline|
Get-PnPWikiPageContent|SharePointPnPPowerShellOnline|
Get-PnPWorkflowDefinition|SharePointPnPPowerShellOnline|
Get-PnPWorkflowSubscription|SharePointPnPPowerShellOnline|
Grant-PnPSiteDesignRights|SharePointPnPPowerShellOnline|
Import-PnPAppPackage|SharePointPnPPowerShellOnline|
Import-PnPTaxonomy|SharePointPnPPowerShellOnline|
Import-PnPTermGroupFromXml|SharePointPnPPowerShellOnline|
Import-PnPTermSet|SharePointPnPPowerShellOnline|
Install-PnPApp|SharePointPnPPowerShellOnline|[spo app install](../cmd/spo/app/app-install.md)
Install-PnPSolution|SharePointPnPPowerShellOnline|
Invoke-PnPWebAction|SharePointPnPPowerShellOnline|
Load-PnPProvisioningTemplate|SharePointPnPPowerShellOnline|
Measure-PnPList|SharePointPnPPowerShellOnline|
Measure-PnPResponseTime|SharePointPnPPowerShellOnline|
Measure-PnPWeb|SharePointPnPPowerShellOnline|
Move-PnPClientSideComponent|SharePointPnPPowerShellOnline|
Move-PnPFile|SharePointPnPPowerShellOnline|
Move-PnPFolder|SharePointPnPPowerShellOnline|
Move-PnPItemProxy|SharePointPnPPowerShellOnline|
Move-PnPListItemToRecycleBin|SharePointPnPPowerShellOnline|
Move-PnPRecycleBinItem|SharePointPnPPowerShellOnline|
New-PnPExtensbilityHandlerObject|SharePointPnPPowerShellOnline|
New-PnPGroup|SharePointPnPPowerShellOnline|
New-PnPList|SharePointPnPPowerShellOnline|
New-PnPPersonalSite|SharePointPnPPowerShellOnline|
New-PnPProvisioningTemplate|SharePointPnPPowerShellOnline|
New-PnPProvisioningTemplateFromFolder|SharePointPnPPowerShellOnline|
New-PnPSite|SharePointPnPPowerShellOnline|[spo site add](../cmd/spo/site/site-add.md)
New-PnPTenantSite|SharePointPnPPowerShellOnline|
New-PnPTerm|SharePointPnPPowerShellOnline|
New-PnPTermGroup|SharePointPnPPowerShellOnline|
New-PnPTermSet|SharePointPnPPowerShellOnline|
New-PnPUnifiedGroup|SharePointPnPPowerShellOnline|
New-PnPUser|SharePointPnPPowerShellOnline|
New-PnPWeb|SharePointPnPPowerShellOnline|
Publish-PnPApp|SharePointPnPPowerShellOnline|[spo app deploy](../cmd/spo/app/app-deploy.md)
Remove-PnPApp|SharePointPnPPowerShellOnline|[spo app remove](../cmd/spo/app/app-remove.md)
Remove-PnPClientSideComponent|SharePointPnPPowerShellOnline|
Remove-PnPClientSidePage|SharePointPnPPowerShellOnline|
Remove-PnPContentType|SharePointPnPPowerShellOnline|
Remove-PnPContentTypeFromDocumentSet|SharePointPnPPowerShellOnline|
Remove-PnPContentTypeFromList|SharePointPnPPowerShellOnline|
Remove-PnPCustomAction|SharePointPnPPowerShellOnline|
Remove-PnPEventReceiver|SharePointPnPPowerShellOnline|
Remove-PnPField|SharePointPnPPowerShellOnline|
Remove-PnPFieldFromContentType|SharePointPnPPowerShellOnline|
Remove-PnPFile|SharePointPnPPowerShellOnline|
Remove-PnPFileFromProvisioningTemplate|SharePointPnPPowerShellOnline|
Remove-PnPFolder|SharePointPnPPowerShellOnline|
Remove-PnPGroup|SharePointPnPPowerShellOnline|
Remove-PnPIndexedProperty|SharePointPnPPowerShellOnline|
Remove-PnPJavaScriptLink|SharePointPnPPowerShellOnline|
Remove-PnPList|SharePointPnPPowerShellOnline|
Remove-PnPListItem|SharePointPnPPowerShellOnline|
Remove-PnPNavigationNode|SharePointPnPPowerShellOnline|
Remove-PnPPropertyBagValue|SharePointPnPPowerShellOnline|
Remove-PnPPublishingImageRendition|SharePointPnPPowerShellOnline|
Remove-PnPSiteClassification|SharePointPnPPowerShellOnline|
Remove-PnPSiteCollectionAdmin|SharePointPnPPowerShellOnline|
Remove-PnPSiteDesign|SharePointPnPPowerShellOnline|
Remove-PnPSiteScript|SharePointPnPPowerShellOnline|
Remove-PnPStorageEntity|SharePointPnPPowerShellOnline|[spo storageentity remove](../cmd/spo/storageentity/storageentity-remove.md)
Remove-PnPTaxonomyItem|SharePointPnPPowerShellOnline|
Remove-PnPTenantSite|SharePointPnPPowerShellOnline|
Remove-PnPTermGroup|SharePointPnPPowerShellOnline|
Remove-PnPUnifiedGroup|SharePointPnPPowerShellOnline|
Remove-PnPUser|SharePointPnPPowerShellOnline|
Remove-PnPUserFromGroup|SharePointPnPPowerShellOnline|
Remove-PnPView|SharePointPnPPowerShellOnline|
Remove-PnPWeb|SharePointPnPPowerShellOnline|
Remove-PnPWebhookSubscription|SharePointPnPPowerShellOnline|
Remove-PnPWebPart|SharePointPnPPowerShellOnline|
Remove-PnPWikiPage|SharePointPnPPowerShellOnline|
Remove-PnPWorkflowDefinition|SharePointPnPPowerShellOnline|
Remove-PnPWorkflowSubscription|SharePointPnPPowerShellOnline|
Rename-PnPFile|SharePointPnPPowerShellOnline|
Rename-PnPFolder|SharePointPnPPowerShellOnline|
Request-PnPReIndexList|SharePointPnPPowerShellOnline|
Request-PnPReIndexWeb|SharePointPnPPowerShellOnline|
Restore-PnPRecycleBinItem|SharePointPnPPowerShellOnline|
Restore-PnPTenantRecycleBinItem|SharePointPnPPowerShellOnline|
Resume-PnPWorkflowInstance|SharePointPnPPowerShellOnline|
Revoke-PnPSiteDesignRights|SharePointPnPPowerShellOnline|
Save-PnPProvisioningTemplate|SharePointPnPPowerShellOnline|
Send-PnPMail|SharePointPnPPowerShellOnline|
Set-PnPAppSideLoading|SharePointPnPPowerShellOnline|
Set-PnPAuditing|SharePointPnPPowerShellOnline|
Set-PnPAvailablePageLayouts|SharePointPnPPowerShellOnline|
Set-PnPClientSidePage|SharePointPnPPowerShellOnline|
Set-PnPClientSideText|SharePointPnPPowerShellOnline|
Set-PnPClientSideWebPart|SharePointPnPPowerShellOnline|
Set-PnPContext|SharePointPnPPowerShellOnline|
Set-PnPDefaultColumnValues|SharePointPnPPowerShellOnline|
Set-PnPDefaultContentTypeToList|SharePointPnPPowerShellOnline|
Set-PnPDefaultPageLayout|SharePointPnPPowerShellOnline|
Set-PnPDocumentSetField|SharePointPnPPowerShellOnline|
Set-PnPField|SharePointPnPPowerShellOnline|
Set-PnPFileCheckedIn|SharePointPnPPowerShellOnline|
Set-PnPFileCheckedOut|SharePointPnPPowerShellOnline|
Set-PnPGroup|SharePointPnPPowerShellOnline|
Set-PnPGroupPermissions|SharePointPnPPowerShellOnline|
Set-PnPHomePage|SharePointPnPPowerShellOnline|
Set-PnPIndexedProperties|SharePointPnPPowerShellOnline|
Set-PnPInPlaceRecordsManagement|SharePointPnPPowerShellOnline|
Set-PnPList|SharePointPnPPowerShellOnline|
Set-PnPListItem|SharePointPnPPowerShellOnline|
Set-PnPListItemAsRecord|SharePointPnPPowerShellOnline|
Set-PnPListItemPermission|SharePointPnPPowerShellOnline|
Set-PnPListPermission|SharePointPnPPowerShellOnline|
Set-PnPMasterPage|SharePointPnPPowerShellOnline|
Set-PnPMinimalDownloadStrategy|SharePointPnPPowerShellOnline|
Set-PnPPropertyBagValue|SharePointPnPPowerShellOnline|
Set-PnPProvisioningTemplateMetadata|SharePointPnPPowerShellOnline|
Set-PnPRequestAccessEmails|SharePointPnPPowerShellOnline|
Set-PnPSearchConfiguration|SharePointPnPPowerShellOnline|
Set-PnPSite|SharePointPnPPowerShellOnline|
Set-PnPSiteClosure|SharePointPnPPowerShellOnline|
Set-PnPSitePolicy|SharePointPnPPowerShellOnline|
Set-PnPStorageEntity|SharePointPnPPowerShellOnline|[spo storageentity set](../cmd/spo/storageentity/storageentity-set.md)
Set-PnPTaxonomyFieldValue|SharePointPnPPowerShellOnline|
Set-PnPTenantSite|SharePointPnPPowerShellOnline|
Set-PnPTheme|SharePointPnPPowerShellOnline|
Set-PnPTraceLog|SharePointPnPPowerShellOnline|
Set-PnPUnifiedGroup|SharePointPnPPowerShellOnline|
Set-PnPUserProfileProperty|SharePointPnPPowerShellOnline|
Set-PnPView|SharePointPnPPowerShellOnline|
Set-PnPWeb|SharePointPnPPowerShellOnline|
Set-PnPWebhookSubscription|SharePointPnPPowerShellOnline|
Set-PnPWebPartProperty|SharePointPnPPowerShellOnline|
Set-PnPWebPermission|SharePointPnPPowerShellOnline|
Set-PnPWikiPageContent|SharePointPnPPowerShellOnline|
Stop-PnPWorkflowInstance|SharePointPnPPowerShellOnline|
Submit-PnPSearchQuery|SharePointPnPPowerShellOnline|
Test-PnPListItemIsRecord|SharePointPnPPowerShellOnline|
Uninstall-PnPApp|SharePointPnPPowerShellOnline|[spo app uninstall](../cmd/spo/app/app-uninstall.md)
Uninstall-PnPAppInstance|SharePointPnPPowerShellOnline|
Uninstall-PnPSolution|SharePointPnPPowerShellOnline|
Unpublish-PnPApp|SharePointPnPPowerShellOnline|[spo app retract](../cmd/spo/app/app-retract.md)
Update-PnPApp|SharePointPnPPowerShellOnline|[spo app upgrade](../cmd/spo/app/app-upgrade.md)
Update-PnPSiteClassification|SharePointPnPPowerShellOnline|