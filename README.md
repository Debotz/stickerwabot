## Installation 📑

- Clone Repository
  ```sh
  git clone https://github.com/Debotz/stickerwabot.git
  ```
- Install Modules
  ```sh
  npm install
  ```
- Start
  ```sh
  npm start
  ```

## Configuration 🗝

- [config.json](https://github.com/Debotz/stickerwabot/blob/master/config/config.json)

  ```json
  {
    "name": "StickerDZ",
    "author": "@Debotz",
    "prefix": "!",
    "timezone": "Asia",
    "groups": true
  }
  ```

  - config.name : _name for the sticker_ (string)
  - config.author : _name for sticker maker_ (string)
  - config.prefix : _prefix for command_ (string)
  - config.timezone : _timezone displays the time at the specified location_ (string)
  - config.groups : _to filter whether bots can respond to group chats or not_ (boolean)

- [console.txt](https://github.com/Debotz/stickerwabot/blob/main/config/console.txt)

  ```txt
    /$$$$$$   /$$     /$$           /$$                           /$$$$$$$   /$$$$$$  /$$$$$$$$
   /$$__  $$ | $$    |__/          | $$                          | $$__  $$ /$$__  $$|__  $$__/
  | $$  \__//$$$$$$   /$$  /$$$$$$$| $$   /$$  /$$$$$$   /$$$$$$ | $$  \ $$| $$  \ $$   | $$
  |  $$$$$$|_  $$_/  | $$ /$$_____/| $$  /$$/ /$$__  $$ /$$__  $$| $$$$$$$ | $$  | $$   | $$
   \____  $$ | $$    | $$| $$      | $$$$$$/ | $$$$$$$$| $$  \__/| $$__  $$| $$  | $$   | $$
   /$$  \ $$ | $$ /$$| $$| $$      | $$_  $$ | $$_____/| $$      | $$  \ $$| $$  | $$   | $$
  |  $$$$$$/ |  $$$$/| $$|  $$$$$$$| $$ \  $$|  $$$$$$$| $$      | $$$$$$$/|  $$$$$$/   | $$
  \______/   \___/  |__/ \_______/|__/  \__/ \_______/|__/      |_______/  \______/    |__/
  ```

  You can replace ascii in https://patorjk.com/software/taag/

## Features 📋

|                  Features                   | Status |
| :-----------------------------------------: | :----: |
|              Image to Sticker               |   ✅   |
|              Video to Sticker               |   ✅   |
|               Gif to Sticker                |   ✅   |
|              Sticker to Image               |   ✅   |
|              Sticker to Video               |   ❎   |
|    Change Sticker Name & Sticker Author     |   ✅   |
| Prefix can be set in the config/config.json |   ✅   |
|       Supports Reply Image to Sticker       |   ✅   |
|       Supports Reply Video to Sticker       |   ✅   |
|        Supports Reply Gif to Sticker        |   ✅   |
|      Supports Reply Stickers to Images      |   ✅   |

## Commands 💭

  <table class="tg">
    <thead>
      <tr>
        <th class="tg-0pky">Commands</th>
        <th class="tg-0pky">Description</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td class="tg-0pky">!sticker</td>
        <td class="tg-0pky">Make Image/Video/Gif into Sticker. You can also send Image/Video/Gif into Sticker directly without Command. [in the Caption or Reply message]</td>
      </tr>
      <tr>
        <td class="tg-0pky">!image</td>
        <td class="tg-0pky">Make Sticker into Image. You can also send Image/Video/Gif into Sticker directly without Command. [in the Reply message]</td>
      </tr>
      <tr>
        <td class="tg-0pky">!change &lt;name&gt; | &lt;author&gt;</td>
        <td class="tg-0pky">Change Sticker Name &amp; Sticker Author as you wish. [in the Reply message]</td>
      </tr>
    </tbody>
  </table>

## Warning 🚧

<p id="warning">Only works on Windows, MacOS, and Linux. <b>Can't work on Android/Termux</b>!</p>
