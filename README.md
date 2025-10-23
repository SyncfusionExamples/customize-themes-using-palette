# How to customize themes using palette in WPF SkinManager?

Syncfusion's **WPF SkinManager** allows developers to apply and customize themes across Syncfusion and standard WPF controls. This sample demonstrates how to:
* Load a **DataGrid** and a **Chromeless Window**.
* Apply a **custom theme look** using **SkinManager**.
* Register and use **theme palette settings** for fine-grained control over colors and styles.

##  Key Components in the Sample
**1. SkinManager Theme Registration**
* The SfSkinManager is used to apply a visual style (e.g., MaterialDark, Office2019Colorful).
* You can register custom palette settings to override default theme colors.

**2. Chromeless Window**
* A window without the standard OS chrome (title bar, borders).
* Styled using the selected theme and palette to match the application's look.

**3. DataGrid Styling**
* The Syncfusion SfDataGrid is themed using the SkinManager.
* Custom palette colors are applied to headers, rows, and grid lines.

## Themes Supported
You can use and customize multiple themes using ThemeSettings. Please refer the following [link](https://help.syncfusion.com/wpf/themes/skin-manager#themes-list)
