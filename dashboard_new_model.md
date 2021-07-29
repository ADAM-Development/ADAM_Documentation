<h1>Making a New Model from Scratch</h1>

<p>
    In this tutorial, we will use the data files located at 
<a href="https://github.com/ADAM-Development/ADAM_Documentation/tree/main/Downloadable_content/example_custom_model">this link</a> to demonstrate how to make your own model from scratch. 
</p>

<h2>Creating a new Model</h2>

First, navigate to your model list by selecting **Manage Models** on the dashboard homepage. Next select **New Model**. 

<img src="Pictures\Dashboard_tutorials\new_model\model_list.png">

<p>
    You will be prompted to enter the model name and description. The description of the model should provide a brief overview of the purpose of the model or what problem it is attempting to solve. 
</p>

<img src="Pictures\Dashboard_tutorials\new_model\enter_info.png">

After selecting **Yes**, the model will be added to your model list.

<img src="Pictures\Dashboard_tutorials\new_model\new_model.png">

<h2>Entering information in the Model</h2>

<p>
    Clicking on the model will bring you into a progress bar screen with a row of buttons labeled from steps 1 through 6 and another row of buttons with various options. 
</p>

<img src="Pictures\Dashboard_tutorials\new_model\progress_bar.png">

<p>
    The first row of buttons is where you will go to enter information about the model. The second row of buttons gives you options for what you can do with the model. It is best to use these options once the model data is complete. 
</p>

<p>
    For a custom model, you will need to input your own data. You can do this by creating your own supply, demand, technology site, and technology candidate files, or you can use some other method of uploading data. Please review the 
<a href="input_files.html">Input Files Tutorial</a> for information on each file type, or the <a href="dashboard_input_data.html">Adding Data to a Model Tutorial</a> for various methods of adding data. 
</p>

<h2>Step 1 - Model Type</h2>

Begin inputting data by selecting **Step 1**. You will be taken to a page where you can define the model type and the time basis. 

<img src="Pictures\Dashboard_tutorials\new_model\step1.png">

The default model type is a **Supply Chain Design** type model, and the default time basis is **Year**. A design-type model is used when your data contains technology candidates, otherwise a management-type model is used.

The time basis is up to you. Just keep in mind that you will need to have your data in the units of your selected time basis; additionally, the results will be in the selected time units.

In this example, we will leave it as the default settings. Clicking **Confirm** will bring you to the next step.

<h2>Step 2 - Suppy Data</h2>

<p>
    Step 2 is where you can add supply data to the model. Use the first three options to upload data. For a review on how each option works, please refer to the 
<a href="/ADAM_Documentation/dashboard_input_data.html">Adding Data to a Model Tutorial</a>.
</p>

<img src="Pictures\Dashboard_tutorials\new_model\step2.png">

<p>
    After uploading the example supply file, the model should look like this: 
</p>

<img src="Pictures\Dashboard_tutorials\new_model\step2_data.png">

Then click **Next** to save the supply data and proceed to the next step. 

<h2>Step 3 - Demand Data</h2>

<p>
    Similar to the supply data, we will upload a CSV file containing the demand data in step 3. After uploading the example, the model should look like this:
</p>

<img src="Pictures\Dashboard_tutorials\new_model\step4.png">

Then click **Next** to save the demand data and proceed to the next step.

<h2>Step 4 - Technology Data</h2>

In step 3, we will upload our technology data using the same method as before. When uploading the technology data, make sure to toggle the **Type** to match the file. 

<img src="Pictures\Dashboard_tutorials\new_model\step3_type.png">

ADAM only allows you to upload one file at a time so first select **Technology Site Data** as the type and upload the example technology site file, then select **Upload Data** again and repeat the process with the technology candidate file.

<p>
    If you uploaded the example files correctly, the model should look like this: 
</p>

<img src="Pictures\Dashboard_tutorials\new_model\step3.png">

Then, click **Next** to save the technology data and proceed to the next step. 


<h2>Step 5 - Transport Data</h2>

Step 5 is adding the transportation data to the model. For models with many nodes (over 200), you should select the **Skip** option. Otherwise, select **Generate Transportation Routes**. This will generate every possible pathway for each product. Make sure to select all the data layers before saving. 

<p>
    The digestate pathways overlap the bio-electricity pathways so you may have to toggle some of the data layers in order to view the bio-electricity pathways. 
</p>

<img src="Pictures\Dashboard_tutorials\new_model\step5.png">

The **Read Transportation Data** option is used when you have previously generated transportation routes and have saved them. This option is slightly faster than generating new transportation routes.

After generating transportation routes, you can now use the distance filter option. This is an optional step that allows you to limit the transportation pathways to those within a certain distance range. Clicking **Fit** will apply the selected distance filter, and clicking **Recover all Routes** will remove the distance filter.

<img src="Pictures\Dashboard_tutorials\new_model\dist_filter.png">

After applying the transportation routes, click **Save Changes** in order to save.

<h2>Step 6 - Run Model</h2> 

<p>
    Now that all of the input data is uploaded, the model is now complete. The final step is running the model. 
</p>

<img src="Pictures\Dashboard_tutorials\new_model\step6.png">

Once the status is **Completed**, you may view the results. For more information on how to interpert the results, please refer to the
<a href="/ADAM_Documentation/dashboard_results.html">Interpreting the Results Tutorial</a>.

<img src="Pictures\Dashboard_tutorials\new_model\completed.png">

<h2>The Other Options</h2>

Besides the **View Model Results** option, there are also several other options that you can select. Below, there is a short description of the option and their functions. 

| Option | Description |
| ------------- | ------------- |
| **Clear Model Data** | clears all data in the model |
| **Delete Model** | deletes the model from the model list | 
| **Load Model** | loads data from another model into this model |
| **Download Model Data** | allows you to download all of the input data (supply, technology, demand) in the form of csv files | 
| **Get P-Graph** | allows you to view the process graph for this system |

<br>
<br>

<a href="/ADAM_Documentation/dashboard.html">Back to Dashboard Tutorials</a>