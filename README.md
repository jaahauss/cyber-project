NOTE: This project has been made for Cyber Security Base Project I -course. It has intentional security flaws. Previous project by the same creator has been used as the base, but has been modified to meet the requirements of this course.

# Book Club -application

Using the application, users can comment on read books and suggest new books to read.

## Installation guide
Clone this repository to your own computer and go to the root file. Create `.env`-document and define its contents as follows:

`DATABASE_URL=<local-address-of-database>`

`SECRET_KEY=<a-secret-key>`

Next activate virtual environment and install dependencies.
If you are using Linux or Mac, use commands:

`python3 -m venv venv`

`source venv/bin/activate`

`pip install -r ./requirements.txt`

If you are using Windows, use commands:

`py -m venv .venv`

`.venv\Scripts\activate`

`pip install -r ./requirements.txt`

Finally define the schema for the database:

`psql < schema.sql`

Now you can run the application:

`flask run`



