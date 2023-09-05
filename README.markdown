# Knuff
The debug application for Apple Push Notification Service (APNs).

Fix topic error(400) by optimize user interaction！

New UI as below:

![截屏2023-09-05 15.22.07](https://p.ipic.vip/aj1a36.png)

## Features
* Send push notifications to APNS (Apple Push Notification Service) very easily (no configuration needed at all)
* Load / Save documents including token and JSON payload
* Grabs the certificate right from your keychain
* Get the device token automatically; forget about manually retrieving the device token through logging or similar techniques. Even more useful when not in sandbox mode (requires [Knuff-Framework](https://github.com/KnuffApp/Knuff-Framework))
* Support for error response codes
* Detects Development/Production environment automatically
* Supports universal certificates
* Custom JSON payloads
* Identity export to PEM format (⌘ + E)

## Knuff iOS App

We created an iOS companion app to make it even easier to get up and running with APNs, download it from the [App Store](https://itunes.apple.com/us/app/knuff-the-apns-debug-tool/id993435856).

## Usage of automatic token detection (iOS8+)

To use this feature with your own apps, have a look at [Knuff-Framework](https://github.com/KnuffApp/Knuff-Framework)

## System Requirements

Due to the usage of the HTTP/2 protocol, Knuff only supports OS X El Capitan 10.11+

## License

Knuff is licensed under [The MIT License (MIT)](LICENSE).

## More Info

Have a question? Please [open an issue](https://github.com/KnuffApp/Knuff/issues/new)!
