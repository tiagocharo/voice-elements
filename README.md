# &lt;voice-elements&gt;

> Web Component wrapper to the [Web Speech API](https://dvcs.w3.org/hg/speech-api/raw-file/tip/speechapi.html), that allows you to do voice recognition (speech to text) and speech synthesis (text to speech) using [Polymer](http://www.polymer-project.org/).

## Demo

[Check it live!](http://zenorocha.github.io/voice-elements)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install voice-elements --save
```

Or [download as ZIP](https://github.com/zenorocha/voice-elements/archive/gh-pages.zip).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/voice-elements/dist/voice-player.html">
    <link rel="import" href="bower_components/voice-elements/dist/voice-recognition.html">
    ```

3. Start using it!

    ```html
    <voice-player></voice-player>
    <voice-recognition></voice-recognition>
    ```