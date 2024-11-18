
Demo shell script `hello.sh`
```sh
#!/bin/sh
echo 'Hello Shell...'
```

Download and run shell script in one line
```sh
curl -sLo- https://raw.githubusercontent.com/cuimingda/hello-shell/refs/heads/main/hello.sh | sh
```

Expected output
```plaintext
Hello Shell...
```