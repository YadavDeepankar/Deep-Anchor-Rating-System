# Deep Anchor Rating System

## Description

This web application calculates a product rating using the Deep Anchor Rating System.  The Deep Anchor Rating is designed to be more aligned with user sentiment than a traditional weighted average.  It adjusts the rating based on the distribution of positive and negative feedback.

## Features

* **Input**: Users provide the total number of ratings and the percentage distribution of star ratings (1-star to 5-star).
* **Calculation**: The tool calculates the Deep Anchor Rating.
* **Output**: The Deep Anchor Rating is displayed.
* **Validation**: The form includes input validation to ensure data accuracy.
* **Responsive Design**: The user interface is responsive, adapting to different screen sizes (using Tailwind CSS).

## How to Use

1.  Open the "index.html" file in your browser.
2.  Enter the total number of ratings.
3.  Enter the percentage of ratings for each star level (1-star to 5-star).  Ensure that the percentages add up to 100%.
4.  Click the "Calculate Ratings" button.
5.  The Deep Anchor Rating will be displayed.

## Technical Details

The Deep Anchor Rating is calculated as follows:

1.  **Weighted Average**: A standard weighted average is calculated from the star rating percentages.
2.  **Penalties**: Penalties are applied for higher percentages of 1-star, 2-star, and 3-star ratings.
3.  **Rewards**: Rewards are applied for higher percentages of 4-star and 5-star ratings.
4.  **Final Adjustment**: The penalties and rewards are added to the weighted average.
5.  **Capping**: The final rating is capped at 5 stars.

## Technologies Used

* HTML
* CSS (Tailwind CSS)
* JavaScript

## Setup (for local development)

1.  Clone this repository.
2.  Open the "index.html" file in your browser.

## Contributing

Contributions are welcome! Please submit pull requests with any enhancements or bug fixes.
```
