# awesome-wow-rust

> 🚨 We have a discord server! Please join if you'd like to get involved: https://discord.gg/RjSytaEuuX

Excellent resources for world of warcraft private servers in rust. There is still a lot of room for experimentation with a few differing approaches.
This resource will act like a hub to share ideas and experiment with alternatives.

## Servers

- [wrath-rs](https://github.com/Victov/wrath-rs): the most complete implementation, with movement in the world 
- [azerust](https://github.com/arlyon/azerust): an experiment into a modular high-tech server platform with interfaces over graphql and [tokio-console](https://github.com/tokio-rs/console)
- [wow_vanilla_server](https://github.com/gtker/wow_vanilla_server): experimental 1.12 server with no external dependencies other than `cargo run`.

## Libraries

- [wow-srp](https://github.com/gtker/wow_srp): wow's flavour of SRP-6 authentication
- [wow_login_messages](https://github.com/gtker/wow_messages): datastructures for the wow login server
- [wow_world_messages](https://github.com/gtker/wow_messages): message definitions and types for wow world server
- [wow_message_parser](https://github.com/gtker/wow_messages/tree/main/wow_message_parser): a pest-based parser for wow packets
- [wowm](https://gtker.com/wow_messages/): a DSL for the world of warcraft protocol, aiming to cover client / server for versions 1.x, 2.x, and 3.x
- [wow_dbc](https://github.com/gtker/wow_dbc): library for reading 1.12, 2.4.3, and 3.3.5 DBC files
