# Google-Search-Suggestions-react
In this project, let's build a Google Search Suggestions app by applying the concepts we have learned till now.

### Refer to the image below:

<br/>
<div style="text-align: center;">
<img src="https://assets.ccbp.in/frontend/content/react-js/google-search-suggestions-output.gif" style="max-width:50%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

### Design Files

<details>
<summary>Click to view</summary>

- [Extra Small (Size < 576px), Small (Size >= 576px)](https://assets.ccbp.in/frontend/content/react-js/login-sm-output.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px)](https://assets.ccbp.in/frontend/content/react-js/login-lg-output.png)

</details>

### Set Up Instructions

<details>
<summary>Click to view</summary>

- Download dependencies by running `npm install`
- Start up the app using `npm start`
</details>

### Completion Instructions

<details>
<summary>Functionality to be added</summary>
<br/>

The app must have the following functionalities

 - Initially, all suggestions in the **suggestionsList** should be displayed
 - When a value is provided in the search input, then display the suggestions which includes the search input irrespective of case
 - When the arrow of a suggestion is clicked, then the value of the search input should be updated with the respective suggestion clicked
 - The **GoogleSuggestions** component receives the ***suggestionsList** as a prop. It consists of a list of suggestion objects with the following properties in each suggestion object

</details>

<details>
<summary>Implementation Files</summary>
<br/>

Use these files to complete the implementation:

- src/components/GoogleSuggestions/index.jss
- src/components/GoogleSuggestions/index.css
- src/components/SuggestionItem/index.js
- src/components/SuggestionItem/index.css

</details>

### Important Note

<details>
<summary>Click to view</summary>
<br/>
**The following instructions are required for the tests to pass**

- Achieve the given layout using only Conditional Rendering
</details>

### Resources

<details>
<summary>Image Urls</summary>

<br/>

  - https://assets.ccbp.in/frontend/react-js/google-logo.png alt should be **google logo**
  - https://assets.ccbp.in/frontend/react-js/google-search-icon.png alt should be **search icon**
  - https://assets.ccbp.in/frontend/react-js/diagonal-arrow-left-up.png alt should be **arrow**

</details>

<details>
<summary>Colors</summary>


<div style="background-color: #bfbfbf ; width: 150px; padding: 10px; color: black">Hex: #bfbfbf</div>
<div style="background-color: #64748b ; width: 150px; padding: 10px; color: white">Hex: #64748b</div>
<div style="background-color: #475569; width: 150px; padding: 10px; color: white">Hex: #475569</div>

</details>

<details>
<summary>Font-families</summary>

- Roboto

</details>

> ### _Things to Keep in Mind_
>
> - All components you implement should go in the `src/components` directory.
> - Don't change the component folder names as those are the files being imported into the tests.
> - **Do not remove the pre-filled code**
> - Want to quickly review some of the concepts you’ve been learning? Take a look at the Cheat Sheets.
