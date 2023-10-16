
# English-to-SQL-Query

This Python project is designed to convert English sentences into SQL queries. It leverages libraries such as dotenv, langchain, and HuggingFaceHub to facilitate this conversion.

## Libraries Used

- dotenv
- langchain
- HuggingFaceHub

## Features

- **English to SQL Conversion**: The script converts English sentences into SQL queries, making it easier to interact with databases using a natural language interface.
- **Customizable Configuration**: The use of dotenv allows you to configure database credentials and settings without hardcoding them into the script.
- **Natural Language Processing**: langchain and HuggingFaceHub enable the parsing of English sentences and the generation of corresponding SQL queries.

## Prerequisites

Before running the script, make sure you have the following libraries installed:

- Python 3.x
- dotenv
- langchain
- HuggingFaceHub

You can install these libraries using pip:

```bash
pip install dotenv langchain huggingface-hub
```

## Usage

1. Clone this repository to your local machine:

```bash
git clone https://github.com/yourusername/english-to-sql.git
```

2. Navigate to the project directory:

```bash
cd english-to-sql
```

3. Configure your database credentials and settings by creating a `.env` file and adding the necessary variables.

```env
DB_HOST=your_database_host
DB_USER=your_database_user
DB_PASSWORD=your_database_password
DB_NAME=your_database_name
```

4. Run the Python script:

```bash
python english_to_sql.py
```

5. Follow the prompts to enter an English sentence, and the script will convert it into an SQL query.

## Customization

You can customize the script to work with different database systems or adapt it to handle specific SQL dialects by modifying the `english_to_sql.py` script.

## License

This project is licensed under the Apache. See the [LICENSE.md](LICENSE.md) file for details.

