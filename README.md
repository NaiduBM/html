<form class="booking-form">
  <h2>Table Booking Form</h2>
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" required>
  <label for="email">Email:</label>
  <input type="email" id="email" name="email" required>
  <label for="phone">Phone:</label>
  <input type="tel" id="phone" name="phone" required>
  <label for="date">Date:</label>
  <input type="date" id="date" name="date" required>
  <label for="time">Time:</label>
  <input type="time" id="time" name="time" required>
  <label for="guests">Number of Guests:</label>
  <input type="number" id="guests" name="guests" min="1" max="10" required>
  <label for="comments">Comments/Requests:</label>
  <textarea id="comments" name="comments" rows="5"></textarea>
  <input type="submit" value="Book Table">
</form>
