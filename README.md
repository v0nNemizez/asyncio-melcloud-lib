# Project Name: asyncio-melcloud-lib

## Description:
This project is a Python library that provides an asynchronous interface for interacting with the MelCloud API. It allows users to control and monitor Mitsubishi Electric air conditioning units remotely using asyncio.

## Features:
- Asynchronous API calls for improved performance and responsiveness.
- Support for authentication and authorization with the MelCloud API.
- Ability to control and monitor multiple air conditioning units.
- Comprehensive documentation and examples for easy integration.

## Installation:
To install the asyncio-melcloud-lib library, simply run the following command:

```
pip install asyncio-melcloud-lib
```

## Usage:
To get started with the asyncio-melcloud-lib library, import it into your Python project:

```python
import asyncio_melcloud_lib
```

Then, create an instance of the `MelCloudClient` class and authenticate with your MelCloud credentials:

```python
client = asyncio_melcloud_lib.MelCloudClient(username='your_username', password='your_password')
await client.login()
```

Once authenticated, you can use the various methods provided by the library to control and monitor your air conditioning units.

## Examples:
Here are a few examples to help you get started:

- Get a list of all available devices:

```python
devices = await client.get_devices()
```

- Set the temperature of a specific device:

```python
await client.set_temp(device_id='device_id', temperature=22)
```

- Get the current temperature of a specific device:

```python
temperature = await client.get_temperature(device_id='device_id')
```

For more examples and detailed documentation, please refer to the [official documentation](https://github.com/your_username/asyncio-melcloud-lib).

## Contributing:
Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request on the [GitHub repository](https://github.com/your_username/asyncio-melcloud-lib).

## License:
This project is licensed under the MIT License. See the [LICENSE](https://github.com/your_username/asyncio-melcloud-lib/blob/main/LICENSE) file for more information.
