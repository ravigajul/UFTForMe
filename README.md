# UFTForMe
# Keyword View/Expert View
# Parameterization --datatable(global/local), environment variables/xmls
# Datadriver--One stop point to view all the values that can be parameterized 
# Checkpoints
	1. PageCheckpoint--total# links and images on webpage,time taken to load the page, html source tags and broken links
	2. Bitmap Checkpoint --check bitmap of image . Fails mostly during run time due to resolution issues
	3. Image Checkpoint --will check properties of web image instead of the actual bitmaps
	4. Text/TextArea checkpoint --compare expected text. You can configure the text before and after for accuracy of the check
	5. Accessibility check point --verifies if a page is confirming to w3c standards (word wide web consortium)
	6. Database checkpoint--query results to be compared with runtime results
	7. Table Checkpoint -check the contents of a cell or a grid of a table in web page
	8. Xml checkpoints -- to verify xml data/schema
	9. Standard CheckPoint --can work as anyother check point if inserted like auto convert to image if pointed to image.
	
# Output Values - to store the values at run time
	1. Standard output value --to output value of a property
	2. Text/TextArea output value
	3. Database output value
	4. Xml output value

# Reporter.Report evenstatus,reportStepName, ReportDetails[,image file path]
	1. Eventstatus-micpass/micfail/micdone/micwarning(0/1/2/3)

# Object identification
	1. Mandatory Properties 
	2. Assistive properties
# Smart identification -slows down script execution by unchecking enable smart identification
	1. Base filter properties
	2. Optional filter properties

# Ordinal Identifiers-if multiple objects with same properties exist we can access a particular object by setting its index value as 0 or 1 etc
	1. Index based --0,1,2,3
	2. Location based----00,01,02, etc
	3. Creation time --browser open time  first browser 0 and succeeding browers 1,2,3 and so on.

# Local Object Repository
	1. Default repository
	2. Specific to actions
	
# Operations performed in repository
	1. Highlight in application
	2. Add to repository
	3. Locate in the repository
	4. Update from application
# Shared Object Repository (.tsr)
	1. Exported local object repository can be associated to multiple actions for common objects to decrease the size of object repository and increase performance
	2. Preferable when objects are dynamic and needs lot of maintenance.
	3. Cannot edit shared object repositories directly
	4. Resources-->repository manager -->file---enable editing to edit the shared object repository

# Object repository manager
	1.  Tools --object repository comparison tool
	2. Edit shared object respository--File--enable editing
	3. Object Repository merge tool

# Recording Modes
	1. Context Sensitive --Normal recording mode
	2. Analog Recording --captures the mouse movements.
		a. Relative to a screen/Relative to the following window
		b. Can switch to this mode only while recording--record--analog recording
	3. Low Level ---captures the coordinates of a click

# Function Libraries(.qfl)
	1. Create function library 
	2. associate a function library
	3. File-settings--resources

# Transactions
	1. Measure how long it takes to run a section of a test
	2. Start and end transaction statements
	3. Insert--start transaction / end transaction

# Recovery Scenario
	1. If two flight windows are visible qtp confuses, one window needs to be closed and can be handled by recovery scenario
	2. Resources--recovery scenario manager
	3. Triggering event
	4. Recovery operation
	5. Post recovery
	6. Name 
	7. Finish
	Only for predictable events which are more frequent and if that cannot be handled dynamicaly
	
# On error resume next --to continue with next step when error occurs
# On error goto 0 to nullify the above action and continue showing errors


