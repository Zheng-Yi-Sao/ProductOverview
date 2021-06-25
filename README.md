# Project Name

> Amazon Item Page Clone

## Related Projects

  - https://github.com/Zheng-Yi-Sao/ProductGallery
  - https://github.com/Zheng-Yi-Sao/ProductInformation
  - https://github.com/Zheng-Yi-Sao/CustomerReviews

## Table of Contents

1. [Usage](#Usage)
1. [Requirements](#requirements)
1. [Development](#development)

## Usage

> The current setup is for a service running by Docker container. 
> To run locally without Docker:
> 1. Git clone the repo
> 2. Run npm install
> 3. Comment out line 4 - 9 in ProductOverview/database/index.js, use line 11 - 16
> 4. Run npm seed to seed the data
> 5. Replace environment variables with local host and the desired port
> 6. Run npm start
>

## Requirements

An `nvmrc` file is included if using [nvm](https://github.com/creationix/nvm).

- Node 6.13.0
- etc

## Development

### Installing Dependencies

From within the root directory:

```sh
npm install -g webpack
npm install
```

