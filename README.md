
### Project Description

This is a Rails API project that retrieves information about superheroes and their abilities. The API enables users to handle superheroes and their abilities, and it includes two models: Hero and Power. The Hero model represents a superhero, while the Power model represents an ability that a superhero can possess. The application also includes a join table model called HeroPower, which manages the relationship between a Hero and a Power.

The HeroPower model comprises a strength attribute that accepts three possible values: Strong, Weak, and Average. The Power model requires a description attribute that must be at least 20 characters long and present.

The application provides numerous RESTful routes that allow users to view, create, update, and delete superheroes and abilities.

### Features

- Users can view a list of all heroes and their associated powers.

> `GET /heroes`

- Users can view a list of all powers.

> `GET /powers`

- Users can view details of a specific hero by id, including their name, superhero name, and powers.

> `GET /heroes/:id`

- Users can view details of a specific power, including its name and description.

> `GET /powers/:id`

- Users can create a new hero power association.

> `POST /hero_powers`

- Users can update the description of a power.

> `PATCH /powers/:id`

### Technology Used

- Ruby on Rails
- Postgres

### Setup Instructions

To run this application on your local machine, you need to have Ruby on Rails and Postgesql installed. Follow these steps:

- Open your terminal.
- Clone the repository `https://github.com/Bernardkoech/Phase-4-codechallenge-superheroes.git`
- `Bundle install`
- Run rails server using the command: `rails s`
- Use Postman to access the endpoints.

### Copyright and license information

#### Author

 Bernard Koech

#### License

This project is licensed under the MIT License - see the LICENSE.md file for details

