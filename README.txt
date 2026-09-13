CREIGHTON INTERACTIVE — RESPONSIVE HOMEPAGE

Upload these three files to the root of the creightoninteractive.github.io repository:

1. index.html
2. CreightonInteractiveLogo16_9.png
3. CreightonInteractivePortraitPhoneMode.png

Responsive behavior:
- Portrait phones/tablets/iPads use CreightonInteractivePortraitPhoneMode.png
- Landscape phones/tablets/Chromebooks/desktops use CreightonInteractiveLogo16_9.png
- The launch button becomes smaller/lower on short landscape phone screens so it does not cover the INTERACTIVE word
- Safe-area padding is included for iPhone-style bottom insets

Launch URL expected:
    /physics-skeeball/

Basic landing-page hardening retained:
- Content Security Policy
- no-referrer
- no third-party scripts/forms/objects
- insecure resource requests upgraded to HTTPS
