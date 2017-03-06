# Alexa Skill Test

Alexa Skill Test provides a live server for local testing of Alexa Skills written in Node.js. Right now, testing skills usually involves going through the [Amazon Alexa Developer Portal](https://developer.amazon.com/alexa). This project makes testing much easier.

## Requirements

* Node/npm
* An Amazon Alexa Skill built using the [https://github.com/alexa/alexa-skills-kit-sdk-for-nodejs](Alexa Skill Kit SDK for Node.js)

## Install

It's recommended to install Alexa Skill Test as a global npm package:

`npm install -g alexa-skill-test`

After install, the `alexa-skill-test` command will be available to you.

## Usage

Within your terminal, change directory to your valid Amazon skill. Your skill will need a `package.json` and a main script file. Run the following command:

`alexa-skill-test`

This starts up a local testing server using your Alexa skill.

In your browser navigate to `http://localhost:3000`. You should see a simple UI for sending test requests to your skill.

## License

MIT