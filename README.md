# Shuffle
A cool lil music bot :)

# Setup

First of all make sure you have python 3.10+
1. Install poetry
2. Configure IDE venv and poetry
3. Install necessary packages using the command below
4. Create `.env` file with required variables set (table below)
```shell
$ poetry install
```
## `.env` variables

All variables are required. (except either `PGSQL_URL` or other database env vars are required)

|   Key    |  Description  |  Type   |
| -------- |  -----------  | ------- |  
| LL_ADDRESS | The lavalink address to conect the bot | str (must prefixed with `http`/`https`) | 
| LL_PORT | The Lavalink address' port | int (default: `8000`) | 
| LL_PASSWORD | The password to authorize to ll server | str (default: `"youshallnotpass"`) | 
| PGSQL_URL | Special url to connect to postgres db. Use this or use other env vars | str (default: `None`) | 
| USER | Database name to connect | str (default: `music`) | 
| PASSWORD | Database password | str | 
| HOST | Database host | str (default: `127.0.0.1`) | 
| PORT | Database port | int (default: `5432`) |
| TOKEN | Bot's token | str |

# For Collaborators

Yall are free to open pr :3