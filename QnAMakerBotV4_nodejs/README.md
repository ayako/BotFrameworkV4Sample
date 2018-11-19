# QnAMakerBot Sample

[QnAMaker](https://www.qnamaker.ai/) を利用する、シンプルな FAQ Chatbot サンプルです。

*Simple FAQ Chatbot using [QnAMaker](https://www.qnamaker.ai/).*

# How to use

## Config Settings

QnA Maker で app を作成します。設定に必要な値は 'SETTINGS' ページにあります。
こちらのサンプルの qnamaker.bot (bot setting file) を開き、下記の値を、作成した QnA Maker app の情報に入れ替えます。

*Create QnA Maker app, go to 'SETTINGS' page to see configuration.
Open qnamaker.bot (bot setting file) of this sample, and replace these values below to your QnA Maker app's ones.*

- YOUR_QNAMAKER_KEY
- YOUR_QNAMAKER_KNOWLEDGEBASE_ID
- YOUR_QNAMAKER_NAME

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