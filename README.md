# BuscaCep

This is a simple web application that allows users to search for addresses based on Brazilian ZIP codes (CEP).  It utilizes the ViaCEP web service to retrieve address information.

# Features
- Form Input: Provides fields for user information (Name, Phone, Email) and address details (CEP, Street, Neighborhood, Number, City, State).

- CEP Lookup: When a user enters a CEP and leaves the CEP input field, the application automatically queries the ViaCEP service.

- Address Auto-fill: If a valid CEP is provided, the Street, Neighborhood, City, and State fields are automatically populated with the retrieved address data.

- Error Handling: Displays an alert message if the CEP is invalid or not found in the ViaCEP database.

- Clear Form Functionality: Clears the address fields if the CEP is invalid or empty.

- Dependencies: jQuery:  Included from a CDN.

# Technologies Used
- HTML: For the structure of the web page and form.

- JavaScript: For handling user interactions, making AJAX requests to the ViaCEP service, and manipulating the DOM.

- jQuery: A JavaScript library used to simplify DOM manipulation and AJAX requests.

- ViaCEP API: A web service (viacep.com.br) used to retrieve address information from a CEP.

# How to Use
Open the HTML file: Open busca-cep.html in your web browser.

Enter User Information: Fill in the "Name", "Phone", and "Email" fields. The "Phone" field is required and has a placeholder for the format.

Enter the CEP: Type the Brazilian ZIP code (CEP) in the "Cep" field.

Trigger the Lookup: Click outside the "Cep" field (or press Tab) to trigger the address lookup.

View Results:

If the CEP is valid, the address fields (Street, Neighborhood, City, State) will be automatically filled.

If the CEP is invalid or not found, an alert message will be displayed, and the address fields will be cleared.

Fill in Additional Details: Complete the "Number" field.

Submit (Optional): The "Enviar" button does not currently have any functionality in the provided code.  It would need to be linked to a server-side script to process the form data.
  
