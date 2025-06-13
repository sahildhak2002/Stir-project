# Stir-project
✅ Project Description:
The Stir prebooking platform allows users to pre-book event tickets for upcoming shows and experiences. My role was to thoroughly test the website’s user interface, functionality, responsiveness, and security features to ensure a smooth user journey from login to payment.

🧪 Testing Scope and Responsibilities:
UI Testing:

Verified layout consistency across devices (laptops, mobiles).

Identified alignment issues in the footer (Terms & Conditions, Privacy Policy).

Checked responsiveness in different screen sizes and browsers.

Confirmed visibility and behavior of social media icons.

Functional Testing:

Tested form field behavior with valid/invalid inputs.

Verified correct validation messages for mobile number, email, etc.

Ensured the form submitted only when all required fields were completed.

Checked behavior of login with 10-digit mobile number and handling of edge cases.

Verified coupon code validation and error message for incorrect inputs.

Confirmed restriction in profile editing (user can't change name).

Checked if users must select at least one preferred cinema before making payment.

Security Testing:

Ensured no sensitive data is passed via URL parameters.

Verified CSRF token presence in forms.

Tested for input sanitization by entering HTML/JS in form fields to prevent XSS attacks.

Cross-Browser Testing:

Website tested and verified on Chrome, Firefox, Safari, Opera, and Microsoft Edge.

🐞 Bug Reporting Highlights:
Login failed despite valid mobile number input.

Mailto links (support@createstir.com and info@barsaatifilms.com) not working/clickable.

Incomplete alignment in footer.

Non-editable profile section.

📊 Deliverables:
Test Case Sheet with 20 scenarios (UI, Functional, and Security).

Bug Report with severity levels and reproduction steps.

Screenshots for failed scenarios.

🎯 Outcome:
This project helped identify multiple UI/UX issues, functional bugs, and improve validation flows. It also showcased the importance of thorough testing in a real-time production-like environment.
