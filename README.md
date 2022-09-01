# Robot War Body

This is the source for the Robot War body that allows to mount two motors to a
Development kit.

## Source

[![GitHub Actions](https://github.com/nordicplayground/robot-war-body/workflows/Test%20and%20Release/badge.svg)](https://github.com/nordicplayground/robot-war-body/actions)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)
[![Renovate](https://img.shields.io/badge/renovate-enabled-brightgreen.svg)](https://renovatebot.com)
[![Mergify Status](https://img.shields.io/endpoint.svg?url=https://api.mergify.com/v1/badges/nordicplayground/robot-war-body)](https://mergify.io)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://github.com/prettier/prettier/)
[![ESLint: TypeScript](https://img.shields.io/badge/ESLint-TypeScript-blue.svg)](https://github.com/typescript-eslint/typescript-eslint)
[![React](https://github.com/aleen42/badges/raw/master/src/react.svg)](https://reactjs.org/)
[![Vite](https://github.com/aleen42/badges/raw/master/src/vitejs.svg)](https://vitejs.dev/)

The model was developed using [JSCAD](https://github.com/jscad/JSCAD.org), it
can be viewed in the browser
[here](https://nordicplayground.github.io/robot-war-body/).

![3D Model](./artifacts/3d-model.png)

### Set up

    npm ci

### Running

    npm start

## Sliced model

- [Step file](./artifacts/robot-body.stl)
- [Prusa Slicer Project](./artifacts/robot-body.3mf), configured for
  [Creality CR-10 Smart](https://www.creality.com/products/creality-cr-10-smart-3d-printer)
- [GCode for Creality CR-10 Smart](./artifacts/robot-body_3h37m_0.20mm_210C_PLA_CR10SMART.gcode)

![Sliced Model](./artifacts/sliced-model.png)

## Printed and assembled robot

![Top](./artifacts/robot-top.png)

![Bottom](./artifacts/robot-bottom.png)
