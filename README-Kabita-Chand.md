# Student Name: Kabita Chand

## 1. My Assigned Work
I was responsible for implementing alerts and modals for the application.
I added a Bootstrap alert component to the Add New Task page (newtasks.html) to display an error message when user input is incorrect.
I also created a delete confirmation modal on the homepage (index.html) to simulate task deletion.

## 2. Bootstrap Implementation
I used standard Bootstrap components as planned in Table 1.
Components Used:
Alerts: Used .alert and .alert-danger to display error messages for incorrect form input
Modals: Used Bootstrap modal structure (.modal, .modal-dialog, .modal-content) for delete confirmation pop-up
Buttons: Used .btn, .btn-danger, and .btn-secondary for actions inside the modal

Yes, I followed the component mapping from Table 1 by using Bootstrap Alerts and Modals as specified.

## 3. Technical Challenges & Solutions
One challenge was understanding where to place the alert and modal so they matched the correct screens without interfering with other team members’ work.

Another challenge was ensuring the modal worked properly. I resolved this by including the Bootstrap JavaScript bundle and using the correct data attributes (data-bs-toggle, data-bs-target) to trigger the modal.

I also considered form validation behavior from Table 4. While full validation logic is not implemented yet, I used a hidden alert (d-none) to represent how validation feedback would appear.

## 4. AI / LLM Usage
*Did you use an AI tool to help write or debug your code?*
Yes, I used AI to help write and understand the code.

* **What I asked the AI:** 
- How to implement Bootstrap alerts for incorrect form input
- How to create a delete confirmation modal using Bootstrap
- Where to place alerts and modals within existing HTML files

* **How it helped & What I learned:** 
I learned how Bootstrap provides ready-to-use components like alerts and modals that only require specific class names and structure. I also learned that modals depend on Bootstrap’s JavaScript to function and require proper attributes to trigger them. Additionally, I understood how to integrate my work into existing files without affecting other components.

## 5. Live Site Link
*Provide the GitHub Pages link to the specific page(s) you built.*
* **Live URL:** [Insert Link Here]