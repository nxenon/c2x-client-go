# C2X-Client-Go

[![Tool Category](https://badgen.net/badge/Tool/C2%20Client/black)](https://github.com/nxenon/c2x-client-go)
[![APP Version](https://badgen.net/badge/Version/Beta/red)](https://github.com/nxenon/c2x-client-go)
[![Go Version](https://badgen.net/badge/Go/1.13/blue)](https://golang.org/doc/go1.13)
[![License](https://badgen.net/badge/License/GPLv2/purple)](https://github.com/nxenon/c2x-client-go/blob/master/LICENSE)

C2x-Client-Go is client of [C2X](https://github.com/nxenon/c2x) (C2/Post Exploitation) project in Go language.

Installation & Building
----
    You have to first install Go version 1.13
    Run:
    git clone https://github.com/nxenon/c2x-client-go.git
    cd c2x-client-go
    edit c2x-client.go and put the server IP and Port in lines 20 and 21
    if you want the client to run in
    Linux :
    GOOS=linux go build c2x-client.go
    Windows :
    GOOS=windows go build c2x-client.go
    now you have c2x-client compiled.
    run it in target system and wait to connect to c2x server

