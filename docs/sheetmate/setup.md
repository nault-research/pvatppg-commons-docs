
# Setup SheetMATE

!!! warning "SheetMATE is in development"
    SheetMATE is a product in active development. It currently request more permissions than it needs for read/write of google drive and will require approval of permissions. A non-MSU account must be used as MSU will not allow the correct permissions to be provided. We are actively working on limiting the permissions and relocating the code on the server instead of the user account.

---

## <b>Installing SheetMATE development version</b>

1. Request the sheetMATE link from the [PVAT PPG Data Commons team](mailto: naultran@msu.edu).
2. Click on <u>_Extensions_</u> and select <u>_App Script_</u>
   <p align="left">
     <img src="../../assets/images/app_script_screenshot.png" width="400"
     style="border: 3px solid #ccc; border-radius: 6px;">
   </p>
    This will open a new tab which will display several scripts and code. 

3. Choose the script named <u>*code.gs*</u> and then select <u>*Run*</u> from the top menu
   <p align="left">
     <img src="../../assets/images/run_app_script_screenshot.png" width="1200" 
     style="border: 3px solid #ccc; border-radius: 6px;">
   </p>

    Here Google will request Authorization and review of permissions. It will indicate that Google has not verified this app. You will need to select <u>*Advanced*</u> then <u>*Go to gen3 (unsafe)*</u> to proceed. You will also need to check the box and approve all requested permissions.

4. Return to the Google Sheets tab. You will now have a new menu option called <u>*Gen3DataCommons*</u>. 
   <p align="left">
     <img src="../../assets/images/gen3_menu_screenshot.png" width="1200" 
     style="border: 3px solid #ccc; border-radius: 6px;">
   </p>


---

## <b>Setup sheetMATE profile</b>

1. Go to [PVAT PPG Commons](dev.pvatppgmsu.com) and sign-in.
<i>Note: PPG members should all have access to the commons via their MSU netid. Contact us if you do not have access</i>

2. Select <b>Profile</b> then <create API key>. 
   <p align="left">
     <img src="../../assets/images/apikey_screenshot.png" width="1200" 
     style="border: 3px solid #ccc; border-radius: 6px;">
   </p>

3. <b>Download json</b> API key to somewhere you will be able to find it 
  <span id="download-json"></span>
  <p align="left">
    <img src="../../assets/images/apijson_screenshot.png" width="1200" 
    style="border: 3px solid #ccc; border-radius: 6px;">
  </p>


4. <b> You are ready to [start uploading (meta)data using sheetMATE!](../getting-started/walkthrough.md)</b>