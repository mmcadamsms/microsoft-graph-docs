---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestParameters := &msgraphsdk.UnifiedRoleManagementPolicyAssignmentRequestBuilderGetQueryParameters{
	Expand: "policy($expand=rules)",
}
options := &msgraphsdk.UnifiedRoleManagementPolicyAssignmentRequestBuilderGetOptions{
	Q: requestParameters,
}
unifiedRoleManagementPolicyAssignmentId := "unifiedRoleManagementPolicyAssignment-id"
result, err := graphClient.Policies().RoleManagementPolicyAssignmentsById(&unifiedRoleManagementPolicyAssignmentId).Get(options)


```