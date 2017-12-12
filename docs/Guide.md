# OE UI Designer

The `oe-ui-designer` component is a plugin to `oe-studio` and helps design/create html pages.

## Navigating to UI Designer

To navigate to UI Designer, first Go to [oe-designer](http://localhost:3000/designer) and click on the UI Designer icon as marked in the below image:

![Start Page][start-page]

you will be navigated to UI Designer, now to design a new html page, click on `Create/Manage Components` button.

![UI Designer][ui-designer-home]

A menu will appear which shows the available options to create a page.

![Create/Manage Components][create-manage-component]

This menu has two options when creating the page which are to create a polymer component or a static page.

![Polymer Components Menu][create-polymer-component]
![Static Page Menu][create-static-page]

### Create polymer component using UI Designer

In the create/manager components menu we can select **Polymer Components** and then **Add Component** as seen in below image.

![Add Polymer Component][add-polymer-component]

The **Add Component** will take you through steps to select options during creation of component.

![Add Component][add-component]
![Add Component Name][add-component-name]
![Add Component Template][add-component-template]

You will now get a blank template page, where you can start the design for the component. The central white space is where you can drag drop elements.

![Create Component][create-component-html]

The footer of this page has operations that can be performed
1. Set URL for the page, which would allow for a preview of the page
2. Undo/Redo the changes done in the HTML
3. Desktop/Mobile View
4. Save/Download
5. HTML DOM
6. Page Preview (if URL is set)
7. Style/Attribute Options

The first step would be to create a layout where you can drag/drop elements. The following two screenshots show you the Layout menu and Text Element Menu.

![Add Layout][add-layout]
![Add Text Element][add-text-element]

After adding a H1 Text Element, you can edit the text and add options to the element selected.

![Element Options][element-options]

In the right side explorer menu, has the following operation
1. Add/Search attributes of the element
2. Adding inline styles or class
3. Style manager for maintaining local/global styles
4. Tree view of elements in the page
5. Attach model to the page
6. Asset management

[start-page]:  images/start-page.PNG "Start Page"
[ui-designer-home]: images/home.PNG "UI Designer"
[create-manage-component]: images/footer.PNG "Create/Manage Components"
[create-polymer-component]:images/footer-polymer.PNG "Polymer Components Menu"
[create-static-page]:images/footer-static.PNG "Static Page Menu"
[add-polymer-component]: images/create-component.PNG "Add Polymer Component"
[add-component]: images/add-component.PNG "Add Component"
[add-component-name]: images/add-component-name.PNG "Add Component Name"
[add-component-template]: images/add-component-template.PNG "Add Component Template"
[create-component-html]: images/create-html.PNG "Create Component HTML"
[set-component-url]: images/create-html-seturl.PNG "Set Component URL"
[html-dom]: images/create-html-elements.PNG "HTML DOM"
[add-layout]: images/create-html-layout.PNG "Add Layout"
[add-text-element]: images/create-html-text-ele.PNG "Add Text Element"
[element-options]: images/create-html-options.PNG "Element Options"