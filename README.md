# NUS-SDS-Datathon-Champion

## Column Header Descriptions

- `AccountID`: A distinctive label or number assigned to a specific account within a system or organisation.
- `Company`: Description of the client's race.
- `SIC Code`: Standard Industrial Classification (SIC) code is a numerical system used to classify and categorise industries based on their primary economic activities. 
- `Industry`: Specific sector of economic activity
- `8-Digit SIC Code`: A numerical code system used to classify and categorise industries based on their primary business activities. 
- `8-Digit SIC Description`: Description of the 8-digit SIC code.
- `Year Found`: Year in which an entity, such as a company or organisation, was founded or established.
- `Entity Type`: The legal structure or form that an organisation or business entity takes.
- `Parent Company`: A corporation or another form of business entity that owns or controls another company 
- `Parent Country`: The country of origin or the home country of a multinational corporation or a company that has subsidiaries or operations in - multiple countries.
- `Ownership Type`: The classification or categorization of the legal structure that dictates how a business entity is owned, managed, and organised.
- `Company Description`: A concise and informative overview that provides key details about a business entity.
- `Square Footage`: A unit of measure used to quantify the total area or size of a two-dimensional space. 
- `Company Status (Active/Inactive)`: The current standing or operational condition of a business entity, indicating whether it is currently active and conducting business or inactive
- `Employees (Single Site)`: The total number of individuals employed by a company at a specific location or site.
- `Employees (Domestic Ultimate Total)`: The total number of individuals employed by a company across all its domestic or home-country operations. 
- `Employees (Global Ultimate Total)`: The total number of individuals employed by a company across all its global operations.
- `Sales (Domestic Ultimate Total USD)`: The total sales revenue generated by a company within its domestic or home country operations, measured in U.S. dollars. 
- `Sales (Global Ultimate Total USD)`: The total sales revenue generated by a company on a global scale, measured in U.S. dollars. 
- `Import/Export Status`: The classification of a company based on its involvement in international trade, specifically with regard to importing and exporting goods.
- `Fiscal Year End`: The conclusion of a company's accounting and financial reporting period.
- `Global Ultimate Company`: The top-level entity or parent company within a corporate structure that has a presence and operations on a global scale. 
- `Global Ultimate`: A country that holds a central or pivotal role within a multinational corporate structure as the ultimate or top-level entity at a global scale.
- `Domestic Ultimate Company`: The highest-level entity within a corporate structure that is based in the country where the business primarily operates.
- `Is Domestic Ultimate`: A categorical attribute or indicator that signifies whether a particular entity or company is the ultimate or highest-level company within a corporate structure based in its home country. 
- `Is Global Ultimate`: A categorical attribute or indicator that signifies whether a particular entity or company holds the status of being the ultimate or highest-level company within a corporate structure on a global scale.

## Submission Instructions

1. Rename the submission notebook as "NUS_DATATHON_CHAMPION_\<TEAM NAME\>.ipynb". For example, if your team name is "NUS 1", your submission notebook should be named as "NUS_DATATHON_CHAMPION_NUS 1.ipynb". \
The notebook already contains a template function, named `testing_hidden_data`, to take in the test data and output the predictions. You are to fill in the function with your model and any preprocessing function that you may have. \
Note: Each team should only submit one notebook and the notebook should be in the `master` branch.

2. You can save your model and upload it in the GitHub repository provided that it does not exceed the file size limit on GitHub (see Section 3 on instructions for large models). If you saved your model, you are to provide a script the load the model. Please name the loading function as `load_model`. \
If the model is not saved, we will assume that the model is trained using the training function and the output of the training model is a model that can be is trained using the template function, `testing_hidden_data`, provided in the notebook. Please name the training function as `train_model`.

3. If your model is too large to be uploaded to GitHub, you can upload it to Google Drive and share the link with us. Please ensure that the link is accessible by anyone with the link. Please provide a `LOAD_MODEL_INSTRUCTIONS.md` file in the GitHub repository to explain how to load the model. Note that you are strongly discouraged to use such large models. 