# Chef Generic Webhook
Whether you have five or five thousand servers, Chef lets you manage them all by turning infrastructure into code. Infrastructure described as code is flexible, versionable, human-readable, and testable. Check out the sweet video [here](media/mysweetvideo.mov). 

# Pre-Requisites
* Chef Server v 3.x or higher.  The Generic Webhook is new functionality.
* Generic Webhook configured.  
* Jenkins Communication Plan (see files) imported into xMatters or created in xMatters.
* xMatters account - If you don't have one, [get one](https://www.xmatters.com)!
* xMatters account - If you don't have one, [get one](https://www.xmatters.com)!

# Files
* [FileA.js](FileA.js) - The javascript file to be pasted into a Shared Library. It generally does xyz. 
* [MySweetCommPlan.zip](MySweetCommPlan.zip) - The comm plan (if needed) that has all the coold scripts and email format and such. 

# Installation
Details of the installation go here. 

## Application ABC set up
Specific steps go here

## xMatters set up
1. Create a new Shared Library or (In|Out)bound integration
2. Add this code here:
   ```
   var items = [];
   items.push( { "stuff": "value"} );
   console.log( 'Do stuff' );
   ```
   
# Testing
Be specific. What should happen to make sure this code works? What would a user expect to see?

# Troubleshooting
Optional section for how to troubleshoot. Especially anything in the source application that an xMatters developer might not know about. 