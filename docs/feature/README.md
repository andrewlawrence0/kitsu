# Create a Feature Film Production

Now that you have designed your workflow in Kitsu and invited more people, it's time to create your production. 

Click on the **Create a new
production** button.

![Create a production](../img/getting-started/create_production.png)

Enter your production name, and choose **Feature Film** as the **type**, then select the style of your production (2D, 3D).


Then, you must fill in technical information, such as the number of FPS, the Ration, and the Resolution.

All these data will be used when Kitsu re-encodes the video previews uploaded.

Then, you need to define your production's start and end dates.

![Add a production](../img/getting-started/add_production.png)

You can define your production workflow in the next part, 3 to 6.



You need to select your asset task type (3), shot task type (4), task status (5), and asset types (6).

![Add a production Pipeline](../img/getting-started/add_production_pipe.png)


::: tip
To create your **Production Workflow**, you will select Task Types from the Global Library.

If you realize you missed some Task Types, you can create them later.

See the [Studio Workflow](../first_production/README_configure_Kitsu.md#studio-workflow) section.
:::

Then, 7 and 8 are the option parts. If you already have a spreadsheet with your asset/shot.

See the **import CSV** section for more details.

[Import asset](../batch-action/README.md#create-assets-from-a-csv-spreadsheet-file)

[Import shot](../batch-action/README.md#create-shots-from-a-csv-spreadsheet-file)

Validate everything with the ![All done](../img/getting-started/all_done_go.png) button.






## Introduction to Kitsu global Page



Welcome to Kitsu's global asset page.

Let's take a look around.

![Presentation of the global page](../img/getting-started/presentation_global.png)

On the top part (1), you have the **global navigation**, which is always visible throughout all the production pages.

**From left to right:**


### Main Menu

You will open the main menu by clicking on the top left button, Kitsu![Main menu button](../img/getting-started/main_button.png) (or your Studio logo).

On the main menu, you will find direct access to your assigned tasks, productions, global and team schedules, the workflow customization page, and the Kitsu settings.

::: details Main Menu Details
**WORKSPACE**
- My Tasks: your assigned tasks 
- My Checks: All the tasks with status **Is Feedback Request** depending on your department(s)
- My Productions: Get back to the selection on the production page.


**STUDIO**
- Productions
- People
- Timesheets
- Main Schedule
- Team Schedule
- All tasks
- News Feed
- Entity Search


**ADMIN**
- Departments
- Task Types
- Asset Types
- Custom Actions
- Automation
- 3D Backgrounds
- Bots
- Settings
- Logs

::: warning Permission Visibility
The WORKSPACE section is enabled for all permissions except My Checks, which artists do not see.

Artist (and above) can also see their own **Timesheets**, and have access to the **Entity Search**
:::

### Navigation

You will see the navigation dropdown menu on the right of the main menu icon.

![Presentation of the global page](../img/getting-started/presentation_global_header.png)


You can choose between production. The name of the actual production and actual page are always displayed.

You can use the dropdown menu to navigate from production to production (if you have several).

Once you have selected a production, the next dropdown menu will help you navigate through the different pages of this production.


::: details Navigation details
The first section is about the tracking of your tasks
- Assets
- Shots
- Sequence
- Edits (If you have created specific tasks)

The second section is more about the side of the production
- Concepts
- Breakdown
- Playlists
- News feed

The third section is about statistics
- Sequence Stats
- Asset Type Stats

The fourth section is related to Team Management
- Schedule
- Quotas
- Team

The fifth section is about the settings of your production
- Settings

::: tip
You start with the asset page, but you can change your production homepage to other entities (see setting page)
:::



### Global Search, News, Notification and Documentation
You have the global search on the right of the navigation dropdown menu. It's a quick access search that will display the four first results. If you need more results and filtering options, see the **Entity Search** page.


The next icon ![News](../img/getting-started/canny.png) is a direct link to our news and feedback page. 

You can see all the new features with an animated gif and also add suggestions about the next feature you want to see in Kitsu.


Then, the bell shows you your notification (assignation, comments, tag)![Notification](../img/getting-started/notification_icon_on.png). The number of notifications unread will appear in the bell icon.



The last icon before your avatar is the documentation button.
![documentation button](../img/getting-started/documentation_button.png), that you are reading right now!


### Personal Settings
You can click on your avatar to open your menu (setting, documentation, etc.).

![Profile enlarged](../img/getting-started/profil_enlarge.png).

## The Tasks Spreadsheet

### Entitie spreadsheet

The second part of the screen is common to all the entities (asset, shot, sequence, Edit). This is the global tasks spreadsheet.

Here, you see the status, assignation, priority, etc, for each task.

::: tip
The spreadsheet's first line and column header always appear at the top of the page, even if you scroll down.

You can also **Stick** other columns to keep them visible at all times.
:::

### Filters

The first element on the left is the filter box. You can type anything you want for simple filtering, sequence, asset type, etc.

If you need more advanced filtering, please use the filter builder button.

![Filter Builder](../img/getting-started/filter_builder.png)

You can then save all the filters and use them as your pages.

::: warning
You must press **Enter** on your keyboard to launch the filters on a feature film.
:::

### Simplify the display

On the right part of the screen, there are some buttons (from left to right) to hide or display the assignation, hide or display the extra column, enlarge or reduce the thumbnail,
![display and Hide option](../img/getting-started/display_hide_option.png)


### Import / Export
batch import thumbnail ![batch import thumbnail](../img/getting-started/add_thumbnails.png), and finally import ![Import button](../img/getting-started/import.png) or export ![export button](../img/getting-started/export.png) data.



### Metadata column
Below, you have the name of the column. the (+) next to **Name** ![Add metadata column](../img/getting-started/add_column_custom.png) is here to create a new metadata column. Then, you have the name of the task type column.

### Customize the view
On the far right of the screen, next to the scroll bar, is the option to hide and display a text column

![Display/hide text column](../img/getting-started/visible_column_detail.png).


### Sum-up of your view
The last part (4), at the bottom of the screen, is the sum-up of your displayed page. It means the sum-up will update if you filter the page.

You can see the number of elements (assets or shots), the total number of estimated days, and the total number of days already spent.



## Create an Asset
### Create your first asset
So, now that we have created our production and have a general grasp of the Kitsu interface, it's time to create our first asset.

On the asset page, click on **Add assets**.

![Asset page first time](../img/getting-started/add_assets_first.png)

::: warning
When you create an asset, your task workflow will be applied, and **all the tasks will be created simultaneously as the asset**.
:::

A pop-up window opens:

It asks you to choose the **Asset Type** (1).
If you didn't add a new asset type, Kitsu will provide examples such as Characters, Environment, FX, Props, etc. 
Let's start with a character.

::: tip
You can also customize the asset type list and the tasks pipeline.
[Customization of the workflow](../customization-pipeline/README.md#modify-an-existing-asset-types) )
:::

We give it a **Name** (2) and enter a description that helps the Artist know what to do and quickly identify the asset.

Click on **Confirm and stay** if you have multiple assets to create.


![Create an asset](../img/getting-started/add_asset_popup.png)

You can change the asset type and keep adding assets.

::: tip
The newly created asset appears in the background whenever you click on **Confirm and stay**.
:::

After adding your last asset, click
on **Confirm**. It will create the asset and close the window. 

::: tip
If you click on **Confirm and stay** but realize you don't have more assets to add, click on **Close**, and the window will be canceled.
:::

![Global asset page](../img/getting-started/asset_edit.png)

You will also see the tasks that are selected for your assets workflow are created at the same time.


If you need to add more **Assets**, click the **+ Create assets** button.

::: details Create Assets from a CSV Spreadsheet File
You may already have your asset list ready in a spreadsheet file.
With Kitsu, you have two ways to import them; the first is to import a `.csv` file and copy-paste your data directly into Kitsu.

First, save your spreadsheet as a `.csv` file.

Then, go back to the asset page on Kitsu and click on the **Import** icon.
![Import Icon](../img/getting-started/import.png)

A pop-up window **Import data from a CSV** opens. Click on **Browse** to pick your `.csv` file.

![Import csv file](../img/getting-started/import_csv_asset.png)

To see the result, click on the **Preview** button.
  
You can check and adjust the name of the columns by previewing your data.
 
NB: the **Episode** column is only mandatory for a **TV Show** production.
 
![Import data copy paste data](../img/getting-started/import_preview_data.png)

Once everything is good, click the **Confirm** button to import your data into Kitsu.

You have imported all your assets into Kitsu and created the task according to your Settings.

![Import data copy paste data](../img/getting-started/import_result_asset.png)
:::

::: details Create Assets by Copying / Pasting a Spreadsheet File

Open your spreadsheet, select your data, and copy them.

![Import copy data](../img/getting-started/import_copypas_asset.png)

Then, go back to the asset page on Kitsu and click on the **Import** icon 
![Import Icon](../img/getting-started/import.png).

A pop-up window **Import data from a CSV** opens; click on the **Paste a CSV data** tab.

![Import data copy paste tab](../img/getting-started/import_pastcsvdata_asset.png)
 
You can paste your previously selected data and see the result with the **Preview** button.
 
![Import data copy paste data](../img/getting-started/import_pastcsvdata2_asset.png)
  
You can check and adjust the name of the columns by previewing your data.
 
NB: the **Episode** column is only mandatory for a **TV Show** production.
 
![Import data copy paste data](../img/getting-started/import_preview_data.png)

Once everything is good, click the **Confirm** button to import your data into Kitsu.

You have imported all your assets into Kitsu and created the task according to your Settings.

![Import data copy paste data](../img/getting-started/import_result_asset.png)
:::

### See the Details of an Asset

To see an asset's detail, click on its name.

![Asset detail](../img/getting-started/asset_detail.png)

A new page opens with the list of the tasks, the assignation, and the status newsfeed on the right.


![Asset detail page](../img/getting-started/asset_detail_page.png)

You can click on the status of each task to open the comment panel and see the history of the comments and the different versions.


![Asset detail page](../img/getting-started/asset_detail_page_panel.png)



You can also access the **Casting**, 

![Asset detail casting](../img/getting-started/asset_detail_page_casting.png)

**concept** linked to this asset, 

![Asset detail casting](../img/getting-started/asset_detail_page_concept.png)

The **Schedule** is available if you have previously filled out the task type page data. If you have already filled out the data, you can modify them directly here. 

![Asset detail casting](../img/getting-started/asset_detail_page_schedule.png)

the **Preview Files** uploaded at various task types, 

![Asset detail casting](../img/getting-started/asset_detail_page_file.png)

And the **Timelog** if people have filled out their timesheet on the tasks of this asset.

![Asset detail casting](../img/getting-started/asset_detail_page_timelog.png)



## Add more tasks after creating the assets


If you realize **after** creating the assets that the task is missing, you can still add them.

First, ensure the missing task type is added to the settings page under the task type tab.

Then go back to the asset page and click on **+ Add tasks**






 ### Update your assets
You can update your assets at any point, change their name and asset type, modify their description, and add any custom information you added to the global page.

You can edit assets by going to the asset page, hovering over the asset you want to modify, and then clicking on the **edit** button
![Edit button](../img/getting-started/edit_button.png) (1) on the right side of
the line.

![Edit an asset](../img/getting-started/asset_edit01.png)

To extend the description on the main asset page, click on the first words (2), and a pop-up with the full description will open.

To delete an asset, see the FAQ : [How to delete an asset](../faq-deletion/README.md##how-to-delete-an-asset)


::: details Update Assets with the CSV Import
You can use the CSV import to update your data quickly.

You can update the **type** of an asset, the **Assignation**, the **Status** of tasks, and add a **Comment**.

You need to switch on the option **Update existing data**. Then, the lines that will be updated
will be highlighted in blue.

![Import data copy paste data](../img/getting-started/import_update_asset.png)

:::


::: details Update Assets by Copying / Pasting a Spreadsheet File

Open your spreadsheet, select your data, and copy them.

![Import copy data](../img/getting-started/import_copypas_asset.png)

Then, go back to the asset page on Kitsu and click on the **Import** icon 
![Import Icon](../img/getting-started/import.png).

A pop-up window **Import data from a CSV** opens; click on the **Paste a CSV data** tab.

![Import data copy paste tab](../img/getting-started/import_pastcsvdata_asset.png)
 
You can paste your previously selected data and see the result with the **Preview** button.
 
![Import data copy paste data](../img/getting-started/import_pastcsvdata2_asset.png)
  
You can check and adjust the name of the columns by previewing your data.

NB: the **Episode** column is only mandatory for a **TV Show** production. 
 
You need to switch on the option **Update existing data**. Then, the lines that will be updated
will be highlighted in blue.

![Import data copy paste data](../img/getting-started/import_update_asset.png)

You have imported all your assets into Kitsu and created the task according to your Settings.

![Import data copy paste data](../img/getting-started/import_result_asset.png)
:::


## Create a Concept
### Upload a Concept

To create a **Concept**, go to the **Concept** page with the navigation menu.

![Concept Menu](../img/getting-started/menu_concept.png)

To upload a concept, click the **Add a new reference to concepts** button.

You can upload one or several concepts at the same time.

![Concept empty page](../img/getting-started/concept_empty_prod.png)

Once you upload your previews, the concept page will look like this.

![Concept filled page](../img/getting-started/concept_filled_prod.png)


You can interact with the concept in two ways: click on the picture to see an enlarged view.
The second is to click on the status part to open the **Comment Panel** on the right.

On the comment panel, you have two options: link a concept to an existing asset or delete it.
You can also comment and change the status of the asset.

The idea is to have one version per **Concept**. If it's not validated, you need to upload a new concept, not to have multiple versions of the same concept.

One concept is one task.


![Concept options](../img/getting-started/concept_options.png)


### Link a Concept to an Asset

Once concepts are uploaded, you can link them to the assets.

You can see the links on the status part of the assets.

Click on the status part of the concept; it will open the comment panel on the right.

![Concept Comment Panel](../img/getting-started/concept_comment_panel.png)

At the top of the comment panel, you have two options: Link a concept to an asset and delete the concept.

To link an asset, click on the **Link** ![Link button](../img/getting-started/link_icon.png) button.

Kitsu will display all the **Assets** available to link with the concept uploaded.

Kitsu will list the linked assets at the top of the comment panel. For now, there are No Links.


![Concept link](../img/getting-started/concept_link.png)

To link an asset, click on it. The names of the linked assets will appear at the top of the screen under the preview of the concept.


![Concept asset linked](../img/getting-started/concept_asset_linked.png)

Once a concept is linked to an asset, it can be seen on the asset's detail page.

Return to the asset page, and click on the asset name you want to see the concept.

![Detail asset page](../img/getting-started/asset_detail_page.png)

Per default, the casting detail is displayed on the second part of the screen. 
Use the dropdown menu to choose the concept.

![asset detail concept](../img/getting-started/asset_detail_concept.png)

Once in the concept section, you will see all the concepts created for this asset. You can filter them per status.

![asset detail concept list](../img/getting-started/asset_detail_concep_listt.png)


## Create a Shot
### Create your first shot

It's time to create **shots** for your production.

::: warning
Shots are linked to Sequences in Kitsu.
This means you must create a sequence and then populate this sequence with shots.
:::

You need to go to the **Shots** page: you can use the
dropdown menu and click on the **SHOTS**.

![Drop down menu shot](../img/getting-started/drop_down_menu_shot.png)

Click on the **Add shots** button to start with the shot creation.

![First add shots](../img/getting-started/new_shot.png)

::: warning
When you create a shot, the task workflow you have designed will be applied, and all the tasks will be created at the same time as the shot.
:::

A new pop-up opens for the creation of the shots.
You can now create the sequences and the shots.

Enter the first sequence, for instance, sq01,
then **add**. 

Now, you can see your sequence has been created. To add shots to this sequence, select it and create your shots.

For example, type sh0010 on the shots column, then again **add**.
You can also define padding for your shots.

::: tip
If you want to name your shots ten on ten as SH0010, SH0020, SH0030, etc, set the **Shot Padding** as 10
:::

![Manage shots](../img/getting-started/manage_shot.png)

You can now see that new shots are listed and linked by their sequence.
You have created the first shot of the first sequence.

Now, let's add more shots than just one! As you can see, the box already contains your name
code but incremented, so you have to continue to click on **add** to
create more shots.

![Add shots](../img/getting-started/add_shots.png)

To add more sequences, go to the left part, type the name of your new sequence, and then click on **add**.
Your second sequence is selected, and you can now add shots.

::: tip
If a shot is misplaced on a sequence, you have to edit the shot
![Edit button](../img/getting-started/edit_button.png), and change the
sequence.
![edit shot Change sequence](../img/getting-started/edit_shot.png)

![Change sequence](../img/getting-started/change_seq.png)
:::


To delete a shot, see the FAQ : [How to delete a shot](../faq-deletion/README.md#how-to-delete-a-shot)

To delete a sequence, see the FAQ : [How to delete a Sequence](../faq-deletion/README.md#how-to-delete-a-sequence)




## Create Shots from an EDL File
You may already have your shots list ready in an **EDL** file.
With Kitsu, you can directly import your **EDL** file to create the sequence, shot, number of frames, and Frame in and out.

On the **Global Shot Page**, you will see an **Import EDL** button.

![Import EDL Button](../img/getting-started/import_edl_button.png)

You can select the naming convention of the video file used during the editing on the pop-up.

![Import EDL Menu](../img/getting-started/import_edl_menu.png)

It means the video clip on the editing is named as project_sequence_shot.extension.

Here is an example of an EDL for the LGC production.

![EDL Example](../img/getting-started/edl_example.png)

The video files are named  LGC_100-000.mov, which means LGC is the production name, 100 is the sequence name, and 000 is the shot name.

You can import the EDL file once you have the naming convention.

Then click on **Upload EDL**

Then Kitsu will create the shots.

![EDL Shot creation](../img/getting-started/edl_shot_creation.png)
:::

::: details Create Shots from a CSV Spreadsheet File
You may already have your shots list ready in a spreadsheet file.
With Kitsu, you have two ways to import them; the first is to import a `.csv` file directly, and the second is to copy-paste your data directly into Kitsu.

First, save your spreadsheet as a `.csv` file.

Then, return to the shot page on Kitsu and click the **Import** icon.
![Import Icon](../img/getting-started/import.png)

A pop-up window **Import data from a CSV** opens. Click on **Browse** to pick your `.csv` file.

![Import csv file](../img/getting-started/import_csv_shot.png)

To see the result, click on the **Preview** button.
  
You can check and adjust the name of the columns by previewing your data.
 
NB: the **Episode** column is only mandatory for a **TV Show** production.
 
![Import data copy paste data](../img/getting-started/import_preview_data_shot.png)

Once everything is good, click the **Confirm** button to import your data into Kitsu.

All your shots are imported into Kitsu, and the task is created according to your **Settings**.

![Import data copy paste data](../img/getting-started/import_result_shot.png)
:::


::: details Create Shots by Copying / Pasting a Spreadsheet File
Open your spreadsheet, select your data, and copy them.

![Import copy data](../img/getting-started/import_copypas_shot.png)

Then, go back to the shot page on Kitsu and click on the **Import** icon 
![Import Icon](../img/getting-started/import.png).

A pop-up window **Import data from a CSV** opens; click on the **Paste a CSV data** tab.

![Import data copy paste tab](../img/getting-started/import_pastcsvdata_shot.png)
 
You can paste your previously selected data and see the result with the **Preview** button.
 
![Import data copy paste data](../img/getting-started/import_pastcsvdata2_shot.png)
  
You can check and adjust the name of the columns by previewing your data.
 
NB: the **Episode** column is only mandatory for a **TV Show** production.
 
![Import data copy paste data](../img/getting-started/import_preview_data_shot.png)

Once everything is good, click the **Confirm** button to import your data into Kitsu.

All your shots are imported into Kitsu, and the task is created according to your **Settings**.

![Import data copy paste data](../img/getting-started/import_result_shot.png)
:::

### See the Details of a Shot

If you want to see the details of a shot, click on its name.

![Shot detail](../img/getting-started/shot_detail.png)

A new page opens with the list of the tasks, the assignation, and the status newsfeed on the right.
You can navigate through each by clicking on the name of the tabs.

![Shot detail page](../img/getting-started/shot_detail_page.png)

You can click on the status of each task to open the comment panel and see the history of the comments and the different versions.


![Shot detail page](../img/getting-started/shot_detail_page_panel.png)


You can also access the **Casting**, 

![Asset detail casting](../img/getting-started/shot_detail_page_casting.png)


The **Schedule** is available if you have previously filled out the task type page data. If you have already filled out the data, you can modify them directly here. 

![Asset detail casting](../img/getting-started/shot_detail_page_schedule.png)

the **Preview Files** uploaded at various task types, 

![Asset detail casting](../img/getting-started/shot_detail_page_file.png)

And the **Timelog** if people have filled out their timesheet on the tasks of this asset.

![Asset detail casting](../img/getting-started/shot_detail_page_timelog.png)




## Add more tasks after creating the shots
If you realize after creating the shots that the task is missing, you can still add them.

First, ensure the missing task type is added to the settings page under the task type tab.

Then go back to the shot page and click on + Add tasks.


### Update your shots

You can update your shots at any point, change their names and sequences, modify their descriptions, and add any custom information you added to the global page.

You can edit shots by going to the shot page, hovering over the shot you want to modify, and then clicking on the **edit** button
![Edit button](../img/getting-started/edit_button.png) (1) on the right side of the line.

![Edit an asset](../img/getting-started/asset_edit01.png)

To extend the description on the main shot page, click on the first words (2), and a pop-up with the full description will open.


::: details Update Shots Information with CSV Import
You can use the **CSV Import** to update your data as the **NB Frames**, **Frame IN**, **Frame Out**, or any custom **Metadata column**.

You can update the **Assignation**, and the **Status** of tasks and add a **Comment**.

Open your spreadsheet, select your data, and copy them.

![Import copy data](../img/getting-started/import_copypas_shot.png)

Then, go back to the shot page on Kitsu and click on the **Import** icon 
![Import Icon](../img/getting-started/import.png).

A pop-up window **Import data from a CSV** opens; click on the **Paste a CSV data** tab.

![Import data copy paste tab](../img/getting-started/import_pastcsvdata_shot.png)
 
You can paste your previously selected data and see the result with the **Preview** button.
 
![Import data copy paste data](../img/getting-started/import_pastcsvdata2_shot.png)
  
You need to switch on the **Option: Update existing data**.
The updated shots will be in blue.

 
NB: the **Episode** column is only mandatory for a **TV Show** production.
 
![Import data copy paste data](../img/getting-started/update_preview_data_shot.png)

Once everything is good, click the **Confirm** button to import your data into Kitsu.

All your shots are imported into Kitsu, and the task is created according to your **Settings**.

![Import data copy paste data](../img/getting-started/import_result_shot.png)
:::



## Add the number of Frames and Frame ranges to the shots

At this stage of the production, the animatic should be done. This means you have
the length (**number of frames**, **Frame range In**, and **Frame range Out**) for each shot. You can
add this information to the spreadsheet. This way, you are sure that all
the frames are calculated and none are missing or over-computed.

::: warning
If you have created your shots and sequence by hand, 
the **Frame** column will be hidden. You must edit at least one shot and fill in the number of frames to display the **Frame** column.
The column will be displayed if you have created your shots and imported the number of frames with a CSV/spreadsheet.
:::



You need to edit the shots to fill in the frame range information. Click on the
edit button ![Edit button](../img/getting-started/edit_button.png) on the right
side of the shot line.

![edit shot Change sequence](../img/getting-started/edit_shot.png)

You can enter the shots **In** and **Out ** in the new window. Then, save by clicking the **Confirm** button.



![Shot edit page](../img/getting-started/shot_edit.png)

Now, the frame range appears on the general spreadsheet of the shot page.

![Shot edit page](../img/getting-started/shot_framerange_global.png)

Now that you have unlocked the **Frames**, **In**, and **Out** columns, you can fill them
directly from the global shot page.

Click on the case you want to fill in and add the data.

::: tip
If you enter the **Frame In** and **Frame Out**, Kitsu automatically calculates the **Number of Frame**.
:::

![Shot edit page](../img/getting-started/shot_framerange_global_edit.png)


You can also use the **CSV Import** to update your frame range quickly.
 [Update Shots information with CSV Import](../batch-action/README.md#update-shots-information-with-csv-import)

You can also access the history of shot values.

![Shot framerange detail](../img/getting-started/shot_framerange_detail.png)

![Shot Values History](../img/getting-started/shot_values_history.png)


## Create Custom Metadata Columns

To add more information on the general spreadsheet pages, you must create a custom **metadata column**.

You may have extra information to add to your pages, such as the **level of difficulties**, **Weather**, **Tag**, etc. You can store all text (or number) information in the custom metadata column.


Click on the **+** near the Name column.

![Metadata Column](../img/getting-started/add_column_custom.png)



With the **Type** option, you can choose how you want to store your information:
- a free **Text**, 
- a **Number**, 
- a **Checkbox**, 
- a **List of value**,
- a **List of tags**,
- a **Checklist**.

![Metadata Column detail](../img/getting-started/custom_column_detail.png)

::: warning 
The **Text**, **Number**, and **Checkbox** allow you to add different information for each entity. You don't have to plan it first.

The **List of value**, **List of tags**, and **Checklist** give you the same choice for each entity. Moreover, it has to be filled now.

![Metadata Column list](../img/getting-started/custom_column_list.png)

Type the list elements below **Available values**, and confirm them by clicking on **Add value**.
:::

You can also link the **metadata column** to one or several **departments**.

::: tip
Link a metadata column to a department. The artists/supervisors will see it on their to-do page and in the department-filtered view.

You can link the metadata column to one or more departments. Click on the department from the list and then click on **add** to be effective.

Here, the VFX column is linked to two departments.

![Department metadata column filtered view](../img/getting-started/department_filtered_view_column.png)

:::

::: details Edit meta column
On the global page of the asset or the shot, click on the arrow on the direct right of your metadata column and click on **Edit**.

![Metadata column Edit](../img/getting-started/custom_column_edit.png)
:::


You can fill in this information directly on the global spreadsheets page.
The cases are editable.

![Metadata Column detail](../img/getting-started/custom_column_list_edit.png)

::: tip
You can batch-modify the metadata column by selecting several entities on the left and then modifying your metadata column.
:::

::: details Edit by hand
You can also modify the information with the edit button ![Edit button](../img/getting-started/edit_button.png).

You now see a new line on the edit pop-up. You can select the information from the list,
alternatively, enter the free text or number, check a box, or use the checklist, depending on your previous choice.

Remember to press the **Confirm** button when you are done.

![Metadata Column detail](../img/getting-started/edit_asset_custom.png)
:::

Go to the general spreadsheet page to edit or delete the metadata column.
Nearby the name of your metadata column, click on the arrow ![Metadata Column detail](../img/getting-started/arrow.png).

::: tip
You can **sort** your global page with this new column. Click the arrow on the right of the column name to open his menu. Then click on **Sort By**.

You can also **Stick** the metadata column to the left.
:::


## Create a Sequence

In Kitsu, you can also track tasks at the **Sequence** Level.
It's especially useful when
you have macro tasks to track, like Story and color Board, Color Grading, etc.

Use the navigation menu to go to the **Sequences** page.

![Navigation Sequences](../img/getting-started/drop_down_menu_sequence_page.png)

::: warning
This new page behaves like the asset and shot global page.

To use this page, You first need to create dedicated task types on your **Global Library**
 with the **Sequence** attribute.

See **Pipeline customization** Section to create a new **Task Type**.

[Pipeline customization](../customization-pipeline/README.md)

Once you have created your **Task Types**  on your **Global Library**, add them to your
**Production Library** (setting page).
:::

Once your task types are ready on the settings page, you must create a sequence (the same as the assets or shots).




This new page behaves like the asset and shot global page. You can add your edits with the **+ New Sequence** button.

You can assign tasks, do the review, change status, etc.

You can add a metadata column, fill in the description, etc.


::: tip
You can create a sequence directly from here (+New sequence button) or a sequence linked to your shots from the global shot page.
:::


You can **Rename** and **Delete** the Sequence entity on this page, as for the asset and shot entity.

If you click on the name of a sequence, you will see the detail page of this sequence.

![Sequence detailed page](../img/getting-started/sequence_detail_page.png)

On the detailed page, you have access to the sequence casting.
You can see all the assets used in the whole sequence.

You can also access the schedule, Preview Files, Activity, and Timelog of the sequence **tasks**.



## Create an Edit

You can track tasks at the **Edit** Level in Kitsu.

It's especially useful when
You have several edits to track through several validation steps. 
For example, you can track your whole movie, several trailers, the First Edit, Fine Edit, mix, etc.

::: warning
Per default, the **Edit** page will not be displayed until you have task types for it on your **production library** (setting page)
:::



To use this page, you need to first create a dedicated task type on your **Global Library**
 with the **Edit** attribute.

See **Pipeline customization** Section to create a new **Task Type**.

[Pipeline customization](../customization-pipeline/README.md)


Once you have created your **Task Types**  on your **Global Library**, add them to your
**Production Library**, you will see the **Edit** displayed on the navigation drop-down menu.


![Navigation Edit](../img/getting-started/drop_down_menu_edit.png)


This new page behaves like the asset and shot global page. You can add your edits with the **+ New edit** button.

You can assign tasks, do the review, change status, etc.

You can add a metadata column, fill in the description, etc.

::: tip
Depending on your deliveries, you can also change the resolution per **Edit**.
:::

::: warning
The detail page is different from the other entities.

As **Edit** focuses on a specific long video, the detail page looks more like the comment detail page.
:::

You can **Rename** and **Delete** the Edit entity on this page for the asset and shot entity.







## Create a Breakdown List

Filling out the breakdown helps you with the assembly of the shots. With the
breakdown, you have all the details of the assets you need to add to create your
shot, and we are sure to omit nothing.

On the dropdown menu, choose **BREAKDOWN**.

![drop down Menu breakdown](../img/getting-started/drop_down_menu_breakdown.png)

On the left of the breakdown page is the episode/sequence/shot menu (1); you can choose between those you created. They are the right part of
the screen; all the assets created are available for this production (main pack and episodes) (3). Moreover, in
the middle section, it is your selection for the shot (2).

![Breakdown page](../img/getting-started/breakdown_general_empty.png)

So now you have to select the shot you want to cast.

You can display the assets as text if you don't have thumbnails yet or enlarge the
thumbnails size.


![Breakdown page text display](../img/getting-started/breakdown_text_display.png)

You may also realize an asset needs to be added to the list during your breakdown.

You can create a new asset directly from the breakdown page. Click the **+** on the right of the **All available assets**.

![Breakdown page create asset](../img/getting-started/breakdown_create_asset.png)


You can also choose multiple shots at once. Click on the first shot, hold the **shift** key, and click on the last shot of your selection.

![Breakdown page global bulk select](../img/getting-started/breakdown_general_bulk_select.png)

Then click on the assets you want
to assign: characters, backgrounds, ... from the right part (3).
If you have selected multiple shots, your selection is applied to the numerous shots.

Copy a shot filled with assets and paste this asset selection into another shot.

You can see a **+1** or **+10** when you pass over the asset. It's the number
of times you add this asset, and you can click on it as many times as you need.

![Breakdown add asset](../img/getting-started/breakdown_add_asset.png)

You can also link all your assets to episodes on a TV show without specifying a sequence or shot.

![Breakdown episode asset](../img/getting-started/breakdown_episode.png)

This way, you can link all your assets to one or several episodes before the storyboard/animatic stage.

You can now see the asset in the middle of the screen (2). Next
to the asset's name is the number of times it has been added. In this
example, we have added the character asset Llama two times.


If you add an asset twice by mistake, you must go to the screen's middle part to select assets for this shot (2). From there, click on
**-1**. When you finish this shot, go on with the other shots.
Your selection is automatically saved.

![Breakdown remove asset](../img/getting-started/breakdown_remove_asset.png)

If a new asset is created during the storyboard, return to the asset
page (using the dropdown menu) and create the needed assets. The tasks previously created are applied immediately to these new
assets. However, you have to do the assignment, and then you can
continue with the breakdown.

Now, your **Breakdown** page should look like this.

![breakdown add asset bulk](../img/getting-started/breakdown_general_bulk_select_full.png)

You can also make a breakdown list for your assets if you need to assemble them and keep track of the separate parts.

On the top left corner of the screen, choose **asset** in the dropdown menu below **FOR**.

![Breakdown asset menu](../img/getting-started/breakdown_asset_menu.png)

You can now access a second dropdown menu to choose your asset type: **Character**, **Environment**, **Props**, **FX**, ...

![Breakdown asset type](../img/getting-started/breakdown_asset_menu_type.png)

You can complete the asset breakdown page the same way you did the shots. First, select one or more assets on the left part and then add the right part's elements.

::: details Create a Breakdown List from a CSV File

You may already have your breakdown list ready in a spreadsheet file. With Kitsu, you have two ways to import it: the first is to import a .csv file directly, and the second is to copy-paste your data directly into Kitsu.

First, save your spreadsheet as a `.csv` file following Kitsu's recommendation.

Click on the **import** button ![Import button](../img/getting-started/import.png)

A pop-up window **Import data from a CSV** opens. Click on **Browse** to pick your `.csv` file.

![Breakdown import csv file](../img/getting-started/import_breakdown_csv_file.png)

To see the result, click on the **Preview** button.

You can check and adjust the name of the columns by previewing your data.

NB: the **Episode** column is only mandatory for a **TV Show** production.

![Breakdown import Preview](../img/getting-started/import_breakdown_preview.png)

Once everything is good, click the **Confirm** button to import your data into Kitsu.

Now, you have your breakdown imported into Kitsu.

![Breakdown import Preview](../img/getting-started/breakdown_general_bulk_select_full.png)
:::

::: details Create a Breakdown List by Copying / Pasting a Spreadsheet File

Open your spreadsheet, select your data, and copy them.

![Import copy data](../img/getting-started/import_copypas_breakdown.png)

Then, go back to the breakdown page on Kitsu and click on the **Import** icon 
![Import Icon](../img/getting-started/import.png).

A pop-up window **Import data from a CSV** opens; click on the **Paste a CSV data** tab.

![Import data copy paste tab](../img/getting-started//import_breakdown_csv_file.png)
 
You can paste your previously selected data and see the result with the **Preview** button.
 
![Import data copy paste data](../img/getting-started/import_breakdown_preview.png)
  
You can check and adjust the name of the columns by previewing your data.
 
NB: the **Episode** column is only mandatory for a **TV Show** production.
 
![Import data copy paste data](../img/getting-started/import_breakdown_preview.png)

Once everything is good, click the **Confirm** button to import your data into Kitsu.

Now, all your assets have been imported into Kitsu.

![Import data copy paste data](../img/getting-started/breakdown_general_bulk_select_full.png)
:::

## Introduction to Asset State: Ready For

Most of the time, you don't need to wait for an asset's tasks to be validated to use it on a shot task.

For example, when an asset is validated at the **Concept** stage, it can be used for the **Storyboard** stage.
Then, when it's validated at the **Modeling** stage, you can use it for the **Layout** stage and so on.

That's exactly what the asset state **Ready For** is doing: it lets you know the state of an asset's tasks and compares its usability for the shot tasks.

Now that we have filled out our breakdown, we know exactly which asset is used on every shot.

First, we need to define an asset's state relative to its task status. You can modify the **Ready for** by clicking on a cell. You will see a dropdown menu with the shot task.

![Asset Status](../img/getting-started/asset_status.png)

::: tip
You can use the **automations** to do the heavy lifting.

You can set automation with the **ready for** trigger. 
:::

Now that we have changed some asset states to **Ready for**, we can see the result on the shot page.

You can notice that some white boxes are now **Green**: all the assets cast in this shot are ready for this specific task.

![Asset Status](../img/getting-started/asset_status_box.png)

If you see the white box, Kitsu will display how many assets are ready for this task.

![Asset Status](../img/getting-started/asset_status_empty.png)

 ::: tip
If you don't see any boxes, no assets are cast for this shot.
:::
 
Then, you can click on the shot's name to go to its detail page.
Then, you will see all the assets cast in this shot and their status.

![Asset Status](../img/getting-started/asset_status_detail.png)

It's the fastest way to know if you can start a shot for a specific task.
