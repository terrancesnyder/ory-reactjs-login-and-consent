## Summary

This project gives a boilerplate starter for implementing an ORY hydra and kratos login and consent flow. With some extra bits;

## Extras

* Consent attributes are merged with a consent dictionary, this enables the consent screen to show extra additional details and higher transparency. Its up to you to create an API endpoint that returns the available consent scopes and the mapping to their descriptions, names, etc.
* Webhook - When consent is granted or revoked we send a custom WEB hook containing the consent scopes and identity information. This is useful for consent tracking systems and historical tracking for a user privacy page, etc.

## Disclaimer

This isn't ready for production or is production quality. Just initial POC work.

## Getting Started

npm install
./run.sh
