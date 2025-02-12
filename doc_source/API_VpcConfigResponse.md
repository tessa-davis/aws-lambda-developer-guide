# VpcConfigResponse<a name="API_VpcConfigResponse"></a>

The VPC security groups and subnets that are attached to a Lambda function\.

## Contents<a name="API_VpcConfigResponse_Contents"></a>

 **SecurityGroupIds**   <a name="SSS-Type-VpcConfigResponse-SecurityGroupIds"></a>
A list of VPC security groups IDs\.  
Type: Array of strings  
Array Members: Maximum number of 5 items\.  
Required: No

 **SubnetIds**   <a name="SSS-Type-VpcConfigResponse-SubnetIds"></a>
A list of VPC subnet IDs\.  
Type: Array of strings  
Array Members: Maximum number of 16 items\.  
Required: No

 **VpcId**   <a name="SSS-Type-VpcConfigResponse-VpcId"></a>
The ID of the VPC\.  
Type: String  
Required: No

## See Also<a name="API_VpcConfigResponse_SeeAlso"></a>

For more information about using this API in one of the language\-specific AWS SDKs, see the following:
+  [ AWS SDK for C\+\+](https://docs.aws.amazon.com/goto/SdkForCpp/lambda-2015-03-31/VpcConfigResponse) 
+  [ AWS SDK for Go](https://docs.aws.amazon.com/goto/SdkForGoV1/lambda-2015-03-31/VpcConfigResponse) 
+  [ AWS SDK for Java V2](https://docs.aws.amazon.com/goto/SdkForJavaV2/lambda-2015-03-31/VpcConfigResponse) 
+  [ AWS SDK for Ruby V3](https://docs.aws.amazon.com/goto/SdkForRubyV3/lambda-2015-03-31/VpcConfigResponse) 