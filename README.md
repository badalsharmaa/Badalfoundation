
# Watch Live Preview:👇
http://badalfoundation.great-site.net/

# Badalfoundation

![Web capture_22-6-2023_19553_badalfoundation great-site net](https://github.com/badalsharmaa/Badalfoundation/assets/71165326/91d4b939-971a-46c5-b2bc-e7691cbb051e)


This is a website that allows users to make donations to various causes and charities. The website is created using HTML and CSS, and it integrates a payment gateway to process the transactions.

The website consists of the following pages:

- Home: This is the landing page that displays the mission and vision of the website, as well as some featured causes and testimonials from donors and beneficiaries.
- Service: This is the page that lists all the available causes and charities that users can donate to. Each cause has a brief description, a progress bar, and a donate button.
- Donate: This is the page that shows the details of the selected cause and the amount to donate. Users can enter their name, email, and payment information, and confirm their donation.
- Thank You: This is the page that confirms the successful donation and thanks the user for their generosity. It also provides a receipt and a link to share the donation on social media.

The website uses a payment gateway API to handle the payment processing. The API requires the following parameters:

- amount: The amount of money to donate in cents.
- currency: The currency code of the donation (e.g. USD, EUR, INR).
- source: The payment method of the user (e.g. card, bank transfer, PayPal).
- description: A brief description of the donation (e.g. Donation for Cause X).

The API returns a response with the following fields:

- id: A unique identifier for the transaction.
- status: The status of the transaction (e.g. succeeded, failed, pending).
- message: A message explaining the status or any errors.

The website uses JavaScript to validate the user input, send the request to the API, and display the response on the thank you page. It also uses CSS to style the layout and appearance of the website.
