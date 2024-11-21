### Sway Screen Shot

## Instal first:
- `sudo pacman -S grim slurp mtpaint`

## Add to sway config hotkey command for Print Screen:
- `bindsym Print exec bash -c 'file="/home/domino/$(date +%Y%m%d_%Hh%Mm%Ss)_grim.png" && grim -g "$(slurp)" $file && mtpaint $file'`

  
