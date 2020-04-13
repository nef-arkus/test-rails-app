<a href="https://www.twilio.com">
  <img src="https://static0.twilio.com/marketing/bundles/marketing/img/logos/wordmark-red.svg" alt="Twilio" width="250" />
</a>

This application example demonstrates how to do simple phone verification with Ruby on Rails Framework, and Twilio Verify.

![](https://github.com/TwilioDevEd/verify-v2-quickstart-rails/workflows/Ruby/badge.svg)

> We are currently in the process of updating this sample template. If you are encountering any issues with the sample, please open an issue at [github.com/twilio-labs/code-exchange/issues](https://github.com/twilio-labs/code-exchange/issues) and we'll try to help you.

## Local Development

1. Clone the project and cd into it.
    ```bash
    git clone ...
    cd verify-v2-quickstart-rails/
    ```

1. Copy `.env.example` to `.env` to setup you environment.
    ```bash
    cp .env.example .env
    ```

1. Edit `.env` to add your Twilio access keys. For Twilio API credentials find [here](https://www.twilio.com/console) and for Verification Service SID [here](https://www.twilio.com/console/verify/services).
    ```
    TWILIO_ACCOUNT_SID=ACXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
    TWILIO_AUTH_TOKEN=7axxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
    TWILIO_VERIFICATION_SID=VAXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
    ```

1. Install gem dependencies
    ```bash
    bundle install
    ```

1. Run migrations to create the database.
    ```bash
    rails db:migrate
    ```

1. Run the application.
    ```bach
    rails server
    ```

1. Check it out at [http://localhost:3000](http://localhost:3000)


That's it!

## Run the tests

1. Run minitests

    ```bash
    rails test
    ```

## Meta

* No warranty expressed or implied. Software is as is. Diggity.
* The CodeExchange repository can be found [here](https://github.com/twilio-labs/code-exchange/).
* [MIT License](http://www.opensource.org/licenses/mit-license.html)
* Lovingly crafted by Twilio Developer Education.
