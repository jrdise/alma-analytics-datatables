# alma-analytics-datatables
Client-side JavaScript code for embedding Alma Analytics reports in webpages.

## Instructions

### 1. Link to DataTable JS and CSS files
Copy the links from the alma-analytics-datatables-dependencies txt file with the <head> section of your page.

In LibGuides, you can copy and paste the links into the "Guide Custom JS/CSS" on the guide edit page to apply them to just that guide, or you can add them to all guide pages by placing them in the Custom JS/CSS code within the Look & Feel section (admins required).

### 2. Copy and Paste the HTML/JS code
Copy the code from the alma-analytics-datatables txt file and paste in into your webpage.

In LibGuides, you can copy and paste the code into a Rich Text / HTML component on the guide page (make sure to be in the HTML/Source editor), or copy and paste it into a new widget (Content > Assets > +Add Content Item > Media/Widget) that can be added to any guide page.

### 3. Update variables in code for your institution
Update the apiKey, path, primoBaseURL, and primoViewID variables with values specific to your specific Alma Analytics report url and institution's alma instance.

See "// API URL and parameters" and "// Primo search URL variables" sections of code.

### 4. Customize DataTable options (optional)
DataTable offers many options that can be passed to the DataTable constructor. See the "// Convert HTML table to DataTable" section of the code.

View additional DataTable options at https://datatables.net/reference/option/
