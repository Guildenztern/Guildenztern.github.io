## Building a Raspberry Pi Penetration Testing Dropbox

This will be the blog post for my pentest dropbox that I used on a recent personal project. Do not need GUI for this to work, so long as the WiFi and configs are preset properly.

---

### Hardware, Software, and Accounts

This section will list the Hardware and Software that I used

#### Hardware

Hardware Lists

#### Software

Software Lists

#### Accounts

Accounts (AWS, Lightsail, EC2, etc)

---

### Prodecure

Procedure section for steps

#### Step 1

Step 1

#### Step 2

Step 2

#### etc etc etc

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

#### Bash Commands Tester

```bash
wget https://git.io/vpn -O openvpn-install.sh
chmod +x ./openvpn-install.sh
./openvpn-install.sh

scp -i cloud_server_key ubuntu@cloud_server_hostname:~/raspberry_box.ovpn ./
scp -i cloud_server_key ubuntu@cloud_server_hostname:~/attack_box.ovpn ./

openvpn raspberry_box.ovpn
openvpn attack_box.ovpn

cp ./raspberry_box.ovpn /etc/openvpn/openvpn.conf
systemctl enable openvpn
```

#### Text File Tester

```
This is a tester for a text file edit, with no code highlighting.
```


---

#### Some T-SQL Code

```tsql
SELECT This, [Is], A, Code, Block -- Using SSMS style syntax highlighting
    , REVERSE('abc')
FROM dbo.SomeTable s
    CROSS JOIN dbo.OtherTable o;
```

#### Some PowerShell Code

```powershell
Write-Host "This is a powershell Code block";

# There are many other languages you can use, but the style has to be loaded first

ForEach ($thing in $things) {
    Write-Output "It highlights it using the GitHub style"
}
```
