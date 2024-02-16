## Building a Raspberry Pi Penetration Testing Dropbox

This will be the blog post for my pentest dropbox that I used on a recent personal project. Do not need GUI for this to work, so long as the WiFi and configs are preset properly.

---

### Hardware, Software, and Accounts Used

This section will list the Hardware and Software that I used

#### Hardware

* Hardware Lists
* Hardware Lists
* Hardware Lists

#### Software

* Software Lists
* Software Lists
* Software Lists

#### Accounts

Accounts (AWS, Lightsail, EC2, etc)
* Lightsail
* EC2
* etc

---

### Prodecure

Procedure section for steps

#### **Phase 1**: Connecting the Raspberry Pi to WiFi automatically on startup

**Step 1:** Create the new ```wpa_supplicant.conf``` file

Log into Kali ... lorem ipsum dolor sit amet

#### Step 2

1. Step 2
2. 2
3. 3

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

#### Config File Edit Test

```bash
This is a tester for a config file from CLI.
```

#### Text File Tester

```txt
This is a tester for a text file edit, with no code highlighting.
```


---

Fin.
