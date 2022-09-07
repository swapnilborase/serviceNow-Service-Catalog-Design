# serviceNow-Service-Catalog-Design
Service Request Management system provides an intuitive interface with predefined work flows for IT requests to be reliably submitted, routed, approved, monitored and delivered with minimum human interference. Every individuals developed complex Service Catalog using Custom Table, including Catalog Clients scripts/Catalog UI policies, and complex Workflows.

# Roles / Responsibilities
Hostel Admission Process - I created a ServiceNow Catalog Service for taking admission in college hostels in different areas & also for different gender along multiple types of bed sharing & room types. Students are required to fill out the all the mandatory field. Students are required to entire their personal, parent, educational, hostel details in order to take the admission. The catalog service is has list about specific hostel that they chose was populated in read-only fields with Catalog Client Script. The Form dynamically changed when different values are selected using UI Policy & Action. when the Boys Hostel selected all the Girls Hostel field is not visible & vice-versa. In my workflow there are 2 different approval users based on the information that was entered into the form. At the end of the workflow, I added scripts to update my custom table to get all the entered information by the students.

* Worked on ServiceNow developer to design a catalog form, workflow, and scripts.
* Created Workflow to provide a drag-and-drop interface for automating multi-step processes across the platform.
* Created 2 custom tables for list of boys hostel and girls hostel
* Wrote Field validation on catalog client scripts using JavaScript.
* Created ITIL group and ITIL users to test the flow project.
* Created a catalog Item list for users to order an item.
* Used Request Item workflow with the workflow that is created for user approval and handles tasks.
* Combined Catalog Client Script to store and pass information to a custom table.
