# App Flow

### Screen 1A - First screen
First screen will be shown when:
 - app is freshly installed
 - user has choosen "add other server" in screen 1B
 
![01A First screen.png](Screenshots/01A%20First%20screen.png)

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

After successful authethentication, when there is only **one** VPN profile available, the client should directly connect and show this screen. The 'toggle' in this screen should trigger disconnect and go to screen 1B
![04 Connecting  - Secure internet.png](Screenshots/04%20Connecting%20%20-%20Secure%20internet.png)


![05 Connected  - Secure internet.png](Screenshots/05%20Connected%20%20-%20Secure%20internet.png)

![06A Select profile.png](Screenshots/06A%20Select%20profile.png)

![06B Connected  - Institute Access.png](Screenshots/06B%20Connected%20%20-%20Institute%20Access.png)

![07B Not connected  - expired.png](Screenshots/07B%20Not%20connected%20%20-%20expired.png)

![07 Not connected  - Secure internet.png](Screenshots/07%20Not%20connected%20%20-%20Secure%20internet.png)

![08 Connection info.png](Screenshots/08%20Connection%20info.png)

![09 Settings.png](Screenshots/09%20Settings.png)

![10 Connection Error.png](Screenshots/10%20Connection%20Error.png)

![11 Flags.png](Screenshots/11%20Flags.png)

 ### Screen 1C - First screen: Let's Connect! VPN 
This is the Let's Connect! VPN version of the app which doesn't have the discovery available.
First screen will be shown when:
 - app is freshly installed
 - user has choosen "add other server" just like screen 1B
 
![01C Let's Connect.png](Screenshots/01C%20Let's%20Connect.png)
