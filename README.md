## Projects

### Find Country

1. Fetch country data when the website is loaded, and data will be loaded in an array.
2. The loaded data is looped to find and display the best matching country for user input.
3. If the match result is satisfactory, the user can press the `confirm` button to activate the results. 

    - region, subregion information are fetched from the loaded data
    - sunrise, sunset time are fetched only when the `confirm` button is pressed (when user confirms the country)
    - **sunrise, sunset time are fetched in UTC time so it needs to be converted to local time (to be completed)**

#### Reference APIS 
- Rest Countries: https://restcountries.eu/
- Sunset and sunrise times API: https://api.sunrise-sunset.org/