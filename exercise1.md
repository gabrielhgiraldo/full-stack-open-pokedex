# chosen language: Python

## Linting Testing and Building

### linting

Lynting in python is often handled by pylint and/or flake8 in a linting script, manually through the commandline, and through the IDE such as Visual Studio Code via extensions.

### testing

Testing in Python is often handled via pytest or unittest libraries.

### building

Since python is an interpreted language, there is usually no building. However, since there can be C extensions to the python library some packages may need to be built.

## CI CD Alternatives

### Gitlab-CI

gitlab-ci is a popular alternative to jenkins. Although it doesn't have the flexibility of Jenkins, it is much easier of a setup for simple gradle builds/publish to docker projects.

## Self-Hosted vs Cloud

This setup would be better in a cloud environment since it's a small team of just 6 people, thus there probably is not as much funding to pay for large upfront hardware expenses necesarry for a self-hosted cloud. Furthermore, since it is just in development stages and not yet released, it would classify as a startup, which means it could grow or just as easily faily making the flexibility of a cloud hosted system necessary to avoid losses in having to either overpay for too large or too small of a system or complete loss of the hardware investments in case of a failure.a
