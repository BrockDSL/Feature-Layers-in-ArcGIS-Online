![image](https://user-images.githubusercontent.com/45638590/176009670-5a28dcc6-1b48-4092-b5b5-567413f1990d.png)

# Creating a Feature Layer in ArcGIS Online
This tutorial provides step-by-step instructions for creating a new feature layer in ArcGIS Online using the key waypoints in Laura Secord's journey from Queenston to Thorold.

----

## Setup Instructions
In preparation for this tutorial, you will need an ArcGIS Online Organizational account or your Brock University credentials. NOTE: you cannot create features with a public account using these steps.

Download the [Laura Secord Images zip folder](https://github.com/BrockDSL/feature-layers-in-arcgis-online/blob/main/FeatureImages.zip) and extract all files.

----

## Tutorial

1. Go to arcgis.com and click Sign in.
2. Click "Your ArcGIS Organization's URL".
3. Enter the text 'brock' to complete the URL. Click Continue.
4. Click Brock University. You will be taken to the Brock University authentication page where you will enter your Brock credentials and click Sign in.
5. From the tabs across the top, click **Content**.
6. Click **+ New Item**.
7. Select **Feature layer - design your own layer**.
8. Enter a layer name and select *point, line or polygon*. This example will create a point layer.
9. Click **Next**.

![image](https://user-images.githubusercontent.com/45638590/175981617-a38acf86-2048-46bb-87fc-458ba6ba1b8b.png)

10. Enter a Title, folder, tags and summary for the new feature layer.
11. Click **Next**.
12. The Item Description page appears. Add a summary and details as required.
13. Click **Data**, click **Fields** from the top right, click **Add field**.

![image](https://user-images.githubusercontent.com/45638590/175981930-c658e791-9297-4b93-8398-d06f947d5219.png)

14. Enter a **Field Name** (i.e. Label), **Display Name** (alias such as **Label**), **Type** (i.e. string), **Length** (for descriptions, increase the size to 2,000 or more. For labels, reduce the length to 30.)
15. Click **Add New Field** and repeat for all the fields you wish to enter.
16. Click the **Overview** tab.
17. Click **Open in Map Viewer**.

##Editing##

1. Click ![image](https://user-images.githubusercontent.com/45638590/175988242-36039c00-7f4b-489e-aee0-da602b5f2079.png) and select **Search** to enter a placename (i.e. Queenston). Hit enter or click an option from the list.
2. Click the X to close the search results.
3. To start an 'edit session', click ![image](https://user-images.githubusercontent.com/45638590/175983304-2c2f8510-16a9-4f94-a5dc-bd5fe3e85782.png) from the lower right menu.
5. Click **New feature** button then click the location on the map. **NOTE: You can update the geometry any time during an edit session**. You will be prompted to fill in the various fields of information (i.e. Label "Queenston", Description "Site of the Secord Homestead").
6. Click **Create**.
7. Repeat for additional features. For example, zoom to **St. Davids**, add a feature labeled as such with the description "Laura's first stop was at her relatives' homestead in St. Davids".
8. Additional feature stops for Laura's journey would include: 
- Homer (Laura would've had to cross Ten Mile Creek at Homer)
- Shipman's Corners (known as St. Catharines downtown today. Note the search tool doesn't recognize the historical name)
- Power Glen (Another crossing of the Twelve Mile Creek and uphill climb)
- Decew House (Finally, Laura is escorted to Decew House by the natives to give her warning to Lt. Fitzgibbon)
9. When you are finished adding featuress, click the 3 dots beside the layer name and click **Save**.

![image](https://user-images.githubusercontent.com/45638590/175997941-31a7620a-cb6c-43ac-9c62-20eccb0272b3.png)


##Adding Images##

1. Click the 3 dots beside the layer name and click **Show Properties**. The item's properties panel appears on the right.
2. Click **Information** from the properties panel.

![image](https://user-images.githubusercontent.com/45638590/175998936-5941370b-3d86-422f-9fbc-c710b4981967.png)
 
3. Under **Source Layer** click **Tutorial Points > Feature Layer**. This will open a new window showing the feature layer item description.
4. Click **Data**. You will see the feature entries including the defined fields (Description, Label). Notice also the field titled **Photos and Files**.
5. Under the Photos and Files field, click **Add** and upload the related image.
6. Click **Upload**.
7. Click **Close**.
8. Repeat for the remaining images. NOTE: You can upload more than one image per record.

##Editing the Table

1. To edit a field in the table, double-click the entry. 

##Creating Pop-ups

1. Continuing from above, click the **Overview** tab then click **Open in Map Viewer**.
2. Clicking a point on the map will result in the default pop-up.

![image](https://user-images.githubusercontent.com/45638590/176007064-c137d2b9-048a-4500-92d1-a53ab77210ce.png)

3. Click the configure pop-ups tool from the right ![image](https://user-images.githubusercontent.com/45638590/176007368-23601382-62ad-4a36-aac2-5e9160b12e47.png)

4. The pop-ups panel appears to the right of the map view.
5. Click **Title** and in the entry window, delete the default and type in the code **{Label}**. See below.

![image](https://user-images.githubusercontent.com/45638590/176007936-88b89824-d37a-4e6a-9ac7-66c44359f11a.png)

6. This action defines the title for the pop-up from the entry in the table with the field name **Label**. Notice the pop-up updates on-the-fly.
7. Next, click the 3 dots beside **Fields list** and click **Delete**.
8. Then, click **+ Content** and select **Text**.
9. Enter the code **{Description}** to insert the **Description** field from the table. Click OK. The result shows the description BELOW the image.
10. From the configure pop-up panel, drag and drop the description content above the "attachment" content.

![image](https://user-images.githubusercontent.com/45638590/176008768-017eda8a-e4a6-4673-91b1-6b32f688614e.png)

The results should reflect the new order of things.

![image](https://user-images.githubusercontent.com/45638590/176008919-93c6e1cc-ef4d-4405-a777-ac11225f9723.png)

11. To save the configured pop-ups with the layer, click the Tutorial Points layer menu (3 dots beside the layer name) and click **Save**.

##Visualization

1. Continuing from above, click the **Styles** button ![image](https://user-images.githubusercontent.com/45638590/176010512-40afcbf1-fe40-4801-b5c5-ac84bdbe2196.png)
 from the top of the right menu.
2. From step 2, click **Location (Single Symbol)**

![image](https://user-images.githubusercontent.com/45638590/176010862-872e5b9e-68de-4226-94e8-0f798d3a8fb7.png)

3. Click **Symbol Style** > **Current Symbol**
4. Select a **Category** such as 

----

## Next Steps (Optional)
This is where you can add any additional resources, follow up tutorial, or workshop reccomendations that users might use to continue learning about the tool described in the tutorial.  The more the better!

----

**End notes**
This is where you mention the DSL, MDGL, or Research Lifecycle department and put in contact information.  An example of what this might look like is:

**This tutorial is supported by the Brock University Research Lifecycle Department.  If you have any questions or concerns regarding this tutorial, don't hesitate to contact [DSL@Brocku.ca](mailto:DSL@Brocku.ca)**
