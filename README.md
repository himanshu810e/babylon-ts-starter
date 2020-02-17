# babylon.js Typescript Starter

Access the sample app online 
https://himanshu810e.github.io/babylon-ts-starter/

This Repository contains a sample BABYLON.js application.

## Setup

`npm install`

## Running

`npm start`

## Build

 `npm run build`

## Structure

- `src/` *source code folder*

    - `index.ts` *application entry point*

    - `glsl.d.ts` *typescript definition file to resolve .glsl files*

    - `Materials/` *folder for custom materials/shaders*

        - `SampleMaterial.ts` *sample custom material*

        - `Shaders/` *folder containing GLSL shader code*

            - `Sample/` *folder containing sample shader* 

                - `sample.fragment.glsl` *sample fragment shader*

                - `sample.vertex.glsl` *sample vertex shader*

- `public` *folder containing static assets*

    - `index.html` *HTML entry point*

- `dist` *folder containing build output*
