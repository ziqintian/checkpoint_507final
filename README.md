## SI 507 Final Project Checkpoint

### Project code

Here's the link to the GitHub repository to the project checkpoint [SI507 checkpoint GitHub](https://github.com/ziqintian/checkpoint_507final).

### Data sources

#### 1. Wikipedia
- List of United States cities by population
List of United States cities by population
[Wikipedia-population](https://en.wikipedia.org/wiki/List_of_United_States_cities_by_population).
Data of each city is scraped from this page to give a background information about cities. "rank" "city", "state", "population", and "land area" are shown in the table.

- Challenge score: 4

#### 2. Unsplash [Link to Unsplash photos page](https://unsplash.com/)
- The photos of each city can be accessed based on users request.

#### 3. Yelp Fushion [Link to Yelp Fushion](https://api.yelp.com/v3/businesses/search)
- I use private API to access restaurant information. "Restaurant name", "url", "transactions", "price" and "rating" are included in restaurant information shown to the users.

- Challenge score: 4

### Data Structure

- Tree structure with dictionary to add information for each restaurant
- Price Tree: the tree for restaurants in each price level.

- Structure of Data

![image of tree structure](Documentation/tree.png)

### Interaction and Presentation Plans
- Interacting with users by asking questions. Data visualization based on the answers offered by users.
- Pie chart, bar chart to visualize restaurant information.
