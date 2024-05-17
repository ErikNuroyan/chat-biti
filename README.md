# chat-biti

## Setup

In order to clone the repository please run the following commands in the directory you want to clone to:

```{shell}
git clone --recurse-submodules https://github.com/ErikNuroyan/chat-biti
cd chat-biti
```

## Nginx

Please run the following following commands to place the Nginx configuration file in the right directory and run Nginx.

```{shell}
sh ./api-gateway/setup.sh
nginx
```

Note: Currently supported only for Linux and MacOS.

## Front End
Please follow the steps in ReadMe for [this](https://github.com/NorikKhachatryan01/ai_assistant/tree/bbe3e3249e49dab9322dd288de68b21b5091288c) repository.

## User Service
Please follow the steps in ReadMe for [this](https://github.com/ErikNuroyan/user-service/tree/f710cdfc06746822a63d724e11859c5089237e38) repository.

## ML Service
Please follow the steps in ReadMe for [this](https://github.com/sahNarek/chat/tree/4f67672521d320725d18ced25c069f267fee1082) repository.
