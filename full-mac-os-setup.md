# Full Mac Setup Process

Most of the things listed in here are based on a note that I have on my Obsidian Vault. Some of the things listed in here I haven't automated

## Initial steps on a new Mac

- Sign into iCloud and enable find my (This should be done as soon as the new Mac is turned on).
- Enable FileVault
- Install Ansible (more details in [README.md](./README.md)).
- Install [oh-my-zsh](https://ohmyz.sh/)
- Install the following Apps:
  - Bartender 5
  - OBS
  - Steam
  - [Go](https://go.dev/)
  - [Rust](https://www.rust-lang.org/)
  - [Little Snitch](https://obdev.at/products/littlesnitch/index.html)
- Manual settings to change
  - System Preferences:
    - Accessibility > Display > Reduce Motion
    - Keyboard > Input Sources > Add English and/or Latin American
    - Keyboard > Keyboard shortcuts > Mission Control > Move left (right option + left ) and Move Right (right option + right)
  - Dock:
    - Add Applications and Downloads
    - Turn Magnification on, hiding should be enabled from the ansible playbooks
  - Unvault the auth_config files and place them in their correspondent directories.
- Configure Tailscale
  - Set up my NAS shortcuts
  
## On the previous Mac

- Deauthorize Apple Music in Music App
- Follow the steps from the Apple [guide](https://support.apple.com/en-au/HT212749)

