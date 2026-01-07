## <ins> Evil Portal Flipper Zero Tutorial - Momentum Firmware </ins>
Educational captive portal experiment using HTML templates

**Disclaimer:**
Any information, discussion, or examples I provide are for educational and fictional purposes only and do not constitute advice or instruction. I do not encourage or endorse any real-world actions based on this material. How you choose to interpret or act on this information is entirely your own responsibility. I am not responsible for any actions taken, consequences incurred, or outcomes resulting from your independent use of this material.

Ensure qFlipper is installed so you can access files on your PC. 
https://docs.flipper.net/zero/qflipper

Attach esp32 board (some wont fully seat with case on)

Navigate to `Apps` -> `GPIO` -> `ESP` -> `[ESP32 Evil Portal]`

Click `Select HTML` section and choose the HTML template that best fits your needs. For this project, the `Google_Modern` template was selected for its clean and simple design. Select the best template for your case.

Click `Set AP name` Free_Wifi is default and I usually just leave it default

Click `Start portal`

On mobile or computer connect to "Free_Wifi" -> click sign into network -> sign in with fake email & password (on Flipper you should now see 'client connected' along with the username and password you typed.)

Once finished click `Stop portal` hit the back button and select `Save logs` to save them to your Flipper for later review. (View logs at SD Card/apps_data/evil_portal/logs (qFlipper))

I recommend experimenting with different HTML templates to find what works best for you. I suggest starting with a preconfigured HTML file; you can create or clone a custom template later if you choose.

**Legal notice:** I do not condone or support using this project against systems or individuals without explicit permission. Use is limited to environments you own or are authorized to test.

There are a ton of pre-set HTML files available through Momentum firmware. 

For more visit repo below:

Good source for HTML files for Evil Portal: https://github.com/bigbrodude6119/flipper-zero-evil-portal/tree/main/portals 

Using qFlipper, place your HTML files in the following directory on the SD card:
SD Card/apps_data/evil_portal
