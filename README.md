# Sales Summary Test

## Summary
This static web app fetches data from a `data.csv` file, calculates the total of the sales column, and displays the result in the `#total-sales` element. The title of the page is set to "Sales Summary test" and Bootstrap 5 is loaded from jsdelivr. 

## Setup
To deploy this web app on GitHub Pages:
1. Fork this repository.
2. Upload your `data.csv` file containing the sales data.
3. Go to the repository's settings and choose the branch where your app lives.
4. Go to your settings and set GitHub Pages source to the branch where your static site will be served.

## Usage
Access the page via the GitHub Pages link. You can pass query parameters to filter the sales data by certain criteria.

Example:
```
https://your-github-username.github.io/sales-summary?category=shoes
```

## Code Explanation
The app consists of an HTML file that includes a script to fetch the `data.csv` file and perform the necessary calculations. The fetched data is used to calculate the total sales, which is then displayed on the page.

## License
This project is licensed under the MIT License.