
# FiveM Script Generator

This is a simple **FiveM script generator** written in **C#**. It helps you quickly generate the necessary files for a basic FiveM resource. The program generates four essential files for your resource:

- `server.lua` - Server-side Lua script.
- `client.lua` - Client-side Lua script.
- `config.lua` - Configuration file for your resource.
- `fxmanifest.lua` - Metadata file for the resource, telling FiveM about your scripts.

The program is designed to make it easy to create a starting point for your FiveM resources by generating a basic file structure.

## Features

- Automatically creates the following Lua files:
  - `server.lua` (for server-side code)
  - `client.lua` (for client-side code)
  - `config.lua` (for configuration settings)
  - `fxmanifest.lua` (for metadata and resource configuration)
- Allows you to specify the directory where the files should be saved.
- Creates the directory if it doesn't exist.
- Simple and easy to use.

## Requirements

- **.NET SDK** (6.0 or higher) to run the C# program.
  - Download it from [here](https://dotnet.microsoft.com/download).

## How to Use

### 1. Clone the Repository

To get started, clone this repository to your local machine:

```bash
https://github.com/cavodexx/fivem-lua.git
cd your file
