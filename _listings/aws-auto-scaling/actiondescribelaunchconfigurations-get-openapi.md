---
swagger: "2.0"
x-collection-name: AWS Auto Scaling
x-complete: 0
info:
  title: AWS Auto Scaling API Describe Launch Configurations
  version: 1.0.0
  description: Describes one or more launch configurations.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateLaunchConfiguration:
    get:
      summary: Create Launch Configuration
      description: Creates a launch configuration.
      operationId: createLaunchConfiguration
      x-api-path-slug: actioncreatelaunchconfiguration-get
      parameters:
      - in: query
        name: AssociatePublicIpAddress
        description: Used for groups that launch instances into a virtual private
          cloud (VPC)
        type: string
      - in: query
        name: BlockDeviceMappings.member.N
        description: One or more mappings that specify how block devices are exposed
          to the instance
        type: string
      - in: query
        name: ClassicLinkVPCId
        description: The ID of a ClassicLink-enabled VPC to link your EC2-Classic
          instances to
        type: string
      - in: query
        name: ClassicLinkVPCSecurityGroups.member.N
        description: The IDs of one or more security groups for the specified ClassicLink-enabled
          VPC
        type: string
      - in: query
        name: EbsOptimized
        description: Indicates whether the instance is optimized for Amazon EBS I/O
        type: string
      - in: query
        name: IamInstanceProfile
        description: The name or the Amazon Resource Name (ARN) of the instance profile
          associated with the IAM role for the instance
        type: string
      - in: query
        name: ImageId
        description: The ID of the Amazon Machine Image (AMI) to use to launch your
          EC2 instances
        type: string
      - in: query
        name: InstanceId
        description: The ID of the instance to use to create the launch configuration
        type: string
      - in: query
        name: InstanceMonitoring
        description: Enables detailed monitoring (true) or basic monitoring (false)
          for the Auto Scaling instances
        type: string
      - in: query
        name: InstanceType
        description: The instance type of the EC2 instance
        type: string
      - in: query
        name: KernelId
        description: The ID of the kernel associated with the AMI
        type: string
      - in: query
        name: KeyName
        description: The name of the key pair
        type: string
      - in: query
        name: LaunchConfigurationName
        description: The name of the launch configuration
        type: string
      - in: query
        name: PlacementTenancy
        description: The tenancy of the instance
        type: string
      - in: query
        name: RamdiskId
        description: The ID of the RAM disk associated with the AMI
        type: string
      - in: query
        name: SecurityGroups.member.N
        description: One or more security groups with which to associate the instances
        type: string
      - in: query
        name: SpotPrice
        description: The maximum hourly price to be paid for any Spot Instance launched
          to fulfill the request
        type: string
      - in: query
        name: UserData
        description: The user data to make available to the launched EC2 instances
        type: string
      responses:
        200:
          description: OK
      tags:
      - Launch
  /?Action=DeleteLaunchConfiguration:
    get:
      summary: Delete Launch Configuration
      description: Deletes the specified launch configuration.
      operationId: deleteLaunchConfiguration
      x-api-path-slug: actiondeletelaunchconfiguration-get
      parameters:
      - in: query
        name: LaunchConfigurationName
        description: The name of the launch configuration
        type: string
      responses:
        200:
          description: OK
      tags:
      - Launch
  /?Action=DeleteNotificationConfiguration:
    get:
      summary: Delete Notification Configuration
      description: Deletes the specified notification.
      operationId: deleteNotificationConfiguration
      x-api-path-slug: actiondeletenotificationconfiguration-get
      parameters:
      - in: query
        name: AutoScalingGroupName
        description: The name of the Auto Scaling group
        type: string
      - in: query
        name: TopicARN
        description: The Amazon Resource Name (ARN) of the Amazon Simple Notification
          Service (SNS) topic
        type: string
      responses:
        200:
          description: OK
      tags:
      - Notifications
  /?Action=DescribeLaunchConfigurations:
    get:
      summary: Describe Launch Configurations
      description: Describes one or more launch configurations.
      operationId: describeLaunchConfigurations
      x-api-path-slug: actiondescribelaunchconfigurations-get
      parameters:
      - in: query
        name: LaunchConfigurationNames.member.N
        description: The launch configuration names
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of items to return with this call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Launch
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---