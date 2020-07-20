# WebView

##It is based on Javascript framework ,React.RFB is key implemention for this component.It has following responsibilties.
* It shall provide UI to the user for Tenant onbroarding,adding User, device Registration,sending authentication user links for device activation etc
* ANother Key part of this Application is to show the preview and remote view.Remote view is mirror of device display screen where user can interact with device.RFB protocol can be used for this purpose.It shall be designed such that once User lunches the remote view on the selected Device, It shall directly communicate with the Device using RFB.
* All auntication shall be done before lunching the RemoteView or Preview.
* RemoteView shall validate the auntication periodically to make sure session is aunticated throughout.
* RemoteView shall be well modularized to have more capability to interact with multiple devices.Since the way of inteaction is diffrent from device to device and mostly SIngle solution will not fit, we shall take care to well modularize and load the modules in remote view based on device type.
 

##userful study links
   - Please refer the belows links on RFB protocols  to consider the design/implements in java script.
   - [novnc](https://novnc.com/noVNC/docs/API.html)
   - [rfb2](https://www.npmjs.com/package/node-rfb)

+ Note: 
 * This shall be considered as independant Git repository for better collabation across the teams.
 * More ground work shall be done to design this React application.

