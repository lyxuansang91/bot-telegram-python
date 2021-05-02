## Requirements

- Python 3.5.x or above.

## Installation

- pip3 install venv
- python3 -m venv venv
- pip install -r requirements.txt

### How to srape user from telegram

Modify api_hash, api_id, and phone and run following command:

```bash
python scrape_user_from_telegram.py
```

Reference: https://python.gotrained.com/scraping-telegram-group-members-python-telethon/

### How to add user to telegram group

Modify api_hash, api_id, and phone and run following command:

```bash
python add_user_to_telegram_group.py <read_file_name>.csv
```

Reference: https://python.gotrained.com/adding-telegram-members-to-your-groups-telethon-python/
