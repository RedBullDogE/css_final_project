# Exploratory Data Analysis of Telegram Messages

This repository contains a notebook with analysis of Telegram data collected using this [tool](https://github.com/SanGreel/telegram-data-collection) by SanGreel.

To use it you need:

1. Clone this repo to your local machine.
2. Collect your Telegram data (dialogs and meta) with the script mentioned above.
3. Set paths to the data in the following variables: `DIALOGS_MERGED_DATA_PATH`, `DIALOGS_META_MERGED_DATA_PATH`.
    * For convenience, I advise you to create a data folder in the root of the repository right next to the notebook and insert CSV files there.
4. Check your Telegram ID (e.g. with [this](https://t.me/getmyid_bot) bot) and put in the `chat_id` variable.
5. Run the notebook.

It will take some time to process all sections.

You can freely change any sections, remove unnecessary and add new ones.