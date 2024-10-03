# alma-analytics-datatables
Client-side JavaScript code for embedding Alma Analytics reports in webpages using the Alma Analytics API and DataTables, a Javascript HTML table enhancing library.

## Instructions

### 1. Alma Analytics and Analytics API Setup
- Save Alma Analytics report to a shared folder (preferably your institution shared folder).

- Copy the path of the report, which you can find after path= in the URL for the report

- Create an Analytics API key in the Developer Network. Make sure your account is affiliated with your campus.

- Test the API call: https://api-na.hosted.exlibrisgroup.com/almaws/v1/analytics/reports?apikey={YOUR_KEY}&path={PATH_PARAMETER}

### 2. Link to DataTable JS and CSS files
Copy the links from the <b>alma-analytics-datatables-dependencies.txt</b> file and paste them into the head tags on your page.

In LibGuides, you can copy and paste the links into the "Guide Custom JS/CSS" on the guide edit page to apply them to just that guide, or you can add them to all guide pages by placing them in the Custom JS/CSS code within the Look & Feel section (admins required).

### 3. Copy and Paste the HTML/JS code
Copy the code from the <b>alma-analytics-datatables.txt</b> file and paste in into your webpage.

In LibGuides, you can copy and paste the code into a Rich Text / HTML component on the guide page (make sure to be in the HTML/Source editor), or copy and paste it into a new widget (Content > Assets > +Add Content Item > Media/Widget) that can be added to any guide page.

### 4. Update variables in code for your institution
Update the apiKey, path, primoBaseURL, and primoViewID variables with values specific to your specific Alma Analytics report url and institution's alma instance.

See "// API URL and parameters" and "// Primo search URL variables" sections of code.

### 5. Customize DataTable options (optional)
DataTable offers many options that can be passed to the DataTable constructor. See the "// Convert HTML table to DataTable" section of the code.

View additional DataTable options at https://datatables.net/reference/option/
