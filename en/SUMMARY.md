# Summary

* [Features Overview](/README.md)
* [Preparation for Integration](./resource/Preparation.md)
* [Integrate SDK](./resource/Integrated.md)
* [Demo App](./resource/Demo.md)
* [iOS Adaptation](./resource/iOSAdaptation.md)
* [User Management](./resource/User.md#user-management)
  - [Use Mobile Phone for Login](./resource/User.md#use-mobile-phone-for-login)
  - [Use Email for Login](./resource/User.md#use-email-for-login)
  - [Use UID for Login](./resource/User.md#use-uid-for-login)
  - [Third Party Login](./resource/User.md#third-party-login)
  - [Login by Auth2](./resource/User.md#login-by-auth2)
  - [Anonymous registration](./resource/User.md#anonymous-registration)
  - [Modify User Info](./resource/User.md#modify-user-info)
  - [Logout, Disable Account](./resource/User.md#logout-disable-account)
  - [User Data Model](./resource/User.md#user-data-model)
  - [Handling of Expired Session](./resource/User.md#handling-of-expired-session)
* [Home Management](./resource/HomeAbout.md)
  - [Home Relationship Management](./resource/Home.md#home-relationship-management)
  - [Operation of Home](./resource/Home.md#home-information-management)
  - [Home Member Management](./resource/Home.md#member-management)
  - [Room Management](./resource/Home.md#room-information-management)
  - [Home's Weather](./resource/Home.md#home-weather)
* [Device Configuration](./resource/Activator.md#device-configuration)
  - [Functional Overview](./resource/Activator.md#functional-overview)
  - [Instructions](./resource/Activator.md#instructions)
  - [Implementation](./resource/Activator.md#Implementation)
    - [Quick Connection Mode](./resource/Activator.md#quick-connection-mode)
    - [HotSpot Mode](./resource/Activator.md#hotspot-mode)
    - [Camera Scan Code Network Configuration](./resource/Activator.md#camera-scan-code-network-configuration)
    - [Wired Network Configuration](./resource/Activator.md#wired-network-configuration)
    - [Sub-Device Configuration](./resource/Activator.md#sub-device-configuration)
    - [Bluetooth Configuration](./resource/Activator.md#bluetooth-configuration)
* [Device Management](./resource/Device.md#device-management)
  - [Initialize Device](./resource/Device.md#initialize-device)
  - [Delegate of Device](./resource/Device.md#delegate-of-device)
  - [Device Control](./resource/Device.md#device-control)
  - [Functions of Device](./resource/Device.md#functions-of-device)
  - [Querying Device Information](./resource/Device.md#querying-device-information)
  - [Modify the Device Name](./resource/Device.md#modify-the-device-name)
  - [Remove Device](./resource/Device.md#remove-device)
  - [Restore Factory Settings](./resource/Device.md#restore-factory-settings)
  - [Obtain Wi-Fi Signal Strength](./resource/Device.md#obtain-wi-fi-signal-strength)
  - [Obtain the Sub-Device List of a Gateway](./resource/Device.md#obtain-the-sub-device-list-of-a-gateway)
  - [Firmware Upgrade](./resource/Device.md#firmware-upgrade)
  - [Fetch the Log of DP Report](./resource/Device.md#fetch-the-log-of-dp-report)
* [Device Multi-Control](./resource/MultiControl.md#device-multi-control)
    - [Overview](./resource/MultiControl.md#overview)
    - [Bussiness Flowchart](./resource/MultiControl.md#bussiness-flowchart)
    - [Get Device Dp Information](./resource/MultiControl.md#get-device-dp-information)
    - [Query Related Information of a Dp](./resource/MultiControl.md#query-related-information-of-a-dp)
    - [Add Multi-control Group](./resource/MultiControl.md#add-multi-control-group)
    - [Update Multi-control Group](./resource/MultiControl.md#update-multi-control-group)
    - [Enable or Disable Multi-control Group](./resource/MultiControl.md#enable-or-disable-multi-control-group)
    - [Query Devices that Support Multi-control](./resource/MultiControl.md#query-devices-that-support-multi-control)
    - [Get Affiliate Device Details](./resource/MultiControl.md#get-affiliate-device-details)
* [Share Devices](./resource/Share.md#shared-devices)
  - [Add Device Share](./resource/Share.md#add-device-share)
  - [Getting Shared Relationships](./resource/Share.md#getting-shared-relationships)
  - [Remove Sharing](./resource/Share.md#remove-sharing)
  - [Modify Note Name](./resource/Share.md#modify-note-name)
* [Timer Task](./resource/Timer.md)
* [Group Management](./resource/Group.md#group-management)
  * [Functional Overview](./resource/Group.md#functional-overview)
  * [Create Group](./resource/Group.md#create-group)
    * [Create Wi-Fi Group](./resource/Group.md#create-wi-fi-group)
    * [Create ZigBee Group](./resource/Group.md#create-zigbee-group)
  * [Group Operation](./resource/Group.md#group-operation)
    * [Instantiation](./resource/Group.md#instantiation)
    * [Modifying group name](./resource/Group.md#modifying-group-name)
    * [Dismiss Group](./resource/Group.md#dismiss-group)
    * [Sending group control command](./resource/Group.md#sending-group-control-command)
    * [Group callback event](./resource/Group.md#group-callback-event)
    * [Group data acquisition](./resource/Group.md#group-data-acquisition)
* [Smart Scene](./resource/SmartScene.md#smart-scene)
  - [Scene Condition](./resource/SmartScene.md#scene-condition)
  - [Scene Action](./resource/SmartScene.md#scene-action)
  - [Smart Scene Management](./resource/SmartScene.md#smart-scene-management)
  - [Scene Operation](./resource/SmartScene.md#scene-operation)
* [Message Center](./resource/Message.md#message-center)
  * [Message](./resource/Message.md#message)
  * [Push Notification](./resource/Message.md#push-notification)
* [Feedback](./resource/Feedback.md#feedback)
  - [Obtain Feedback Talk List](./resource/Feedback.md#obtain-feedback-talk-list)
  - [Obtain Feedback List](./resource/Feedback.md#obtain-feedback-list)
  - [Obtain Feedback Type List](./resource/Feedback.md#obtain-feedback-type-list)
  - [Add Feedback](./resource/Feedback.md#add-feedback)
* [Integrate Push](./resource/Push.md)


* [TUYA BLE](./resource/BLE.md)
  * [Bluetooth Low Energy](./resource/BLE.md#bluetooth-low-energy)
  	- [Preparatory Work](./resource/BLE.md#preparatory-work)
  	- [Scanning Device](./resource/BLE.md#scanning-device)
  	- [BLE Device Activation](./resource/BLE.md#ble-device-activation)
  	- [Dual-mode Device Activation](./resource/BLE.md#dual-mode-device-activation)
  	- [BLE Device Function](./resource/BLE.md#ble-device-function)
  	- [BLE OTA](./resource/BLE.md#ble-ota)
  	- [Error Code](./resource/BLE.md#error-code)
  * [Bluetooth Mesh(SIG)](./resource/SIGMesh.md#bluetooth-meshsig)
       - [Prepare](./resource/SIGMesh.md#prepare)
       - [Basic Notion](./resource/SIGMesh.md#basic-notion)
       - [Management](./resource/SIGMesh.md#management)
       - [Activation](./resource/SIGMesh.md#activation)
       - [Device](./resource/SIGMesh.md#device)
       - [Group](./resource/SIGMesh.md#group)
       - [Control](./resource/SIGMesh.md#control)
       - [Firmware Upgrade](./resource/SIGMesh.md#firmware-upgrade)
  * [Bluetooth Mesh(TUYA)](./resource/Mesh.md#bluetooth-meshtuya)
    - [Prepare](./resource/Mesh.md#prepare)
    - [Basic Notion](./resource/Mesh.md#basic-notion)
    - [Management](./resource/Mesh.md#management)
    - [Activation](./resource/Mesh.md#activation)
    - [Device](./resource/Mesh.md#device)
    - [Group](./resource/Mesh.md#group)
    - [Control](./resource/Mesh.md#control)
    - [Firmware Upgrade](./resource/Mesh.md#firmware-upgrade)



* [Extension SDK](./resource/ExtensionAbout.md)
  * [IPC SDK](./resource/Camera.md)
    * [Integrate SDK](./resource/ipc/rapid_integration.md)
    * [SDK Architecture](./resource/ipc/architecture.md)
    * [Camera Device](./resource/ipc/camera_device.md)
    * [Device Configuration](./resource/ipc/activitor.md)
    * [Camera Features](./resource/ipc/live.md)
      * [Live Video](./resource/ipc/live.md#live-video)
      * [Playback](./resource/ipc/playback.md)
      * [AV Functions](./resource/ipc/av_function.md)
    * [Cloud Storage](./resource/ipc/cloud_video.md)
      * [Flow Chart](./resource/ipc/cloud_video.md#flow-chart)
      * [Cloud Service](./resource/ipc/cloud_video.md#cloud-service)
      * [Cloud Video](./resource/ipc/cloud_video.md#cloud-video)
    * [Extension Features](./resource/ipc/device_points.md)
      * [Data Point Id](./resource/ipc/device_points.md#data-point-id)
      * [Doorbell](./resource/ipc/lowpower.md)
      * [Memory Card](./resource/ipc/sd_card.md)
      * [PTZ](./resource/ipc/ptz.md)
    * [Detection Alarm](./resource/ipc/detect.md)
      * [Message List](./resource/ipc/detect.md#message-list)
      * [Video Message](./resource/ipc/detect.md#video-message)
    * [Encrypted Image](./resource/ipc/encryptImage.md)
    * [Error Codes](./resource/ipc/errors.md)
    * [Permissions](./resource/ipc/required_permission.md)
    * [Debug logs](./resource/ipc/log_file.md)
    * [FAQ](./resource/ipc/FAQ.md)
    * [Change Log](./resource/ipc/version_record.md)
  * [Sweeper SDK](./resource/Sweeper.md#Sweeper-sdk)
    - [Gyroscope and Visual Sweeper](./resource/SweeperInterface.md)
    - [Laser Sweeper](./resource/SweeperLaser.md)
    - [Voice Package Download](./resource/SweeperVoiceDownload.md)
    - [Glossary](./resource/SweeperWordIntroduction.md)
    - [Change Log](./resource/SweeperChangeLog.md)
  * [Smart Lock SDK](./resource/Lock.md)
    - [Wi-Fi Lock](./resource/WiFiLock.md)
    - [BLE Lock](./resource/BLELock.md)



* [API Reference](https://tuyainc.github.io/tuyasmart_home_ios_sdk_api_reference/index.html)
* [Common Interface](./resource/CommonInterface.md)
* [Error Code](./resource/ErrorCode.md)
* [FAQ](./resource/Faq.md)
* [ChangeLog](./resource/ChangeLog.md)
