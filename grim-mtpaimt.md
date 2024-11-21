### Sway Screen Shot

## Instal first:
- `sudo pacman -S grim mtpaint`

## Add to sway config:
- `bindsym Print exec bash -c 'file="/home/domino/$(date +%Y%m%d_%Hh%Mm%Ss)_grim.png" && grim $file && mtpaint $file'`
  
