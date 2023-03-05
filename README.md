# OpenAI ChatGPT Rust Cli

*WIP*

This takes the [OpenAI API](https://platform.openai.com/) and uses it as a cli that can help generate code or make suggestions.

This is mainly a small project to help myself learn rust.

### Code Completion

### Chat 

*To add WIP*

# Setup

This assumes you have an [OpenAI Developer Account](https://platform.openai.com/)


### Generate API Token 

[See here for instructions](https://platform.openai.com/account/api-keys)

After generating the token, set the env variable 
```
export OPENAI_API_KEY={API_KEY}
```

### Install via Cargo 

Via local repo
```
cargo install --path=/path/to/repo
```

Via github
```
cargo install git https://github.com/lyledean1/gptrs
```