AWS Unit 4 — Windows Server EC2 Security Lab

Aim

To launch a Windows Server EC2 instance on AWS, configure secure remote access, and verify basic Windows security settings.

Objectives

- Launch a Windows Server instance using Amazon EC2.
- Configure Remote Desktop Protocol (RDP) access.
- Verify Windows system information.
- Create and verify a local Windows user account.
- Check Windows Defender Firewall status.
- Troubleshoot RDP connectivity.

Tools and Technologies

- Amazon Web Services (AWS)
- Amazon EC2
- Windows Server
- Remote Desktop Protocol (RDP)
- AWS Security Groups
- Windows Defender Firewall
- PowerShell

Procedure

Step 1: Launch the EC2 Instance

Launched a Windows Server EC2 instance from the AWS Management Console and checked its instance status.

Step 2: Configure the Security Group

Configured an inbound RDP rule using TCP port 3389. Remote access should be restricted to a trusted IP address rather than opened to all IP addresses.

Step 3: Connect Through RDP

Attempted to connect to the Windows Server instance using Remote Desktop Connection. Record whether the connection succeeded and include a screenshot if available.

Step 4: Verify System Information

Opened the Windows System Information utility using `msinfo32` to inspect operating system and system details.

Step 5: Create a Local User

Used Computer Management to create a local user account named `LabUser`.

Step 6: Verify Windows Firewall

Used PowerShell to check whether the Domain, Private, and Public Windows Defender Firewall profiles were enabled.

Step 7: Troubleshoot Connectivity

Tested whether TCP port 3389 was reachable from the local computer. The reported test result was unsuccessful, so further troubleshooting may be required.

Security Measures

- Restrict RDP access to trusted IP addresses.
- Keep AWS credentials and private keys confidential.
- Use secure passwords for Windows accounts.
- Keep Windows Firewall enabled.
- Avoid exposing remote access ports to the entire internet.

Results

The lab covered Windows EC2 deployment, RDP security group configuration, system information inspection, local user creation, firewall verification, and connectivity troubleshooting.

The RDP connectivity issue remained unresolved at the time of testing. Update this section if the connection is restored and further verification is completed.


Conclusion

This lab provided practical experience with Windows Server on AWS and demonstrated the importance of securing remote access, checking firewall settings, and troubleshooting network connectivity.
