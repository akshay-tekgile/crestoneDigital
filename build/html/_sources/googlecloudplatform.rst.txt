Google Cloud Platform
=====================

Google Cloud Platform is a suite of public cloud computing services offered by Google. The platform includes a range of hosted services for compute, storage and application development that run on Google hardware. Google Cloud Platform services can be accessed by software developers, cloud administrators and other enterprise IT professionals over the public internet or through a dedicated network connection.

`Google Cloud website <https://cloud.google.com//>`_

`Google Cloud Docs <https://cloud.google.com/docs/>`_

Services Offered by GCP
	* Computing and hosting
	* Storage
	* Networking
	* Big data
	* Machine learning

To use any of the GCP service we have to enable billing. For free trial also we have to enable billing. When we start a free trial by giving our card details google will give $300 in credit and 12 months to explore Google Cloud Platform.

**Start GCP free trail**

* Login to Gmail account
* Go to https://cloud.google.com/ and click "TRY IT FREE"

.. figure:: _static/screenshots/gcp/startFreeTrial.PNG
    :align: center

* Choose Country and accept agreements

.. figure:: _static/screenshots/gcp/acceptAgreements.PNG
    :align: center

* Now a webpage with payment details and customer detail will appear
	Enter details in the form
	- Select type of account we need, "Business" or "Individual"
	- Enter Tax details and related details if applicable
	- Add name and address
	- Enter card Payment details
	After entering all details click "Start my free trail"
	
.. figure:: _static/screenshots/gcp/form1.PNG
    :align: center

.. figure:: _static/screenshots/gcp/form2.PNG
    :align: center
	

**Google BigQuery**


Google BigQuery docs: https://cloud.google.com/bigquery/quickstart-web-ui

**Before you begin**

1. Select or create a GCP project

	Go to - https://console.cloud.google.com/cloud-resource-manager
	
.. figure:: _static/screenshots/gcp/createProject.PNG
    :align: center

Click on create project, Now a page will open
	
.. figure:: _static/screenshots/gcp/projectName.PNG
    :align: center

Enter project name and give location which the project belongs.
	
	Now a project is created
	
	
2. Enable billing for your project.
	Make sure that billing is enabled for your project.
    
	Billing docs: https://support.google.com/cloud/answer/6293499#enable-billing

	If you are a billing administrator on only one billing account, new projects you create are automatically linked to your existing billing account.
	
	To change the billing account:

	* Go to the Google Cloud Platform Console (https://console.cloud.google.com/home/dashboard).
	* Open the console left side menu and select Billing.
	* If you have more than one billing account, you'll be prompted to select Go to linked billing account to manage the current project's billing.
	* Under Projects linked to this billing account, locate the name of the project that you want to change billing for, and then click the menu next to it.
	* Select Change billing account, then choose the desired destination billing account.
	* Click Set account.
	
	Enable billing for an existing project
	If you have a project that you temporarily disabled billing for, you can re-enable billing:

	* Go to the Google Cloud Platform Console.
	* From the projects list, select the project to re-enable billing for.
	* Open the console left side menu and select Billing .
	* Click Link a billing account.
	* Click Set account.
	
.. figure:: _static/screenshots/gcp/dashboard.PNG
    :align: center

.. figure:: _static/screenshots/gcp/dashboardMenu.PNG
    :align: center
	
	
3. Enable the Google BigQuery API.
	BigQuery is automatically enabled in new projects. To activate BigQuery in a pre-existing project, go to Enable the BigQuery API.

	Goto - https://console.cloud.google.com/flows/enableapi?apiid=bigquery-json.googleapis.com

.. figure:: _static/screenshots/gcp/enableApi.PNG
    :align: center

.. figure:: _static/screenshots/gcp/enableApiSelectProject.PNG
    :align: center
	
Now Click "Click Enable Api"
	
.. figure:: _static/screenshots/gcp/apiEnabled.PNG
    :align: center

4. Set up authentication with a service account.
	Set up authentication with a service account so you can access the API from your local workstation.
	docs: https://cloud.google.com/docs/authentication/getting-started

	Creating a service account

    a. Go to the Create service account key page in the GCP Console.
        https://console.cloud.google.com/apis/credentials/serviceaccountkey
    b. From the Service account drop-down list, select New service account.
    c. Enter a name into the Service account name field.
    d. From the Role drop-down list, select Project > Owner.
    e. Click Create. A JSON file that contains your key downloads to your computer.


.. figure:: _static/screenshots/gcp/serviceAccount.PNG
    :align: center

.. figure:: _static/screenshots/gcp/serviceAccountForm.PNG
    :align: center
