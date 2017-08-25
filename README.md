# curl

## Simplified Command Reference

 Command                          | Description
----------------------------------|--------------------
`--basic`                         | basic authentication
`-d, --data <data>`	              | sends specified data in a POST request
`--data-ascii <data>`             | sends ascii data
`--data-binary <data>`            | sends binary data
`--data-raw <data>`               | sends raw data
`--data-urlencode <data>`         | sends urlencode data
`--cacert <CA cert>`              | CA certificate
`–capath <CA path>`               | CA certificate directory
`-H, --header <header>`           | extra header to include in request
`-i, --include`                   | includes HTTP-header in output
`-I, --head`                      | fetch HTTP-header only
`--interface <name>`              | uses specific interface (e.g. `--interface eth0:1`)
`-k, --insecure`                  | allows insecure requests (no cert check)
`-o, --output <file>`             | writes the output to a file
`-s, --silent`                    | don’t show progress meter or error messages
`-S, --show-error`                | opposite of -s, --silent
`-T, --upload-file <file>`        | uploads a file to the remote URL
`-u, --user <user[:password]>`    | specifies the user name and password
`-U, --proxy-user`                | specifies the user name and password for proxies
`-v, --verbose`                   | be more verbose/talkative during the operation
`-w, --write-out <format>`        | displays specific information after to be completed (`content_type, http_code, local_ip, local_port, num_redirects, redirect_url, remote_ip, remote_port, size_download, size_header, size_request, size_upload`)
`-X, --request <command>`         | specifies a custom method (GET, HEAD, DELETE etc)