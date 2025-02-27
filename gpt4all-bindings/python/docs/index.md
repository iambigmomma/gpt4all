# GPT4All Documentation

GPT4All runs large language models (LLMs) privately on everyday desktops & laptops.

No API calls or GPUs required - you can just download the application and [get started](gpt4all_desktop/quickstart.md#quickstart).

!!! note "Desktop Application"
GPT4All runs LLMs as an application on your computer. Nomic's embedding models can bring information from your local documents and files into your chats. It's fast, on-device, and completely **private**.

    <div style="text-align: center; margin-top: 20px;">
        [Download for Windows](https://gpt4all.io/installers/gpt4all-installer-win64.exe) &nbsp;&nbsp;&nbsp;&nbsp;
        [Download for Mac](https://gpt4all.io/installers/gpt4all-installer-darwin.dmg) &nbsp;&nbsp;&nbsp;&nbsp;
        [Download for Linux](https://gpt4all.io/installers/gpt4all-installer-linux.run)
    </div>

!!! note "Python SDK"
Use GPT4All in Python to program with LLMs implemented with the [`llama.cpp`](https://github.com/ggerganov/llama.cpp) backend and [Nomic's C backend](https://github.com/nomic-ai/gpt4all/tree/main/gpt4all-backend). Nomic contributes to open source software like [`llama.cpp`](https://github.com/ggerganov/llama.cpp) to make LLMs accessible and efficient **for all**.

    ```bash
    pip install gpt4all
    ```

    ```python
    from gpt4all import GPT4All
    model = GPT4All("Meta-Llama-3-8B-Instruct.Q4_0.gguf") # downloads / loads a 4.66GB LLM
    with model.chat_session():
        print(model.generate("How can I run LLMs efficiently on my laptop?", max_tokens=1024))
    ```

# Chatbot Page

<script async
  src="https://agent-4e0381cb37857df874e6-qtpuf.ondigitalocean.app/static/chatbot/widget.js"
  data-agent-id="673bafb4-f488-11ef-bf8f-4e013e2ddde4"
  data-chatbot-id="HFNt2h6GtISQ6uqtrDP_KY8Rwqs26mzs"
  data-name="Nomic GPT4All Chatbot"
  data-primary-color="#031B4E"
  data-secondary-color="#E5E8ED"
  data-button-background-color="#0061EB"
  data-starting-message="Howdy! How can I help you today?"
  data-logo="https://media.licdn.com/dms/image/v2/C4D0BAQGp5DCbeBqfog/company-logo_200_200/company-logo_200_200/0/1653426686688/nomic_ai_logo?e=2147483647&v=beta&t=npsShQlvN7I9iD42R04pl9_kM51OwHFTA2_mDTNN8cU">
</script>
