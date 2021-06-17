# micro.blog CLI

### Installation & Configuration

1. Clone the repository

2. Make `microblog` executable
```
chmod +x microblog
```
3. Copy/link `microblog` to `/usr/local/bin` or add
the repo directory to your `$PATH`

4. Create an app token on [this page](https://micro.blog/account/apps)

5. You can store the app token in `$HOME/.config/microblog.conf`
`echo "TOKEN=<app token value" > $HOME/.config/microblog.conf`
Otherwise, prepend the command with `TOKEN=<app token value> microblog ["some text"]`

### Commands
`microblog ["some text"]`
