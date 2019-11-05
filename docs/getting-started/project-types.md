---
id: project-types
title: Project Types
sidebar_label: Project Types
---

The following Project Types can be generated using `create-yoshi-app`:

## Client

Only Client project built with [React](https://reactjs.org/). The result is a bundle that will be uploaded to the cdn.

## Fullstack

A [Node.js](https://nodejs.org/en/) Server + Client project. The result is similar to the client, with a server that serves an html file which uses the created bundle.

## Node Library

A [Node.js](https://docs.npmjs.com/getting-started/creating-node-modules) module that should be used by other Node.js applications as a 3rd party dependency.

## Server

Only Server project

## Business Manager Module

A client project that integrate with business manager APIs.

## Out Of Iframe

An application that has it's view components written in React and run in the viewer.
The application business logic runs inside the platform worker.
For more information head to the [official docs](<https://bo.wix.com/wix-docs/client/client-frameworks#viewer-platform-(ooi)>).

---

For more information, see [the templates](https://github.com/wix/yoshi/tree/master/packages/create-yoshi-app/templates)
for those project types
