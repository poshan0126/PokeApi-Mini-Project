# Pokémon Team Builder

Welcome to the Pokémon Team Builder web application! This application allows users to create and manage their Pokémon teams with ease. Users can search for Pokémon by name using an autocomplete feature, add them to their team, and view detailed information about each Pokémon.

## Features

- **Search for Pokémon**: Utilize the autocomplete search feature to quickly find Pokémon by name.
- **Add Pokémon to Team**: Add selected Pokémon to your team list.
- **View Pokémon Details**: Access detailed information about each Pokémon, including an image and a link to more details.
- **Pokémon Generations**: Explore Pokémon by their respective generations.
- **Pokémon Types**: Discover Pokémon based on their types.

### Autocomplete Feature
The autocomplete feature allows users to quickly find Pokémon by name as they type in the search input. This feature is implemented using the Bootstrap Typeahead plugin and the PokeAPI.

#### How It Works
**Fetch Pokémon Data**: On page load, the application fetches a list of Pokémon names from the PokeAPI.
**Initialize Typeahead**: The fetched Pokémon names are used to initialize the Bootstrap Typeahead plugin on the search input field.
**User Input**: As the user types in the search input field, the Typeahead plugin suggests Pokémon names that match the input.

## Technologies Used
- **HTML5**: Structure the web page content.
- **CSS3**: Style the web page.
- **JavaScript**: Handle dynamic content and user interactions.
- **Bootstrap 4.5.2**: Provide responsive design and prebuilt UI components.
- **PokeAPI**: Fetch Pokémon data from an external API.

## Getting Started

Follow these instructions to set up and run the Pokémon Team Builder on your local machine.

### Prerequisites

- Web browser (Google Chrome, Mozilla Firefox, etc.)
- Internet connection to fetch Pokémon data from PokeAPI

### Installation

1. Clone the repository:
   ```bash
   git clone (https://github.com/poshan0126/PokeApi-Mini-Project)

2. Navigate to the project directory:
    ```bash
        cd pokemon-team-builder
3. Open the index.html file in your preferred web browser:
    ```bash
        open index.html

## Acknowledgements
- PokeAPI for providing the Pokémon data.
- Bootstrap for the responsive design framework.
- Bootstrap Typeahead for the autocomplete plugin.
- LLMS for format correction and some error solving








