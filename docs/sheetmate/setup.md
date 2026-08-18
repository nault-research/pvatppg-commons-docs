
# Setup SheetMATE

!!! warning "SheetMATE is in development"
    SheetMATE is a product in active development. It currently request more permissions than it needs for read/write of google drive and will require approval of permissions. A non-MSU account must be used as MSU will not allow the correct permissions to be provided. We are actively working on limiting the permissions and relocating the code on the server instead of the user account.

---

## <b>Getting the link to SheetMATE</b>

1. Request the SheetMATE link from the [PVAT PPG Data Commons team](mailto: naultran@msu.edu).

2. Click on the link to SheetMATE. <u>Make sure you are signed in with a non-MSU email.</u> 

3. Click the <b>Gen3DataCommons</b> menu option on the right. 
   <p align="left">
     <img src="../../assets/images/gen3_menu_screenshot.png" width="1200" 
     style="border: 3px solid #ccc; border-radius: 6px;">
   </p>

4. An "Authorization required" pop-up message will appear. Click **OK**.

5. Next, another pop-up will appear saying "Google hasn't verified this app". Click the small **Advanced** option on the bottom left, then **Go to SheetMATE (unsafe)**.
   <p align="left">
     <img src="../../assets/images/authorization_required_pop_up.png" width="1200" 
     style="border: 3px solid #ccc; border-radius: 6px;">
   </p>

6. The last pop-up message will ask for permssions. All permission must be selected for SheetMATE to work at this time. Then click **Continue**.
   <p align="left">
     <img src="../../assets/images/google_permissions.png" width="1200" 
     style="border: 3px solid #ccc; border-radius: 6px;">
   </p>

---

## <b>Obtain SheetMATE authentication credential file</b>

1. Go to [PVAT PPG Commons](https://dev.pvatppgmsu.com) and sign-in with your MSU email.
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


4. <b> You are ready to [start uploading (meta)data using sheetMATE!](../getting-started/metadata_walkthrough.md)</b>