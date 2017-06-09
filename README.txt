

[+] INSTALLATION INSTRUCTIONS [+]


Some setup on the site is required before installation

--> Prerequisites <---

Date API
EntityForm
Entity Reference
Entity API


1. Create a content type for your events
2. Create a Date field on that content type - collect an ending date
3. Create an EntityForm to use for collecting comments. This will be the default EntityForm
4. Create an Entity Reference field on your EntityForm referencing your events content type


--> Installation <---

1. Install the module the same way you would install any module. Uncompress this module inside the sites/all/modules/ directory of your site
2. Browse to the configuration page here /admin/config/entityform-custom-settings
3. Fill out the fields on the configuration page. The fields will be populated with example default values
4. Once all of the fields are correct, click "Save Configuration"
5. After the first save of the configuration the features are now ready to use

--> How to Use <---

1. Create a new event. Add your content. Add your to and from dates
2. Scroll down at the bottom of the event you will see a field that says "Attach an Entity Form"
3. The default entity form id will be in there. You may also choose a different entityform to attach to the event if you choose
4. Save the event
5. View the event. If the dates are valid, you will see a link to leave a comment

You can then go on to create Views that pull submissions based on event reference
You can also limit what fields people see versus what editors see by using the "Field Permissions" module