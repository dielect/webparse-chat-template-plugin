<div align="center"><a name="readme-top"></a>

<h1>LobeChat Template Plugin</h1>

---

![lobe-chat-plugin](./lobe-chat-plugin.png)

<B>Self-use LobeChat plugin collection, unofficial</B>
</div>

---

## Introduction

This project is a personal endeavor to create my own LobeChat plugin aimed at enhancing my chat experience. The motivation behind developing this repository stems from my status as a novice in Node.js and my interest in exploring LobeChat, a popular OpenAI client. By documenting my journey and the development process, this repository serves not only as a record of my learning but also as a resource to assist other beginners in navigating their way through similar projects.

## Why This Repository?

As someone new to Node.js, diving into the development of plugins for LobeChat presented itself as a challenging yet exciting opportunity. LobeChat, being an acclaimed OpenAI client, seemed like the perfect platform for me to try my hand at plugin development. This repository is a testament to my learning journey, offering insights and learnings that I hope will benefit other novices in the field. It's a place where I document my progress, challenges, and solutions, making it a practical guide for anyone looking to embark on a similar endeavor.


## Features

- [x] **Web Content Parsing**: Web content parsing tool, core based on readability.
   ```text
    https://lobe.composere.com/readability/manifest-openapi.json
   ```
- [x] **SearXNG Search**: Free networked search, based on the searXng implementation.
   ```text
   https://lobe.composere.com/searxng/manifest-openapi.json
   ```
## How to Use

To get started with using this plugin, please follow the steps below:

1. **Switch to the Develop Branch**

   Begin by switching to the develop branch of this repository to access the latest development features and updates.

2. **Start the Development Server**

   Use the following command to start the development server:

   ```bash
   npm run dev

3. **Integrate the Plugin with Your Custom Plugin JSON File**

      Once the development server is running, you can integrate this plugin into your LobeChat environment. To do so, you will need to specify the path to the plugin's manifest file in your custom plugin configuration. For web content parsing, for example, you can use:

    ```plain text
    http://localhost:3080/readability/manifest-openapi.json
    ```
   ![How to Install](./how-to-install.png)

Replace the URL with the appropriate path where your development server is running and the plugin's manifest file is accessible.

By following these steps, you should be able to seamlessly integrate and start using the plugin with LobeChat to enhance your chat experience.

<B>This section provides clear and concise instructions on how to use your plugin, tailored to your requirements. Feel free to adjust any part of it to better fit your project's setup or naming conventions.</B>

---

## INSTALL
**Docker**

[official reference](https://github.com/vercel/next.js/blob/canary/examples/with-docker/Dockerfile)

```shell
git clone https://github.com/dielect/lobechat-template-plugin.git

cd lobechat-template-plugin/

docker build -t lobe-chat-plugin .

docker run -e PRESET_TOKEN=<your token> -d -p 3080:3080 lobe-chat-plugin
```


## License

[Mit License](./LICENSE)

## Acknowledgments

[searXng](https://github.com/searxng/searxng)
[readability](https://github.com/mozilla/readability)
