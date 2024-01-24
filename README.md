"# Sales-Dashboard"

Brief Description
	This project is aimed at developing a Power BI Dashboard for generating insights about the revenue generated.
	The dataset used for this project is in the Database Folder where the data is stored in 4 different Excel Sheets.

Dashboard Requirements
	Homepage
		Card Visuals representing the total revenue, count of orders, and the value for ATP (Average Ticket Price)
		A button navigating to the details of data
	The main sales dashboard
		Card Visuals representing the total revenue, count of orders, and the value for ATP (Average Ticket Price)
		Revenue and Budget by Year and Quarter
		Revenue, Orders, ATP filtered by supervisor
		Revenued by ProductGroup
		Revenue by Channel
		Orders by ProductCategory
	Tooltips
		Enabled in two visuals which are "Revenue and Budget by Year and Quarter" and Revenued by ProductGroup

Installation / Usage
	Install Power BI Desktop from Microsoft Store
	Download data files from link given in Introduction
	Clone/download this repository to your local machine
	Open Dashboard report file (Sales Dashboard.pbix) in Power BI Desktop, to access the dashboard's interactivity

Technologies
	DAX Formulas have been used to create measure which are stored in a separate table named by "Measure" and Date Table has been created.
	Before Loading Data into PowerBI, data has been transformed in Power Query Editor.
	Functions such as Merge Query, Extract before delimiter have been used.

