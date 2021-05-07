# Give Me Access
## where Me is [@kevinnls](https://github.com/kevinnls)

### What is this?
a script that can be run on your host to do the following automatically

1. create a new user `kevinnls` with separate home directory
	- and add @kevinnls' public key for remote authentication
2. [optional] grant user `kevinnls` sudo permissions
3. [if unavailable] install and enable `opensshserver`
4. [if unavailable] install [`ngrok`](https://ngrok.com/)
    - and authenticate with your own ngrok account
	- add an ngrok tunnel entry `kevinnls` in default config

### And then what?

You just have to run
```
ngrok start kevinnls
```
and keep it running to give me access. Pressing `Ctrl + C` or closing the terminal session will kill my access immediately.