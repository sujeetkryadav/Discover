## Introduction

1. Currently this application available with two different layout(Primary Colors (Red and Orange)).

2. For this, we have two separate Repositories.

3. Depends on requirement you can use any of them.


## Development server

1. Install `Node.js v8.11.4` on development machine.

2. Take the codebase.

2. Go to the project root directory.

3. Run `npm install` command to donwload all required dependencies.

4. Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

5. To run application on other port, run `ng serve --port <port-number>`

## Application configuration

Go to the `config.ts` (\src\app) file and modify the API URL 

## TO Change the logo

1. Copy and paste you logo in `src\assets\img` folder with size of `(1080 x 74)` pixels.

2. Open `config.ts` file and modify the logo name.

3. Save this file.


## Build

1. If you want run this application on root URL then Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Copy the content under `dist` and paste on server.

Example: https://13.59.115.99/#/ , Then Run `ng build`

2. If you want run this application inside folder then Run `ng build --base-href /<folder-name>/`. The build artifacts will be stored in the `dist/` directory.Copy the content under `dist` and paste on server.

Example: https://13.59.115.99/BPDA/#/ , Then run `ng build --base-href /BPDA/`

## Running unit tests

Run `ng test` to execute the unit tests.

