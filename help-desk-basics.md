My notes on the Basics of IT Help Desk. These are the things that are most asked for a Tier 1 position.

# Ticketing Systems
Service: Spiceworks

### How to Create a New Ticket
1. Click on new ticket.
2. Click on calling and start typing to select them.
3. Select category based off of the issue.
4. Start writing a description of the problem asking questions.
5. Summeraize the problem in the short description prompt.
6. Select the Urgency based off of SLA and company priority standards.
7. Assign to appropriate group if necessary.
8. Document steps taken to complete troubleshooting.
9. If successful add solution in detail and close ticket.
10. If unsuccessful escalate to tier 2.

### How to Write Knowledge Base Documentation
1. Click on New Article.
2. Create a title being as specific with the issue as possible.
3. Write a short summary of when the specific issue can occur.
4. Add step by step information.
5. Add a conclusion of why this approach.
6. Add references for complicated topics if required.

# Virtualization
Service: Hyper-V

### Hyper-V Usage
1. Go to the task bar search field and type "turn windows features on or off".
2. Scroll down to Hyper-V checking it off and hit okay.
3. Reboot the computer.
4. Go to the task bar search field and type "Hyper-V Manager".
5. On the left hand side click on current computer name.
6. On the right under actions click "Quick Create"
7. On the left side select the operation to install.
8. Click on local installation course.
9. Change source if necessary and select the corresponding ISO file.
10. On the right hand side click more options and name the Virtual Machine.
11. Click create virtual machine.
12. In the centre where machine are listed right click on machine and select start.

# Remote Access
Service: Zoom | 
Note: All participants must be able to share their screen to use this feature.

### How to Remote in
1. Start or join your zoom meeting.
2. Ask the other person to share their screen.
3. On the top of the screen click view options and select request remote control.
4. Wait for them to accept.

# Active Directory
Note: Active directory can only be installed if the server has a static IP.

### Setup for Server 2019
1. Open Server manager.
2. On the top right click on manage and select "add roles and features".
3. Click next for installation type and make sure Role-based is selected.
4. Click next for destination server and make sure select a server from the server pool is on current server.
5. Click next for select server roles and check off "Active Directory Domain Services".
6. Click next and add features whem prompted.
7. Select DNS Server and click yes and add features when prompted.
8. Click next four times then install.
9. Click promote this server to domain controller.
10. In deployment configuration click "Add a new forest".
11. Add a root domain name and click next.
12. Set the Directory Services Restore Mode password and click next 5 times.
13. Click install and the server will reboot.

### How to add Users
1. On the right side click on the domain name a select new then user.
2. Add first name, last name and a user login name.
3. Click next and set password.
4. Check "user must change password at next logon" and click next.
5. Click next and finished.
6. Double click on name to bring up properties.
7. Click on "member of" and add.
8. Type in name of the group in "Enter the object names to select". 
9. Click check names and OK.

# Networking

### Basic Level
Usually not handled by Tier 1 but basic knowledge is needed.

| Question | Answer |
|-|-|
| What's a Network? | A collection of computers, servers and other devices connected to allow data sharing. |
| Switch vs Router? | Switches allow the sharing of resources by connecting together all the devices, including computers, printers, and servers, in a small network. Routers connect multiple switches, and their respective networks as well as allows networked devices and their users to access the Internet. |
| TCP / IP | Transmission Control Protocol / Internet Protocol. Application layer gets data from a program and sends it to the Transport Layer (TCP) via ports. The data put into small chunks called packets where they can take the fasted route along the internet to get where they are going. TCP puts a header onto each packet that contains instructions on what order to assemble the information. The packets are then pushed onto the Internet Layer which uses the Internet Protocol to attach the original and destination IP Addresses. This is sent to the Network Layer which handles MAC address so the information gets to the right machine.|
| DHCP | Dynamic Host Configuration Protocol. This assigns an IP, subnet mask, default gateway and DNS to a host on a network. Using a server and setting a Scope (the range of IP address the server is allowed to hand out) each client can ask for assignment when connected. The server needs to be on the same network segament to receive the request and repond within the scope. |
| Lan / Wan / Subnet | Local Area Network which is computers connected to eachother that can only talk to eachother. Wide Area Network which is when a router is added to allow for connection to a large network (internet). Subnetwork which is a divison of a larger network via a router which keeps them seperate. |
