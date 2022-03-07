# <Your-Project-Title>
## <img src="images/description.jpg" alt="Logo" width="1698">
 
<div align="justify">
  
The security and privacy tests that are interesting to study in home IoT devices are detailed below:
<br /> 
<br />
<ul>
 <li><strong>Authentication</strong>: the application associated with the smart home IoT device implements a method to authenticate the user's identity.</li>
 <li><strong>Insecure pairing method</strong>: the link between the smart home IoT device and the mobile app uses a pairing method considered insecure or ineffective against MITM or passive eavesdropping attacks and lacks privacy safeguards.</li>
 <li><strong>Unencrypted Communications</strong>: the Wi-Fi communication between the smart home IoT device and mobile app is not encrypted. </li>
 <li><strong>Static MAC address</strong>: the smart home IoT device uses a static MAC address (i.e., it does not change when the device is turned off or restarted), exposing it to tracking and user identification attacks.</li>
 <li><strong>Transmission of sensitive information to third-party servers</strong>: the managing smart home IoT device application sends sensitive user information to third-party servers.</li>
 <li><strong>Sending of information and firmware updates via HTTP</strong>: The mobile app receives firmware updates and sends requests with sensitive information using HTTP without TLS.</li>
</ul>

 <p align="right">(<a href="https://soniasoleracotanilla.github.io/Tests/">Back Testing</a>)</p>

</div>

## <img src="images/testwithus.jpg" alt="Logo" width="1698">
 
<div align="justify">
 
The security and privacy tests performed to the home IoT devices have been carried out within the virtual environment described below.

<div align="center">
  <img src="images/virtualization.jpg" alt="Logo" width="798">  
</div>

For its part, the operation process performed during the analysis of smart home IoT devices is the following:
<br />
<br />
<ul>
 <li>Installing the recommended mobile application for managing the device.</li>
 <li>Plugging the device.</li>
 <li>Switching on the device, if necessary, and the mobile application.</li>
 <li>HTTP data collection activities:</li>
 <ul>
  <li>Pairing of smart home IoT device and the smartphone.</li>
  <li>Turning on and use the device.</li>
  <li>Device shutdown.</li>
 </ul>
 <li>Disconnection.</li>
</ul>
 
<p align="right">(<a href="https://soniasoleracotanilla.github.io/Tests/">Back Testing</a>)</p>


</div>

## <img src="images/results.jpg" alt="Logo" width="1698">

<div align="justify">
 
The results of security and privacy tests show that those low-cost devices have certain shortcomings in terms of encryption of pairing information. Specifically, these devices send the SSID and WPA password without any encryption during the initial pairing and confirmation process. This unprotected information exchange can lead to a takeover situation of the home Wi-Fi network.
<br />
<br />
On the other hand, high-end commercial devices use robust and secure pairing methods such as ZeroConf, which ensures a secure communication from the initial moment of use of this type of device.
<br />
<br />
<p align="right">(<a href="https://soniasoleracotanilla.github.io/Tests/">Back Testing</a>)</p>

</div>
