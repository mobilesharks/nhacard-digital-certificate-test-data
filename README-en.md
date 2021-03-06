![alt text](assets/img/flags/globe.png) [<u>Português</u>](README.md) <u>English</u>
<h1 align="center">
 NhaCard Certificado Digital
</h1>
<h2 align="center">
 Test Data Repository for NhaCard Validator mobile application
</h2>

<p align="center">
  <a href="#about">About</a> •
  <a href="#download">Download</a> •
  <a href="#repos">Repos</a> •
  <a href="#tests">Tests</a> •
  <a href="#faqs">FAQs</a>
</p>

## About

This repository contains test QR Codes to automate the testing of the NhaCard Validator application, the official application for validating NhaCard Digital Certificates with QR Code reading.

The entire validation process is done offline without implementing any Business Rules Engine, so it does not validate the veracity of the data present in the certificate, and the person responsible for reading is also responsible for validating the data presented by the citizen with those presented in the application.

## Download

Get the NhaCard Validator app on [Google PlayStore](https://play.google.com/store/apps/details?id=cv.nosi.app.nhacard.validator) and on [App Store](https://apps.apple.com/us/app/nhacard-validator/id1612251739).

## Repos

If you have the necessary permissions, access the development repositories:
* [Android](https://github.com/mobilesharks/nhacard-certificate-validator-android)
* [iOS](https://github.com/mobilesharks/nhacard-validator-ios)

## Tests

Test QR Codes for NhaCard Digital Certificates:

1. Valid certificates

   1.1. [Vaccine Certificate](CV/1.3.0/1/1.1)

   1.2. [Test Certificate](CV/1.3.0/1/1.2)

   1.3. [Recovery Certificate](CV/1.3.0/1/1.3)

2. [Certificate with unrecognized digital signature](CV/1.3.0/2)

3. [Expired certificate](CV/1.3.0/3)

4. [Invalid QR Code Content](CV/1.3.0/4)

## FAQs

#### How to use it?
Point the camera on your mobile device to scan the QR code of the displayed COVID Digital Certificate. The certificate can be presented in paper or digital format.
The app will automatically verify the certificate.

A green light result means the certificate has been successfully validated.
A result with a red signal means that the certificate has not been validated and the reason is given.

#### Protection against COVID 19
This application does not guarantee the security of the holder of the COVID Digital Certificate in relation to the COVID-19, nor its identity, serving only to validate the authenticity of the certificate.

#### Legal identification
The presentation of the COVID Digital Certificate does not serve as a form of identification of the bearer, always lacking the presentation of a valid and legitimate official identification document.

#### Camera usage
The application uses the device's camera exclusively to scan the QR Code, with prior consent.

#### Personal Data Protection
The display of personal data in the QR Code is temporary in the application, not allowing them to be stored, and the application user undertakes not to store this data by any other means.

#### Rights of the holder
The certificate holder can freely show the QR Code of his digital certificate to the application user. By deciding to do so, the titleholder will be communicating their identity data and content of the certificate to that person, the user of the application.
