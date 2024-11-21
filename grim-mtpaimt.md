### Sway Screen Shot

## Instal first:
- `sudo pacman -S grim mtpaint`

## Add to sway config:
- ` # Start a Screen Shot
    bindsym Print exec bash -c 'file="/home/domino/$(date +%Y%m%d_%Hh%Mm%Ss)_grim.png" && grim $file && mtpaint $file' `
  
