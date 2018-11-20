# LUISBot Sample

[Language Understanding](https://www.luis.ai/) を利用する、シンプルな NLP Chatbot サンプルです。

*Simple NLP Chatbot using [Language Understanding](https://www.luis.ai/).*

# How to use

## Config Settings

Language Understanding(LUIS) で app を作成します。設定に必要な値は 'MANAGE' ページにあります。
こちらのサンプルの nlp-with-luis.bot (bot setting file) を開き、下記の値を、作成した LUIS app の情報に入れ替えます。

*Create Language Understanding(LUIS) app, go to 'MANAGE' page to see configuration.
Open nlp-with-luis.bot (bot setting file) of this sample, and replace these values below to your LUIS app's ones.*

- YOUR_YOUR_LUIS_APPID
- YOUR_LUIS_AUTHORING_KEY

## Install & Run

必要なモジュールを npm でインストールします。
*Intall modules using npm*
>npm i

適時モジュールのアップデートを行ってください。
*Update modules using npm periodically*
>npm update

起動して、Bot Framework Emulator などからアクセスします。
*run and access from Bot Framework Emulator etc*
>npm start