# unity-textFontReplacer

This is a Unity Editor script that can iterate through all the scenes in the Assets/Scenes/ folder and update the Font and Line Spacing of all Text components (including Text (Legacy) and TextMesh Pro) in each scene.
>**Note:** This editor script was generated with the assistance of ChatGPT.

## How to Use

1. **Import the Unity Package**  
   Download and import the provided `unitypackage` into your Unity project. The scripts would be imported to Assets/Editor/

2. **TextMesh Pro**  
   Even if you only use Text (Legacy) objects, for script compatibility, make sure to install TextMesh Pro. You can add a TextMesh Pro Text object in the scene to trigger the installation panel, and click to install the TextMesh Pro Essentials.

3. **Access the Sprite Splitter**  
   From Unity's main menu, navigate to `Tools > Global Text Editor`.

4. **Specify the Font and Line Spacing.**  
   In the popup window, you can specify the Font for Text, the Font for TextMesh Pro, and the Line Spacing. If a field is left blank, that item will not be updated. For example, you can choose to update only the Font for Text or only the Line Spacing.

5. **Apply and Update**  
   Click the `Apply` button to process the slicing.