---
title: Halcyon: Recreating the Demo - Template Settings
description: Your Guide to Recreating Elements of the Halcyon Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/halcyon:Halcyon

---

Template Settings
-----
One of the most important aspects of any Gantry template is its ability to be easily customized using the settings present in the Template Settings page. These settings can be adjusted by navigating to **Administration -> Template Manager -> Halcyon Template**. To replicate the demo, the main changes being made will happen within the Style, Features, Layouts, and Advanced tabs. 

![][halcyon2]

:   1. **FP Top B**  [6%, 72%, se]
    2. **FP RokGallery**  [12%, 19%, se]
    3. **FP RokGallery Feature**  [27%, 36%, se]
    4. **Contact Details**  [78%, 19%, se]
    5. **Network with Us**  [78%, 51%, se]
    6. **Member Access**  [78%, 67%, se]

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a template preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Template Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the Style indicated here relates to the template Style in this menu. More information about how Styles work can be found in our [Gantry documentation][Style].

>> Note: In the interest of simplicity, the override settings listed below are presented as they appear on our demo site which is built on the fixed version of the template.

### Style
| Style   | Option          | Position | Setting                                  |  
| :------ | :-------------- | :------- | :--------------------------------------- |  
| Default | Load Transition |          | On                                       |   
| Default | Font Settings   |          | Font Family: Helvetica Neue, Font Size: Default |  

### Features
| Style   | Option           | Position     | Setting                                                                                 |  
| :------ | :--------------- | :----------- | :-------------------------------------------------------------------------------------- |  
| Default | Logo             | header-a     | Show: On                                                                                |  
| Default | Date             | utility-a    | Show: Off                                                                               |  
| Default | Font-Sizer       | utility-b    | Show: Off                                                                               |  
| Default | Login Panel      | utility-c    | Show: Off, Login Button Text: `Member Login`, Logout Button Text: `Logout`              |  
| Default | Popup Panel      | utility-d    | Show: Off, Popup Button Text: `Popup Module`                                            |  
| Default | Branding         | copyright-c  | Show: On                                                                                |  
| Default | Copyright        | copyright-a  | Show: On, Text: `Designed by RocketTheme`                                               |  
| Default | SmartLoad        |              | Show: On, Component Ignores: `com_community,com_contact,com_k2,com_tienda,com_weblinks` |  
| Default | More Articles    |              | Enable: Off, Text: Load More Articles, Hide Pagination: On                              |  
| Default | To-Top Scroller  | copyright-b  | Show: On, Text: `Back to Top`                                                           |  
| Default | System Messages  | drawer       | Show: On                                                                                |  
| Default | Reset Settings   | footer-b     | Show: Off, Text: `Reset Settings`                                                       |  
| Default | Google Analytics |              | Enable: Off                                                                             |   

### Menu

| Style   | Option                  | Setting                                    |  
| :------ | :---------------------- | :----------------------------------------- |  
| Default | Menu Control            | Show: On, Type: Fusion-Menu                |  
| Default | Select a Menu           | Main Menu                                  |  
| Default | Module Cache            | On                                         |  
| Default | Main Menu Position      | navigation                                 |  
| Default | Sub Menu Position       | subnavigation                              |  
| Default | Side Menu Position      | sidebar-a                                  |  
| Default | Side Menu Module Suffix |                                            |  
| Default | First Level Pill        | On, Duration: 200, Animation: Sine.easeOut |  
| Default | Arrow Indicator         | Duration: 200, Animation: Sine.easeOut     |  
| Default | Sub Menu Panel          | Duration: 200, Animation: Sine.easeOut     |  

### Layouts
| Style   | Option               | Setting               |  
| :------ | :------------------- | :-------------------- |  
| Default | Top Positions        | Positions: 2, 6:6     |  
| Default | Header Positions     | Positions: 2, 6:6     |  
| Default | Showcase Positions   | Positions: 1, 12      |  
| Default | Feature Positions    | Positions: 4, 3:3:3:3 |  
| Default | Utility Positions    | Positions: 4, 3:3:3:3 |  
| Default | MainTop Positions    | Positions: 4, 3:3:3:3 |  
| Default | MainBody Positions   | Positions: 2, 8:4     |  
| Default | MainBottom Positions | Positions: 3, 4:4:4   |  
| Default | Extension Positions  | Positions: 3, 4:4:4   |  
| Default | Bottom Positions     | Positions: 2, 6:6     |  
| Default | Footer Positions     | Positions: 4, 3:3:3:3 |  
| Default | Copyright Positions  | Positions: 3, 4:4:4   |  
| Home    | Mainbody Positions   | Positions: 2, 3:9     |  
| Home    | Extension Positions  | Positions: 3, 5:3:4   |  
| Home    | Bottom Positions     | Positions: 2, 8:4     |  

### Mobile
| Style   | Option               | Position          | Setting                                      |  
| :------ | :------------------- | :---------------- | :------------------------------------------- |  
| Default | iPhone Custom Theme  |                   | On                                           |  
| Default | Android Custom Theme |                   | On                                           |  
| Default | Scalable Content     |                   | Off                                          |  
| Default | Standard View Switch | mobile-copyright  | Enable: On                                   |  
| Default | Mobile Menu          |                   | Menu: Main Menu, Menu Animation: Cube        |  
| Default | Image Resize         |                   | Enabled: On, Min-Width: 80, % of Resize: 25% |  
| Default | Positions Aliases    | mobile-drawer     | drawer                                       |  
| Default | Positions Aliases    | mobile-top        | header-a                                     |  
| Default | Positions Aliases    | mobile-header     | header-c                                     |  
| Default | Positions Aliases    | mobile-navigation | mobile-navigation                            |  
| Default | Positions Aliases    | mobile-showcase   | mobile-showcase                              |  
| Default | Positions Aliases    | mobile-feature    | content-top-a                                |  
| Default | Positions Aliases    | mobile-utility    | mobile-utility                               |  
| Default | Positions Aliases    | mobile-extension  | extension-a                                  |  
| Default | Positions Aliases    | mobile-bottom     | bottom-b                                     |  
| Default | Positions Aliases    | mobile-footer     | footer-a                                     |  
| Default | Positions Aliases    | mobile-copyright  | copyright-a                                  |   

### Advanced
| Style   | Option            | Setting                                                                               |  
| :------ | :---------------- | :------------------------------------------------------------------------------------ |  
| Default | Gantry Cache      | Enabled: On, Cache Timeout: 900                                                       |  
| Default | Input Styling     | Enabled: On, Exclusions: `'.content_vote','#rt-popup','#rt-popuplogin','#vmMainPage'` |  
| Default | Inline JS File    | Off                                                                                   |  
| Default | Display Component | On                                                                                    |  
| Default | Display Mainbody  | On                                                                                    |  
| Default | RTL Support       | On                                                                                    |  
| Default | Module Overlays   | On                                                                                    |  
| Default | Page Suffix       | On                                                                                    |  
| Default | RT Typography     | Enabled: On, Typography Styling: Light                                                |  
| Default | RT Extensions     | On                                                                                    |  
| Default | K2 Styling        | On                                                                                    |  
| Default | IE7 Redirect      | On                                                                                    |

### Assignments
| Style | Option    | Setting |  
| :---- | :-------- | :------ |  
| Home  | Main Menu | Home    |  

[demo25]: assets/Halcyon.jpg
[menu]: ../../start/menu.md
[Style]: http://www.gantry-framework.org/documentation/joomla/configure
[halcyon2]: assets/halcyon2.jpeg