# senaev-keyboard-settings

## How to use Keyboard Layouts

- Clone repo
- Move keyboard layouts from `./layouts` to `/Library/Keyboard Layouts/`
  - `sudo rm -rf /Library/Keyboard\ Layouts/*`
  - `sudo cp -R ./layouts/. /Library/Keyboard\ Layouts`
- Log out and Log in MacOS
- Choose keyboard layouts in `System Settings` -> `Keyboard` -> `Input Sources`

## How to use Karabiner Elements

- Install and provide required permission https://karabiner-elements.pqrs.org/
- Go to `Complex Modifications` -> `Add your own rule` -> Paste JSON from karabiner-complex-modification.json

## How to edit Keyboard Layouts

- Download Ukelele https://software.sil.org/ukelele/
- Open the keyboard layout
- Edit and save
