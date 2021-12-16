# DB Notification Sender API

A simple Flask API to update our firebase database and alert user by sending notifications on the mobile device.

## Prerequisites
1. Get your firebase credentials/configuration file for python and Database URL from the firebase console and put it in the "files" folder.
2. Replace "[LINK_TO_CONFIGURATION_FILE](https://github.com/soumallyadev07/DB-Notification-Sender-API/blob/2ede14308913ae3dbb46b39e6e8e9bb4b4041bf1/app.py#L6)" with the actual link to the file in "app.py".
3. Replace "[DATABASE_URL](https://github.com/soumallyadev07/DB-Notification-Sender-API/blob/2ede14308913ae3dbb46b39e6e8e9bb4b4041bf1/app.py#L8)" with the actual URL in "app.py"

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the requirements.

```bash
virtualenv env
source env/bin/activate
pip install -r requirements.txt
```

## Usage

```bash
python app.py
```
The application will be started and it will start running on port - [6486](http://127.0.0.1:6486/)
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)