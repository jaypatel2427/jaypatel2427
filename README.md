<div align="center">

<img src="assets/divider-glitch.svg" width="100%"/>

<br></br>
  
<img src="./assets/header-banner1.svg" alt="Jay Patel header banner" width="100%">

<br></br>

<img src="assets/header-banner.svg" alt="header banner" width="100%"/>

<br></br>

<img src="./assets/typing-bio2.svg" alt="typing bio">

<br></br>

<img src="assets/typing-bio.svg" alt="typing bio"/>

<br></br>

<background style="background-image:url('https://i.pinimg.com/originals/e2/8d/61/e28d61b0ce1b686bbd9c19b98912101f.gif');position:absolute;top:0;left:0;width:100%;height:1100%;z-index:-1;"></background>

</div>

<br/>

<div align="center">
 <background style="background-image:url('https://i.pinimg.com/originals/e2/8d/61/e28d61b0ce1b686bbd9c19b98912101f.gif');position:absolute;top:0;left:0;width:100%;height:1100%;z-index:-1;"></background>
  
  <img src="assets/profile-avatar.png" width="500" style="border-radius:12px;border:3.6px solid #39ff14;" alt="profile avatar"/>
</div>



<br></br>

<img src="assets/divider-glitch.svg" width="100%"/>


## `whoami`

```

> Name        : JAY BODA
> Role        : Cybersecurity Learner / Aspiring Pentester
> Focus       : Kali Linux, Networking, Web App Security, CTFs
> Currently   : Learning offensive security fundamentals
> Fun fact    : My terminal is my happy place 🐧

```

<img src="assets/divider-glitch.svg" width="100%"/>

## 🛠️ Tools & Arsenal

<div align="center">


![Kali Linux](https://img.shields.io/badge/Kali%20Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-0d1b2a?style=for-the-badge&logo=nmap&logoColor=39ff14)
![Burp Suite](https://img.shields.io/badge/Burp%20Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=for-the-badge&logo=metasploit&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

</div>

<div align="center">
  <background style="background-image:url('https://i.pinimg.com/originals/e2/8d/61/e28d61b0ce1b686bbd9c19b98912101f.gif');position:absolute;top:0;left:0;width:100%;height:1100%;z-index:-1;"></background>
  <img src="assets/kali-dragon.gif" hight="100%" width="260" style="border-radius:12px;border:3.6px solid #ff0000;" alt="kali dragon animation"/>
</div>

<img src="assets/divider-glitch.svg" width="100%"/>

## 📟 Everyday Kali Linux Reference

A quick cheat-sheet of commands I use often (system admin & recon basics — no exploit payloads, just the everyday toolkit):

```bash
# --- System ---
sudo apt update && sudo apt full-upgrade -y      # keep Kali up to date
neofetch                                          # flex your system info
history | tail -20                                # see recent commands

# --- Networking / Recon ---
ip a                                              # show network interfaces
nmap -sV -T4 192.168.1.0/24                       # service/version scan on local subnet
whois example.com                                 # domain registration lookup
dig example.com ANY                               # DNS record lookup
traceroute example.com                            # trace network path

# --- Packet Analysis ---
sudo tcpdump -i eth0 -n                           # live packet capture
wireshark                                         # GUI packet analysis

# --- Web ---
curl -I https://example.com                       # check response headers
gobuster dir -u https://example.com -w wordlist.txt  # directory brute force (own lab targets only)

# --- Password / Hash practice (on your own test files only) ---
hashid hash.txt                                   # identify hash type
john --wordlist=rockyou.txt hash.txt              # practice cracking in a lab

# --- Wireless (own hardware/lab only) ---
sudo airmon-ng start wlan0                        # enable monitor mode
sudo airodump-ng wlan0mon                         # capture nearby traffic info
```

> ⚠️ These are reference commands for **learning on your own systems / authorized labs (TryHackMe, HackTheBox, local VMs)** — always get explicit permission before scanning or testing anything you don't own.

<img src="assets/divider-glitch.svg" width="100%"/>

<div align="center">
<img src="https://i.redd.it/9u1hoy1blufh1.gif" width="360" alt="binary skull"/>
</div>

<img src="assets/divider-glitch.svg" width="100%"/>

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=chartreuse-dark&hide_border=true&bg_color=0d1117" width="48%"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=YOUR_USERNAME&theme=github-dark-blue&hide_border=true&background=0d1117&ring=39ff14&fire=ff2b6d" width="48%"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=chartreuse-dark&hide_border=true&bg_color=0d1117" width="48%"/>

</div>

<img src="https://i.gifer.com/embedded/download/VQcm.gif" width="100%" alt="matrix rain"/>

## 🐍 The Snake That Eats My Contributions

This repo's Action (`.github/workflows/snake.yml`) auto-generates an animated snake that "eats" your contribution graph once a day. After you push and it runs once, it appears below:

<div align="center">
<img src="https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_USERNAME/output/github-contribution-grid-snake-dark.svg" alt="snake game" width="100%"/>
</div>

<img src="assets/divider-glitch.svg" width="100%"/>

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=YOUR_USERNAME&color=39ff14&style=flat-square&label=Profile+Views)

**"There is no patch for human stupidity — but there's always a script for the rest."**

</div>
