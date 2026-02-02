# Floating-Icons-FiveM
A floating icons script for QB/ESX/QBOX , the icons have a smooth animation and With these icons you can mark locations that provide utilities or services.

=
    Floating Icons Script by Abyte Studio
    README / GUIDE
=


Below you will find a simple step-by-step guide explaining
how to create and use your own custom icons.

⚠️ This is purely visual and does not include any functionality linked to the icons. ⚠️

-------------------------------------------------------------------
📌 WHATCH
-------------------------------------------------------------------

https://streamable.com/e/iytg9e


-------------------------------------------------------------------
📌 REQUIREMENTS
-------------------------------------------------------------------
• OpenIV
• Basic image editor (Photoshop, GIMP, Paint.NET, etc.)
• PNG images

-------------------------------------------------------------------
🎨 HOW TO CREATE CUSTOM ICONS (STEP BY STEP)
-------------------------------------------------------------------

1️⃣ Open OpenIV
   - Launch OpenIV
   - Enable "Edit Mode"

2️⃣ Create a new YTD file
   - Create a new file called:
     "icons.ytd"
   - Is very important to name it like that.

3️⃣ Prepare your icon images
   - Format: PNG
   - Size: 128x128 pixels (recommended)
   - Keep the design clean and simple

4️⃣ Import images into the YTD
   - Open your .ytd file in OpenIV
   - Import your PNG images inside the YTD
   - Each image name is VERY IMPORTANT

   Example:
   - casa.png
   - ropa.png
   - coche.png

   These names are the ones you will use in the config.lua

5️⃣ Add the YTD to the resource
   - Place your .ytd file inside:
     /stream/

-------------------------------------------------------------------
⚙️ HOW TO USE ICONS IN config.lua
-------------------------------------------------------------------

Once your icons are inside the .ytd, you can use them like this:

Example:
{
    coords = vector3(0.0, 0.0, 0.0),
    texture = "casa", -- image name inside the .ytd
    size = 0.15
}

IMPORTANT:
• The "texture" value MUST match the image name inside the .ytd
• File names are case-sensitive

-------------------------------------------------------------------
⚠️ IMPORTANT NOTES
-------------------------------------------------------------------
• Recommended icon size: 128x128
• Keep file names simple (no spaces, no special characters)
• If an icon does not show, check:
  - The image name
  - The .ytd is inside /stream/
  - The texture dictionary name is correct

-------------------------------------------------------------------
❤️ THANK YOU
-------------------------------------------------------------------


Enjoy and have fun! 🚀
===================================================================
