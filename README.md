# Booking-application
This simple booking form is designed using Bootstrap to facilitate hotel reservations. It calculates prices based on the number of adults and the duration of the stay.

# Overview
The hotel booking form provides a user-friendly interface to input booking details and calculate the total cost of the stay. It allows users to specify the number of adults and the duration of the stay to generate the total price dynamically.

# Features
*   **Input Fields:** Capture the number of adults and the duration of the stay.
*   **Price Calculation:** Dynamically calculates the total cost based on user inputs.

# Technologies Used
*   **Bootstrap:** Frontend framework for responsive and mobile-first web development.

# Usage
1.  Open the booking form in your web browser.
2.  Enter the number of adults staying.
3.  Specify the duration of the stay in days.
4.  The total cost will be automatically calculated based on the provided information.

# Code Sample
Here's a snippet demonstrating the form structure using Bootstrap classes:
```html
<form>
  <div class="mb-3">
    <label for="adults" class="form-label">Number of Adults:</label>
    <input type="number" class="form-control" id="adults" name="adults" min="1" required>
  </div>
  <div class="mb-3">
    <label for="duration" class="form-label">Duration of Stay (in days):</label>
    <input type="number" class="form-control" id="duration" name="duration" min="1" required>
  </div>
  <div class="mb-3">
    <p>Total Price: <span id="totalPrice">$0</span></p>
  </div>
  <button type="submit" class="btn btn-primary">Book Now</button>
</form>
```
This HTML snippet showcases the structure of the form using Bootstrap's form-control and btn classes for input fields and buttons, respectively. JavaScript will be required to handle the calculation of the total price based on user inputs.

# Contributing
Contributions, feedback, and improvements to enhance the functionality or design of this form are welcome. Feel free to open issues or pull requests to contribute.
