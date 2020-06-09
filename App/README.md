# App Flow

### Screen 1A - First screen
First screen will be shown when:
 - app is freshly installed
 - user has choosen "add other server" in screen 1B
 
![01A First screen.png](Screenshots/01A%20First%20screen.png)

### Screen 1B - First screen when used App before 
This screen is shown when app starts and user has authorised in earlier phase. When clicking on "Add Other Server" the app should go to screen 1A. Via this screen the user should be able to add more VPN servers  to screen 1B.

When an user has already authenticated for a single secure internet server, he is able to connect to the  other countries as well! The "change location" button should view the other countries to which the VPN client could connect.
![01B Fist screen - When used before.png](Screenshots/01B%20First%20screen%20-%20When%20used%20before.png)

 ### Screen 3A - search results
 When an user in screen 1C types a few characters, he should get search results from the new discovery for both secure internet  and institute access usecases. The 'found' results are clickable and should trigger an authentication session in the webbrowser.
 
![03A Results.png](Screenshots/03A%20Results.png)

 ### Screen 3B - add a host-name
 As soon as an user is typing "two dots" in screen 3A, which indicates he wants to connect to a specific hostname, screen 3B should be shown.  The removal of the "two dots" should go back to screen 3A.
 
![03B Result with 2dots.png](Screenshots/03B%20Result%20with%202dots.png)

 ### Screen 3D - authorization
This screen will be shown when webbrowser opened and an user should authenticate in the browser. Usually when an user clicks on the organisation name in Screen 3A, hostname in screen 3B or when the OAuth token expired when clicking in screen 1B this notification will be shown.

![03D Authorization.png](Screenshots/03D%20Authorization.png)

 ### Screen 4 - Connecting

After successful authentication, when there is only **one** VPN profile available, the client should directly connect and show this screen. The 'toggle' in this screen should trigger disconnect and go to screen 1B
![04 Connecting  - Secure internet.png](Screenshots/04%20Connecting%20%20-%20Secure%20internet.png)

### Screen 5 - Connected
After screen 4, when there is a successful connect, this screen should be shown. When an user disconnects (move the slide button), the app should go to screen 1B and **NOT** screen 07.

![05 Connected  - Secure internet.png](Screenshots/05%20Connected%20%20-%20Secure%20internet.png)

### Screen 6A - Select profile
After screen 3D, when more than one VPN profile is available, this screen will be shown. And after clicking on a VPN server in screen 1B when there are more profiles available.

![06A Select profile.png](Screenshots/06A%20Select%20profile.png)

### Screen 6B - Select profile
In screen 6A the user should choose which VPN profile to connect to. After enabling a VPN profile this screen should be shown.

![06B Connected  - Institute Access.png](Screenshots/06B%20Connected%20%20-%20Institute%20Access.png)

### Screen 7B - Not connected
When OAuth and x509 certificate have been expired the client can't connect and this screen should be shown. This screen should **only** be shown when the client was before in screen  05. 
![07B Not connected  - expired.png](Screenshots/07B%20Not%20connected%20%20-%20expired.png)

### Screen 7 - Not connected
When the VPN connection somehow has dropped, being in screen 05, this screen can be shown. 
![07 Not connected  - Secure internet.png](Screenshots/07%20Not%20connected%20%20-%20Secure%20internet.png)

### Screen 8 - Connection info
Screen 5 and Screen 6B contain an option to view the connection info, so shis should be shown.
![08 Connection info.png](Screenshots/08%20Connection%20info.png)

### Screen 9 - Settings
Almost all screens contain the settings button right on top which would trigger this screen.
![09 Settings.png](Screenshots/09%20Settings.png)

### Screen 10 - Connection error
This screen could be triggered after screen 04
![10 Connection Error.png](Screenshots/10%20Connection%20Error.png)

### Screen 11 - Country flags
For the secure internet usecase, after successfully authenticated at **one** country server, the user is able to connect to the other countries as well. These flags can be used for the available countries in the secure internet discovery.
![11 Flags.png](Screenshots/11%20Flags.png)

 ### Screen 1C - First screen: Let's Connect! VPN 
This is the Let's Connect! VPN version of the app which doesn't have the discovery available.
First screen will be shown when:
 - app is freshly installed
 - user has choosen "add other server" just like screen 1B
 
![01C Let's Connect.png](Screenshots/01C%20Let's%20Connect.png)
