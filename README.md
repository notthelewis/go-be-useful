# go-be-useful

A collection of Go libraries and tools to make you go and be useful.

## Table Of Contents

**[Net](#Net)**
**[Data](#Data)**
**[CLI](#CLI)**
**[Misc](#Misc)**
**[Tools](#Tools)**

## Disclaimer

> I opt for rolling my own most times. This repo is not to promote my own libraries. None of my own internal libs are
> listed here as of now. If I do add any libs in, I'll be sure to distinguish them accordingly. 

All credit goes to the authors of the libs themselves. This is a useful cheat sheet of libs I've used in my own work and
gained great benefit from at least once. Some of these libraries are must-haves for every project, others I've just used
for niche things and I've found them to do these things better than competitors.

It's not exhaustive. If you're looking for an exhaustive list of libraries spanning various domains, check out:
[this link](https://github.com/avelino/awesome-go?tab=readme-ov-file).


## Net

| Package Name      | Purpose                           | Package Link                                 |
|:-----------------:|:----------------------------------|:--------------------------------------------:|
| shmipc-go         | Shared memory IPC server          | https://github.com/cloudwego/shmipc-go       |
| httprouter        | Extremely high perf http req mux  | https://github.com/julienschmidt/httprouter  |
| gnet              | epoll+kqueue-based networking     | https://github.com/panjf2000/gnet            |
| jwt-go            | JSON Web Token (JWT) lib          | https://github.com/golang-jwt/jwt            |
| sse               | Server Side Events handling       | https://github.com/r3labs/sse                |

## Data

| Package Name     | Purpose                                           | Package Link                                  |
|:----------------:|:--------------------------------------------------|:---------------------------------------------:|
| go-json          | Shits all over encoding/json                      | https://github.com/goccy/go-json              |
| flatbuf          | High-entropy format with zero encode/decode cost  | https://github.com/google/flatbuffers         | 
| protobuf         | > JSON, < flatbuf, x-platform, easy to use        | https://github.com/protocolbuffers/protobuf   |
| go-qrcode        | Flexible QR Code generation                       | https://github.com/yeqown/go-qrcode           |
| bitmap           | SIMD enabled bitmap                               | https://github.com/kelindar/bitmap            |
| fsm              | Finite State Machine lib                          | https://github.com/cocoonspace/fsm            |
| nats             | lightweight, high perf messaging                  | https://github.com/nats-io/nats.go            |
| sqlite           | High perf sqlite lib                              | https://github.com/crawshaw/sqlite            |
| go-sqlite3       | OG sqlite3 lib. Good enough for nearly everyone   | https://github.com/mattn/go-sqlite3           |
| go-sqlite-bench  | **Not a lib** - just a comparrison of sqlite libs | https://github.com/cvilsmeier/go-sqlite-bench | 
| goqu             | Expressive SQL builder                            | https://github.com/doug-martin/goqu           |

## CLI 

| Package Name      | Purpose                                      | Package Link                                |
|:-----------------:|:---------------------------------------------|:-------------------------------------------:|
| Cobra             | Simple, flexible CLI builder                 | https://github.com/doug-martin/goqu         |
| Bubble Tea        | Rich TUI lib                                 | https://github.com/charmbracelet/bubbletea  |
| Lip Gloss         | Style definitions for nice terminal layouts  | https://github.com/charmbracelet/lipgloss   |

## Misc

| Package Name | Purpose                                           | Package Link                                    |
|:------------:|:--------------------------------------------------|:-----------------------------------------------:|
| dbus         | Nice lib for working with D-Bus  system           | https://github.com/godbus/dbus                  |
| Viper        | Slick configuration management: JSON/YAML/TOML    | https://github.com/spf13/viper                  |
| go-tg        | Telegram bot api lib                              | https://github.com/mr-linch/go-tg               |
| Zap          | Rapid logging, flexibble interface                | https://github.com/uber-go/zap                  |
| Cron         | Nice lib for working with cron expressions        | https://github.com/robfig/cron                  |
| gosseract    | OCR library                                       | https://github.com/otiai10/gosseract            |
| ants         | Goroutine pooling                                 | https://github.com/panjf2000/ants               |
| errgroup     | Waitgroup + error handling                        | https://pkg.go.dev/golang.org/x/sync/errgroup   |
| argon2       | Should be default for storing pw                  | golang.org/x/crypto/argon2                      |

## Tools 

| Tool Name  | Purpose                            | Package Link                     |
|:----------:|:-----------------------------------|:---------------------------------|
| Hugo       | Static site generator. Easy, quick | https://github.com/gohugoio/hugo |

