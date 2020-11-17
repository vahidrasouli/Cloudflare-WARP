# Cloudflare VPN WARP+ 1.1.1.1 for your Desktop (Windows, MacOSX, Ubuntu...)
![Screen-Shot-2020-02-03-at-15.46.48.png](https://www.upsieutoc.com/images/2020/02/03/Screen-Shot-2020-02-03-at-15.46.48.png)

This repository is to help you with installing CloudFlare VPN (1.1.1.1) on your Desktop(Windows, MacOSX, Ubuntu...)

### Detail instruction with Youtube video
[![How to use Cloudflare 1.1.1.1 WARP+ VPN on Desktop](http://img.youtube.com/vi/aOT5ZMsuNU0/0.jpg)](http://www.youtube.com/watch?v=aOT5ZMsuNU0 "How to use Cloudflare 1.1.1.1 WARP+ VPN on Desktop")

### Please follow steps below to get stuffs done

1. Install Wireguard on your OS. You can easily get it from here https://www.wireguard.com/install/
2. Go to https://labs.play-with-docker.com/ and login to the page (If you haven't got an account there, sign up a new one, it might take some minutes to complete) **IF YOUR OS SUPPORTS BASH CLI AND HAS DOCKER INSTALLED, YOU CAN SKIP THIS STEP**
3. Once you are in the session, add a new instance and execute the following command (you can copy and paste to command line)

`git clone https://github.com/cyberman219/cloudflare-vpn-for-desktop/; cd cloudflare-vpn-for-desktop; ./generator.sh`

4. Once the script finished generating the config files, access the link via port 80 *highlighted once finished* and download 2 files *wgcf-identity.json* and *wgcf-profile.conf* to your PC. 
5. Last step, import the *wgcf-profile.conf* config file to Wireguard and enjoy your VPN
![Screen-Shot-2020-02-03-at-15.49.37.png](https://www.upsieutoc.com/images/2020/02/03/Screen-Shot-2020-02-03-at-15.49.37.png)

## If you need further support, you can drop me a message via http://fb.com/gr219
